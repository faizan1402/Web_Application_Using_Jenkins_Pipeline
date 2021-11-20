# Wep_Application_Using_Jenkins_Pipeline

# What is Jenkins?
Jenkins is an open-source Continuous Integration server written in Java for orchestrating a chain of actions to achieve the 
Continuous Integration process in an automated fashion.Jenkins supports the complete development life cycle of software from 
building, testing, documenting the software, deploying, and other stages of the software development life cycle.

# How does Jenkins work?
Jenkins is a server-based application and requires a web server like Apache Tomcat to run on various platforms like Windows, Linux, 
macOS, Unix, etc. To use Jenkins, you need to create pipelines which are a series of steps that a Jenkins server will take. Jenkins 
Continuous Integration Pipeline is a powerful instrument that consists of a set of tools designed to host, monitor, compile and test code, 
or code changes, like:
# Advantages of using Jenkins:
-> Jenkins is being managed by the community which is very open. Every month, they hold public meetings and take inputs from the public 
for the development of Jenkins project.
-> As technology grows, so does Jenkins. So far Jenkins has around 320 plugins published in its plugins database. With plugins, Jenkins 
becomes even more powerful and feature rich.
-> Jenkins tool also supports cloud-based architecture so that you can deploy Jenkins in cloud-based platforms.
-> The reason why Jenkins became popular is that it was created by a developer for developers.

# Jenkins Plugins:
-> Jenkins has a powerful extension and plugin system that allows developers to write plugins affecting nearly every aspect of Jenkins' behavior. 
Even a large part of "core" functionality is written in terms of extensions — extensions that could as well be contributed by plugins.

-> Download and install a JDK
-> Jenkins is based on Java, so to build Jenkins plugins you need to install a Java Development Kit (JDK). Java 11 is the version we recommend to users.
# Installing a plugin:
 Jenkins provides two methods for installing plugins on the controller:
 (1) Using the "Plugin Manager" in the web UI.
 (2) Using the Jenkins CLI install-plugin command

# What is Continuous Integration?
-> "Code check in and build serveral times a day".

Continuous Integration is a process of integrating code changes from multiple developers in a single project many times. 
The software is tested immediately after a code commit. With each code commit, code is built and tested. If the test is passed, 
the build is tested for deployment.
This commit, build, test, and deploy is a continuous process and hence the name continuous integration/deployment.

# Continuous Integration Process :
   Developement -> Commit -> Build -> Test -> Stage -> Deploy Dev/QA -> Production
 <.................Continuous Integration/Delivery................................>
 

# What is Continuous Delivery?
-> "Changes to an application are automatically bug tested and uploaded to a repository.
-> Continuous Delivery is a process, where code changes are automatically built, tested, and prepared for a release to production.
-> It is a process where you build software in such a way that it can be released to production at any time. 

# BUild Pipeline
 -> Build CI/CD pipeline through different Jobs
  # Build Job -> Test Job -> Deploy Job -> Release Job -> Production Job
  
# Types of Pipeline
 -> Scripted Pipeline
 -> Declarative Pipeline
 
 # Scripted Pipeline : 
 Scripted Pipeline using groovey script the whole execute the jobs only single pipeline
 
 # Declarative Pipeline : 
 Declarative pipeline using source code management and git repository,cloud based repository....etc.
