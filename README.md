# How to install project

### Guides
Please follow the following command to run the project in which is given below:

* pull from main branch
* change the datasource url from 127.0.0.1 to your mysql ip
* docker compose down
* use ./gradlew build
* docker compose build
* docker compose up -d

N.B : If you want to run the project in your IDE then just build and run the main file.

### Guides
After successfully run your application in docker. Please follow the link which is given below:

* http://your_ip_address:8080/swagger-ui/index.html
* Please write your ip address in given url and browse.

### Project Controller Details
This project has two controller.
* AuthController (has auth and user registration api's)
* UserController (has user crud api's)

Before access user controller api's. 
* You need to registration user by providing necessary data from http://your_ip_address:8080/auth/user-registration POST api.
* Then get token from http://your_ip_address:8080/auth/login POST by providing username and password
* Then authorize the swagger by providing token.
* Then you are allowed to execute crud apis of user controller.

If you are facing any issue, feel free to ask any questions.