# Day 13
__12/16/2020__

## What are the two common operations that we will set in the handler?

The two most common operations that are used in Proxy work are get and set. Get has two parameters the object and the property being accessed, while the set opperator has three parameters and they are the object, the property being accessed and the value being set for that property. Using both of these in a proxy will trigger traps that act like a domino effect manipulating data in a cascade.


## What do you have to make sure you are doing with every Get to insure the value does not become undefined?

To ensure that the value that is accessed with the Get function does not become undefined a developer must make sure to not override the get function. To do that is fairly simple. Parameters must be passed to the Get function. The object and then the property being accessed on that object. Then the developer must tell that get function to return the obj[prop].


## What are some of the benefits of the proxy object that we are using in our structure for applications?

The benefits of the proxy object that we are using in our structure for applications are huge. We are using the proxy object to have a core set of data and we are accessing the proxy without actually manipulating the core data. We are creating a variable to be used accross our website. This will make structuring and accessing certain pieces of information much much easier. We as budding developers are making a very good structre for us to build on and not have to repeat certain code over and over again. This still does not make one hundred percent sense to me but this article helped a lot. 
