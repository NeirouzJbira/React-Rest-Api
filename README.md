# React-Rest-Api
Web application with MERN stack...


# About the application
Basically a Web App created with MERN Stack

A CRUD application which uses a REST API on backend and using React JS on the frontend. The application is about how a new product can be "created", "updated" or "deleted". It also has image uploading function. The application also uses JWT (Json Web Tokens) for authentication purpose (Login) and Forgot password system. The concept of refresh-tokens is also available. However, the tokens are stored on the local storage of the browser which I believe is a bit unsafe but its just for learning purpose.

On the frontend, React library is being used with React Material Ui and custom CSS just for a clean look with success and error messages.. The website is responsive too..

# Running the application
After extracting the zip file, from the project directory start the server by running 'npm install' and then 'nodemon'.
From another terminal window start the client by running 'cd client' and 'npm install' then 'npm start'.
Your application should run on "http://localhost:3000".


# Note: 
Please prefix "http://localhost:5000" on variables "url" and "imageUrl" on all components of the client (i.e AddProduct.jsx, AllProducts.jsx etc..) wherever required as both the server and the client are running on different ports..

Replace the mongoDb 'dbname', 'username' and 'password' with your own credentials..

And also the password-reset link can be found on your mail at spam folder..
