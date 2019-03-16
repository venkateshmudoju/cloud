# cloud

https://www.javainuse.com/devops/pcf_intvw

 mvn package -> maven will create a jar file 

cf login

It will ask for Cloud Foundry API. Enter The following API value-
     https://api.run.pivotal.io
     
Go to the project root location and using the following command push the employee-producer jar file to PCF for deployment
     cf push test-environment -p target\employee-producer-0.0.1-SNAPSHOT.jar               p->path
     
