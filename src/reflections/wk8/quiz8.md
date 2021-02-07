# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The Package.json file is used for holding metadata relevant to the project. It gives information to npm so that when npm i is called it can install the correct things from off the web. All of the dependancies are located here.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
The package.json file needs to be a top level file so that it can be easily found for deployment. Also so that it can be one of the first things to be read in deployment.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
I believe that the proper command here is in the npm i. Alternatively it comes pre loaded in our template for a project.
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
The .env file and the auth config files are used to provide applications the specific environment data.
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can go to Heroku and look at them there by selecting view logs. Or you can navigate to it from the command line.
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Developers can manually updated the app inside of their Heroku account. Something else that is also needed is to log in to Github.
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is a super helpful and useful tool to control the version of the app that is live. Developers can have a fully functioning clean app working, and by working on a development branch they can make updates while the working version is still live. They can also test the new branch locally and make sure that the site does not go down to bad code. Even if this happens, branching can help with providing a line to fall back on if something goes wrong. This can help companies save a lot of money if done correctly.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Code review should happen all the time, but it should definitely, 100 percent of the time happen before a developement branch goes live.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
The term Merging is used to define combining two branches.
```
