# Laravel Project
## ajax
### for output you need to go to right_click=>inspect=>click_name(i.e.control)=>response
I have made a User Register System in Laravel and i have used MYSQL database. Laravel project contains main.blade.php file inside vendor folder which contains a general submit form and to submit that data, there are two controller files with their routes in route folder- 
1. ATGController.php - It is the controller file which is used to send the data on localhost as its route is given in web.php file.
2. WebServicesController.php - It is controller which is used to send the data through and REST-API request and its route is given in api.php.
REST-API is tested using Postman application which uses POST method to send and save the data. 
Rest-api and localhost are the two different methods either of them can be used to send and save the data in database.

