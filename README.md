Java Demo App
=============

Dependencies
-----

You need maven2 and a jdk installed e.g.

```
sudo apt-get install maven2 openjdk-6-jdk
```
   
Build
-----

```  
mvn package
```

Run Locally
-----------

```
mvn package tomcat7:run
# in another shell call
curl http://localhost:8080/hello/
```

> **Note:** The trailing `/` is needed to see the response in the shell!
