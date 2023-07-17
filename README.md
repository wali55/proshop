# ProShop

[Create React App](https://github.com/facebook/create-react-app).

## Project Description

* ProShop is a MERN stack eCommerce application where user can see our products section, there is pagination if we have more than 8 products when user clicks one of this products, it will take user in a single page that has an id of the product. 

* It have some basic info the description, the price, the rating, down here rating and reviews will show, when the user is logged in he will see a form here to submit the review, a single user can submit one review per product. 

* If the user clicks on the 'Add To Cart' button it will take user to cart page, there he can change the quantity, that will update the price and number of items. When user press proceed to checkout, it will take the user to login or register page. If the user sign in it should take the user to the shipping page. 

* Thw shipping page will show the user the summary of his orders, pricing, tax, shipping cost. When user place order that creates an order in the database. 

* If the order is not paid user can see the payment button. After payment is done using PayPal or Credit card toast will appear saying order is paid. The user will see on the screen paid and also payment date. On the screen a message will says not delivered because admin goes in and checks on delivered button.

 * After making that order if the user goes to the profile he can see all the orders. He can user data, if he clicks on details it will take him back to the order page
 
 * The app has admin functionality. When admin logged in he can see the admin dropdown, can see all the product list, see all the orders, can go to the details of the order and click on the mark as delivered. Now it gets marked as delivered in the database. 
 
 * Admin can edit the product, if admin wants he can delete the product, can create product with dummy data then he can edit the product, we can upload the of the image of the product as Multer is used in this project.
