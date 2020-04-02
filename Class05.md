# Heroku 
Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP.

## Terminology:
* Preliminary: Applications consist of your source code and a description of any dependencies.
* Procfiles list process types - named commands that you may want executed.
* Deploying applications involves sending the application to Heroku using either Git, GitHub, or   via an API.
*  slug : a bundle of your source, fetched dependencies, the language runtime, and compiled/generated output of the build system - ready for execution.
*  Dynos are isolated, virtualized Unix containers, that provide the environment required to run an application.
* 

Heroku is a polyglot platform – it lets you build, run and scale applications in a similar manner across all the languages – utilizing the dependencies and Procfile. The Procfile exposes an architectural aspect of your application and this architecture lets you, for example, scale each part independently

## Deploying Applications 
The Heroku platform uses Git as the primary means for deploying applications
When you create an application on Heroku, it associates a new Git remote, typically named heroku, with the local Git repository for your application.

As a result, deploying code is just the familiar git push, but to the heroku remote instead:
```
git push heroku master

```

## Building Application 
When the Heroku platform receives the application source, it initiates a build of the source application. The build mechanism is typically language specific, but follows the same pattern, typically retrieving the specified dependencies, and creating any necessary assets (whether as simple as processing style sheets or as complex as compiling code).

The source code for your application, together with the fetched dependencies and output of the build phase such as generated assets or compiled code, as well as the language and framework, are assembled into a slug.

## Running Applications on dynos
Heroku executes applications by running a command you specified in the Procfile, on a dyno that’s been preloaded with your prepared slug
Generally, if you deploy an application for the first time, Heroku will run 1 web dyno automatically. In other words, it will boot a dyno, load it with your slug, and execute the command you’ve associated with the web process type in your Procfile.

You have control over how many dynos are running at any given time. Given the Procfile example earlier, you can start 5 dynos, 3 for the web and 2 for the queue process types, as follows:
```
heroku ps:scale web=3 queue=2

```

To understand what’s executing, you just need to know what dynos are running which process types:
```
heroku ps

```

(I used the site https://devcenter.heroku.com/articles/how-heroku-works#running-applications-on-dynos as extrea refrence about the subject)