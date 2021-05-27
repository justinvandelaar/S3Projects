# How to install the Quarkus API
I am gonna explain the steps taken to install the Quarkus API
There are only a few step that you neeed to take.

# Step 1 JDK
Make sure that you have JDK 15 or higher installed.
Downloads can bee found here: https://jdk.java.net/
Version used for the developement of this project 15.0.2

# Step 2 Maven
Make sure tha you have Maven installed on your device.
Download link can be found here.
Version used for the developement of this project 3.8.1.

# Step 3 JAVA_HOME and MAVEN_HOME
Next in order to get Quarkus to reconigze these setups you need to do one more thing.
You have to set up 2 Vars in your pc to let quarukus reconzigze your JDK and Maven.
They are called JAVA_HOME annd MAVEN_HOME, you can add them by following the turtioal down below

JAVA_HOME: https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html
MAVEN_HOME: https://maven.apache.org/install.html

Its important to first Setup JAVA_HOME since maven is depened on that

# Step 4 Done Check
Now run your editor with the application and type in the terminal 
```
mvn quarkus:dev
```
If installed correctly than your application should be building otherwise you havee done something bad 
I recommend refollowing the entire step list then