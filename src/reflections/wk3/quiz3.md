# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The four pillars of Object Oriented Programming are Inheritance, Encapsulation, Abstraction, and Polymorphism.
Inheritance is sharing of information. Encapsulation which is grouping of information. Abstraction is hiding of information. Finally Polymorphism is redefining of information.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
I would access it by 
staff.property
That should target the name property of the object in staff.
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the separating of like information and data together. It allows for cleaner code and it helps with reading other peoples code. Encapsulation is a fantastic methodology in helping developers contain and organize their code in a way that makes sense and is easier to debug and read.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The S in the SOLID principles stands for single-responsibility principle. This means that classes should have one and only one job. There should be new functions and new classes to handle any other changes or manipulations to the data.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
The class is the blueprint or the ideal example of a class. This is what is created before any instances of said class to map out what each instance of this class will have included in its data. The instance of a class is an actual object. It is a unique individual that has all of the characteristics of the class that it comes from but it has its own unique values.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is an object that is essentially a copy of data that is used throughout a website or program that allows developers to manipulate and control the data without completely writing over the original data. This is incredibly helpful in making reusable code and not having to make new code based on every single change that happens.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
The purpose of the MVC pattern is to help developers organize, maintain, and debug their code quickly and efficiently. It helps developers incapsulate their code and it helps separate like types of code and data. It makes debugging code easier and quicker. It also organizes the code in such a way that there are many small batches of code, but no novel length code anywhere.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller in the MVC pattern acts as a communicating middle man. The only time that the page and the html are updated is when the controller tells it to. The controller also talks with the Service and it goes back and forth. The controller creates a barrier between data and the user, so that the user only has the information available to them that the developer allows theme to have.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service in the MVC pattern is responsible for all of the business logic. This means that any functions that are in the website or program are stored here. The controller speaks back and forth with the service to update the page based on how the user interacts with the page. The service houses all of the functions and busy work stuff.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The models job in the MVC pattern is to house the information that is cenetered around classes. The models are similar objects grouped together for encapsulation purposes. The models house the classes, the ideal versions of each object and some of the functions that go with creating new ones. The actual instances of the classes are usually stored in the local browser or a server.
```

