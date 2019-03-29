# ezthesisCamunda
In order to run this package you need to have maven and java installed on your OS.
Just build the module. So that it have target folder setup. 
```
mvn clean
mvn package
mvn spring-boot:run
```
Camunda will be running on http://localhost:8080
**Username**: admin
**Password**: admin

## Starting Process
Once logged in User can start a process via camunda tasklist.
Main process is Fullthesis just start it will be shown in cockpit and respective tasks will be located in tasklist.
For ease of process all of tasks are allocated to one user in order to study the full process

1. First step is to download the code
2. Install the required packages via maven by runnin the first two commands
```
mvn clean
mvn package
```
Once its done make sure there is a target folder created in main folder where you downloaded code.
Then run 
```$xslt
mvn spring-boot:run
```
CAmunda engine will be started at http://localhost:8080

NOTE: If any issue coems up while installing just raise an issue on github we will address that ASAP
