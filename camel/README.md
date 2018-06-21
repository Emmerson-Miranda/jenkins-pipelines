# helloworld-camel-spring-boot-soapui-project-jenkinsfile
This pipeline does following actions:
- download source code from git
- build and package with maven (generate the docker container as well)
- start the container created before
- run SOAPUI test project
- stop the container

## pipeline status example
![alt tag](pipeline_status.png)

## Test results output
![alt tag](pipeline_test_result.png)
