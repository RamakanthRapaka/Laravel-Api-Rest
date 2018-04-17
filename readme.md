# Laravel-Api-Rest
Step 1 : Clone Project(git clone <url>)
Step 2 : composer update 
Step 3 : Change Database Connection .env File
Step 4 : run migrations : php artisan migrate
Step 5 : Run Project : php artisan serve
Step 6 : Open Post Man
Step 7 : First API : http://127.0.0.1:8000/api/register
in Take Method : POST in Body-> form-data: email : rams_547@yahoo.co.in, password : 1234, name: Ramakanth Rapaka, c_password : 1234 after that Click on Send
Second API : http://127.0.0.1:8000/api/login
in take POST method Body->form-data keys...email : rams_547@yahoo.co.in, password : 1234 Then Click on Send
Third Get Details : http://127.0.0.1:8000/api/get-details
in Take Method : POST
Headers -> Authorization : Bearer <after login will token paste here>, Accept : application/json,
in Body->form-data  email: rams_547@yahoo.co.in, password : 1234 Then Click on Send
