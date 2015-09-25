Jetty Example of /META-INF/resources/ Use
=========================================

This project contains 2 modules .

common-resources
----------------

A basic JAR project that simple has `/META-INF/resources/`
content in it.


time-webapp
-----------

A simple WAR project that includes `common-resources` and relies on the
ability to access those resources for it to function properly.


To Build
--------

    $ mvn clean install


To Run
------

    $ cd time-webapp
    $ mvn jetty:run

To Test
-------

Open a browser to [http://localhost:8080/]

