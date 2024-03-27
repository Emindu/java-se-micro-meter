###  This is a demo application which is using micrometer-registry-prometheus for supporting application monitoring for java SE application

In spring boot we can get application default metrics with just adding `micrometer-registry-prometheus` dependency to class path, but when it comes to java se application we have to do few things for getting metrics
1. Registering metrics needed
2. Make a http server on application for exposing micro meter end point

- with making get reqeust to  `http://127.0.0.1:8001/micro-meter` we can get micro meter matrics as below
![image](https://github.com/Emindu/java-se-micro-meter/assets/41495728/2a5b2c2f-254c-4ef7-9aef-1193313c876e)

