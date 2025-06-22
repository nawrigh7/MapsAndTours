# MapsAndTours
This web application allows a user to set locations on a map, which will then create a "tour" of those locations (ending at the original point). It is connected to a database of worldwide breweries, to allow for a global brewery tour.

# How to Run
To see the functionality of this code, download the .jar file located in the [release](https://github.com/nawrigh7/MapsAndTours/releases).
Make sure you have Java 11 or higher installed, then run:

```java -jar server-1.0.0-jar-with-dependencies.jar```
Note: The default port is set to 8088, so when visiting localhost without specifying a port, you would follow https://localhost:8088/

Optionally, you can specify a port to run this on as such:

```java -jar server-1.0.0-jar-with-dependencies.jar 8080```

to run on port 8080. Feel free to copy/paste the above command to run easily.

Then, simply visit:

https://localhost:8080/
