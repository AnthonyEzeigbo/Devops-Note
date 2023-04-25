# Devops-Note

Giving this scenerio, you thought about a great idea on how to solve the problem with the  traditional way of food ordering in a busy aiport, instead of the long lines and slow process of ordering your food, you came up with an idea of solving the frontline problem and reducing the long line by building an app to place your other and you get notified once its ready instead of standing in a long cue.

you will have to ask your self what steps to take to be able to achieve your goal.

there is a number of things that goes into building an App, you have to write the code,you have to host it and make sure the public can have access to it,it has to be scalable to meet up the demand and etc, first thing to do is to start with the development environment first.

*<ins>Development Environment</ins>*

You need a development environment when building out an application, your laptop or desktop can serve as your `Dev` environment and  you will like to chose whatever programming language you would like to use, every app has to be written in a programming language.

Lets assume that we are building our app on our laptop as our ` Dev Environment` using python as our programming language of choice, once we are done building it has to be hosted on our `local host 8080`, why ? because we are building everything locally. where it is accessable to the public but once we shortdown our laptop the app cant be reachable, so we need to host our app on a system that is never turnd off, so what do we do ?, we get a dedicated server for that and that where your production environment comes in.

*<ins>Production Environment</ins>*

Our Production Environment can be hosted in a Data center where our physical server is been housed which is be maintained by us or it can be in the cloud by a cloud provider AWS, Azure,Google Cloud where they maintain all the infrastructure.

If our application is written in a particular language for instance python, you must have the same programming language or runtime installed in your `Dev Environment` which is our laptop or desktop as same as the one in  the server also.
if your application uses any other libraries/dependecies, you must have all of it installed both on you laptop(Dev env) and the server too, and once all that is setup our application is ready to be run on the server.

Your app can now be accessed on the servers ip address, but you do not want your IP address to be public so you purchase a domain name and map your ip address to the domain name.

* workflow
our current workflow involves 
<ins>DevelopmentPhase</ins> : thats the phase where you write your code with your favourite text editor etc `VScode` or `Pycharm` on your laptop.

<ins>BuildPhase</ins> : the build pahse is the pahse where your convert your code that is written in a text format to an executable format, because the end user will not be able to run your App if it hasnt been converted.
we can convert our code in text format to executable formating, by using tools like `Maven` `Gradle` and for this tools to be invoked we have to write a build script
```
$./ build.sh 
```

once built the executable is then moved to the `production phase`

<ins>ProdcutionPhase</ins> : the production phase is in our server which could be at the data center or on the cloud, executable file is been run there and is refered to to be in a deploy state.

<ins>Git</ins>
Git helps all developers to work on the same application at the same time and collabrate efficiently.
Git is the underline technology that is been installed by the developer.

<ins>GitHub</ins>
Github is the publically hosted git based repository of codes, where you can configure project, organistions, users and define different access for different users.
