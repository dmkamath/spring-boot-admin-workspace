
How to use this project
=======================
1. Open this project in IntelliJ. 
1. To do this, clone this to c:\gitrepos\spring-boot-admin-workspace
1. In IntelliJ create a new empty project with path c:\gitrepos\spring-boot-admin-workspace
1. Then add spring-boot-admin (in c:\gitrepos\spring-boot-admin-workspace) as a module. 
    1. make sure you import the module as maven/
    1. it is best to select pom.xml in spring-boot-admin
1. Then add my-app (in c:\gitrepos\spring-boot-admin-workspace) as a module.
    1. make sure you import the module as maven/
    1. it is best to select pom.xml in spring-boot-admin

if all goes well, both apps should build properly

SBA=spring-boot-admin

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


How was this created
====================
Created new workspace following SBA maintainer’s instructions here

## spring-boot-admin (SBA)
use sprint initializer with spring boot admin server

## my-app
use sprint initializer with web and spring boot admin client