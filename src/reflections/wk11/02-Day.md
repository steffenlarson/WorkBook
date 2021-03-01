# Day 52
__02/23/2021__

## What is the difference between a primary key and a foreign key?

Primary keys are the keys listed on a table that identify which specific instance that member of the table is. Foreign keys are placed on the end of the table and reference another table by that tables primary key. Everything will technically have a primary key, but tables that have no relationship will not have a fireign key.


## What is an Alias?

Aliases are used inside of JOIN statements in SQL statements. They are simply assigning a variable for a name of a table so that the code can be dry and readable. They are simply used for readabilities sake.


## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collection:

 CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorpatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
) 

internal IEnumerable<PatientDoctorPatientViewModel> GetByDoctorId(int id)
    {
      string sql = @"
      SELECT
      p.*
      dp.id as DoctorPatientId
      FROM doctorpatients dp
      JOIN patients p ON dp.patientId = p.id
      WHERE doctorId = @id
      ";
      return _db.Query<PatientDoctorPatientViewModel>(sql, new { id });
    }


## Afternoon Project Link:

https://steffenlarson.github.io/contractorapi/


## Reading: Dotnet Web APIs: Relationships