# ezthesisCamunda
In order to run this package you need to have maven and java installed on your OS.
Just build the module. So that it have target folder setup
```
mvn clean
mvn package
mvn spring-boot:run
```
Camunda will be running on localhost:8080
Username: admin
Password: admin

##Starting Process
Once logged in User can start a process via camunda tasklist.
Main process is Fullthesis just start it will be shown in cockpit and respective tasks will be located in tasklist.
For ease of process all of tasks are allocated to one user in order to study the full process