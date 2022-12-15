# Restful
Building a Restful WEB SERVICE using Springboot, by following the Spring documentation: https://spring.io/guides/gs/rest-service/

##  /greeting
You can access the /greeting path by typing : http://localhost:8080/greeting
By default the result would be a JSON object returned with an id of 1 in the first time:



![image](https://user-images.githubusercontent.com/77130152/207837932-00ca1558-6ec8-4ba2-8792-ce2cccd0bf9b.png)

#### Explantion:
The id is initialized when the app is first launched with the value of 1.
It gets incremented everytime the /greeting path is called, (in a url in the browser, using postman ...)

##  /greeting?name=Sohaib

If the /greeting url is called without passing any parameters, It sets the value in "name" to:  "Hello World!"
In this case we passed the name Sohaib, so the output was : Hello Sohaib!

With a different id of course

![image](https://user-images.githubusercontent.com/77130152/207839632-f64beff2-d03b-4b79-a207-655785bf784f.png)
