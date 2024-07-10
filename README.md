# Customer Management System

This project is a web-based application built using Express.js, MongoDB, HTML (EJS), CSS, Bootstrap, and JavaScript. It allows users to manage customer information with functionalities to add, view, edit, search, and delete customers.


## Features

- **User Authentication**: Sign-in page to authenticate users.
- **Add Customers**: Form to add new customer information to the database.
- **View Customers**: Home page displaying all customers added by the user.
- **Edit Customers**: Edit page to update information of a specific customer.
- **Search Customers**: Search functionality to find customers based on a query.
- **Delete Customers**: Option to delete a customer from the database.
- **View Customer Details**: Page to display detailed information about a single customer.


## Installation
1- Clone the repository:
```
git clone https://github.com/Anasoud1/customer-management-system.git
```

2- Navigate to the project directory:
```
cd customer-management-system
```

3- Install the dependencies:
```
npm install
```

4- Set up the MongoDB database and configure the connection string in the .env file.
```
SECRET=jwt_secret_key
MONGO_LINK=mongo_link
PORT=port
```

5- Start the application:
```
npm run dev
```


## Usage

1- Open your browser and navigate to http://localhost:3000.

2- Sign in using your credentials.

3- Use the navigation bar to access different functionalities:
- Add a new customer.
- View the list of customers.
- Edit customer information.
- Search for customers.
- Delete a customer.
- View detailed information about a customer.


## Technologies

- **Backend**: Express.js, MongoDB
- **Frontend**: HTML (EJS), CSS, Bootstrap, JavaScript


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.


## License

This project is licensed under the MIT License.
