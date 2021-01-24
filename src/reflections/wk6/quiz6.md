# Understanding Persistent Relational Data

**1.** When using the Vue `cli` what is the command to initialize a project?
<!-- enter you answer in the space below -->
```
To initialize a project I run the bcw-create command. Then I select the Vue starter option.
```
**2.** Where can you find the scripts to startup you project on localhost?
<!-- enter you answer in the space below -->
```
We run npm i to install the dependancies, and then we run npm run serve. All of this is done in the command line.
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
A component allows developers such as myself to repeat data on a page. The self closing page and component tags are what injects each into the spots that they belong in. A v-for would also be very helpful for repeating elements on a page.
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
Templates, Scripts, and Styles tags.
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The letter 'L' represents the Liskov substitution principle. This means that Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program. Any class must be directly replaceable by any of its subclasses without error. The instances need to maintain all behavior from the base class and any new behaviors unique to the subclass.
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
Using the self closing div with the title of the page being injected in. The self closing div is what enables the router to plug in the page. The route or the URL that the page has is what gets plugged in. Each route also has a name that is registered in the router. And using the name instead of what the URL is saves developers from having to change the URL in every single spot that its needed. Instead we can just change it from the router once and the name remains the same.
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState is used for the whole application. The state in a component is only used locally, or on the page and component that it is inside of. 
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
Services still handle all of the business logic. They handle the actual requests and reponses from the apis. 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
Main.js has the root of our project still. Right beneath that is the App.vue.
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
I remember learning about this. I would like a refresher for this question. I know that it exists, but I do not remember what the actual tag is and I do not remember how to alter it to make the styling only local.
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
Reactive creates the watchable state. Computeds point the changing data towards the Reactive state and appstate.
```