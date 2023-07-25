# Amazing

1. setting up required software.
2. Adding required extensions and its settings
3. Create React App
4. Create Git Repository
5. List Products
   a. Create product array
   b. add product image
   c. render product
   d. style product
6. Routing to Home Screen and Detail Page
7. Create Node.js server

   1. run npm init in root folder
   2. Update package.json set "type": "module"
   3. Add .js (data file) to import
   4. npm install express
   5. create server.js
   6. auto update of server on changes in file (nodemon install)
   7. create route for api/products
   8. return products
   9. run npm start

8. Fetch products from backend

   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook

9. Manage State By Reducer HOok

   1. define reducer
   2. update fetch data
   3. get state from useReducer

10. Add bootstrap UI Framework

a. npm install react-bootstrap bootstrap
b. Update App.js

11. Create Product and Rating Component

a. Create Rating Component
b. Create Product Component
c. Add rating component in product component

12. Create the Product Detail Page with Bootstrap

a. Fetching Product from backend.
b. Product Image , Product Information & Product Status if available button to add to cart else out of stock.
c. Changing title of the page as per the product title using helmet

13. Create Loading and message component
    a. create loading component
    b. create spinner component
    c. create message component
    d. define util.js to define getError function

14. Implement Add to Cart
    a. Create React Context
    b. Define Reducer
    c. Create store provider
    d. Implement add to cart button handler

15. Improve cart functionality
    a. check existing item in cart
    b. check cart items in backend

16. Create cart Screen
    a. create 2 columns
    b. display item list.
    c. create action column.

17. Complete Cart Screen
    a. click handler for inc/dec item
    b. click handler for remove item
    c. click handler for checkout
