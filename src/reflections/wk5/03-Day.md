# Day 23
__01/13/2021__

## In simple terms what is a sub-document?

A sub document is a document that is nested inside of another document. Like an array of moves inside of a character model. The moves have names and keys to activate them listed in the data. The character also has a name and more data that pertains to it. Alternatively it could be a schema that is nested inside of another schema. The schema for the moves could be brought into the character model.


## When might you use a sub-document?

The times that developers could use a sub document are many. The primary instance that I can think about is when data (and the relationships for that data) become more and more complex. When there are multiple objects or information that have multiple parts is when I believe that using sub-documents will be most helpful. This is because ultimately we want to group all of the like data together, but we do not want to have massive massive objects being returned every single time a simple request is comming in. We only want to have to provide exactly what the user is asking for.


## How do you add to a collection of sub-documents? What about editing them?

To add to a collection of sub-documents first a developer must find the document that they wish to change. Then if there is an array that they are wanting to add to they need to grab the array. If not then the change can be made to whatever property that they desire to change. That step is the same if the property is the only thing being changed. The final step to adding or editing to anything inside of a sub-document is to run a .save to save the change to the database.


## Afternoon Project Link:
https://steffenlarson.github.io/triviagame/