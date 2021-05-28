

How was this created
====================
Created new workspace following SBA maintainer’s instructions here

## spring-boot-admin (SBA)
use sprint initializer with spring boot admin server

## my-app
use sprint initializer with web and spring boot admin client

How to use this project
=======================
Open this project in IntelliJ. (If all goes well maven project builds properly)

to start SBA right click on src/main/java/com/example/demo/springbootadmin/SpringBootAdminApplication.java and hit Run

then in the browser http://localhost:8080

SBA starts and begins to listen to apps
Since no apps are running, SBA now should show application count as 0


Differences between these apps and our apps
============================================
our apps use gradle to build but these use maven. no big deal just saying..

next start my-app. this app represents the application managed by SBA.
to do this, right click src/main/java/com/example/demo/myapp/MyAppApplication.java and hit Run

SBA now should show application count as 1

