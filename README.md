
# MEAN Stack Product Management App Web Application Developed By Rahul Gupta

Product Management App Web Application V.1

## Development server Front (Angular)

Run `npm install` in client folder for install node_modules.

Run `ng serve` for a angular server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Development server Back (Node)

Run `npm install` in server folder for install node_modules.

Run `mongod` for start mongodb connection.

Run `node ./bin/www `for  node server. This app will automatically connected to database.(MongoDB)


## Description (following steps for better result)

-------------------------------------Added Details in Database--------------------------------------------

Enter some details by below api with the help of Insomnia (https://insomnia.rest/download/) or Postman (https://www.postman.com/downloads/)

Add user for Admin (http://localhost:3001/api/register) method "POST" 
{
 "email":"your email address",
 "password":"your password"
}
Add Category Names for product (http://localhost:3001/api/addNewCategory) method "POST"
{
 "categoryName":"any category name"
}
----------------------------------------------------------------------------------


Login with Your Credentials in Application : `http://localhost:4200/`

You can add any new product by click on add new product button 

Listing all product by click on product list button

Search Product with Product name and category name and also based on net price.

You can edit, view and delete product by hover on perticuler product.

You can logout by click on Logout button.

We have added image of this app.

## Further help

Email: a1rahulgupta@gmail.com
Contact Us: 9927955351
