

# library Project 
This project is a Node.js application for managing an online bookstore. It provides functionalities for users to browse, search, and purchase books, as well as for administrators to manage inventory, process orders, and track sales.


## Features:
- User Authentication: Users can create accounts, log in, and log out securely. Passwords are hashed for security.

- Book Management: Administrators can add new books, update existing books, and delete books from the inventory. Each book includes details such as name, price, description, quantity, image, and department.

- Shopping Cart: Users can add books to their shopping cart, adjust quantities, and remove items before checkout.

- Wishlist: Users can add books to their wishlist for future reference or purchase.

- Order Processing: Users can place orders, view order history, and track the status of their orders. Administrators can view all orders, update order status, and manage shipping information.

- Search and Filtering: Users can search for books by name, department, or author. They can also filter books by department.
  
- Rating and Reviews: Users can view and submit ratings and reviews for books.


# Technologies Used:

- Node.js: Backend JavaScript runtime environment.
- Express.js: Web application framework for Node.js.
- MongoDB: NoSQL database used for storing book and user data.
- Mongoose: MongoDB object modeling for Node.js.
- bcrypt: Library for hashing passwords.
- JWT (JSON Web Tokens): Used for user authentication and authorization.
- Multer: Middleware for handling multipart/form-data, used for uploading book images

