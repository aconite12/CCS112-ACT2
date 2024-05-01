# SwiftBuy E-Commerce Platform

SwiftBuy is an e-commerce platform developed to streamline the process of buying and selling products online. It consists of a front-end application built with React and a back-end API developed with Laravel to handle data management and business logic.

## Objective

The objective of this project is to create a functional e-commerce platform where users can browse products, add items to their cart, view their cart, remove items from their cart, and complete the checkout process.

## Requirements

### Front-End Application (React):

- Implement a user-friendly interface using React to allow users to interact with the e-commerce platform.
- Display a list of available products fetched from the Laravel API.
- Allow users to add items to their shopping cart.
- Provide a cart view where users can see the items in their cart along with the quantity and total price.
- Allow users to remove items from their cart.
- Implement a checkout process where users can enter their shipping details and complete the purchase.

### Back-End API (Laravel):

- Develop a RESTful API using Laravel to handle requests from the front-end application.
- Implement endpoints to fetch product data from the database and send it to the front end.
- Create endpoints to manage the shopping cart, including adding items, removing items, and updating quantities.
- Implement functionality to calculate the total price of the items in the cart.

## Solution Approach

### Front-End Development (React):

- Create React components for different sections of the e-commerce platform, such as product listing, cart view, and checkout.
- Use React Router to handle navigation between different pages of the application.
- Implement state management using React Hooks to manage the state of the shopping cart and user interactions.
- Use Fetch API to make HTTP requests to the Laravel API and fetch data.
- Design the user interface to be responsive and accessible across various devices and screen sizes.

### Back-End Development (Laravel):

- Set up a Laravel project with appropriate database configurations.
- Define models and migrations to represent products, users, and carts in the database.
- Implement controllers to handle incoming requests from the front end and perform necessary operations, such as fetching product data and managing the shopping cart.
- Use Laravel's validation features to validate incoming requests and ensure data integrity.
- Implement authentication and authorization mechanisms to secure the API endpoints and restrict access to authenticated users only.
- Utilize Laravel's built-in features for handling sessions and managing user authentication.

## Getting Started

To get started with SwiftBuy, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `frontend` directory and run `npm install` to install the necessary dependencies.
3. Run `npm start` to start the React development server.
4. Navigate to the `backend` directory and run `composer install` to install the necessary PHP dependencies.
5. Set up your database configurations in the `.env` file.
6. Run database migrations using `php artisan migrate`.
7. Run the Laravel development server using `php artisan serve`.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the [MIT License](LICENSE).
