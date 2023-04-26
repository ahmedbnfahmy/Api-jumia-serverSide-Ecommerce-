# Ecommerce API

This is an ecommerce API built with Node.js, Mongoose, Stripe payment method, and Express. This API allows developers to build their own ecommerce web application.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/ecommerce-api.git`
2. Install dependencies: `npm install`
3. Create a `.env` file in the root directory of the project and add the following environment variables:
   - `MONGODB_URI`: the URI for your MongoDB database
   - `STRIPE_SECRET_KEY`: your Stripe secret key
4. Start the server: `npm start`

## Usage

Once the server is running, you can send HTTP requests to the API at `http://localhost:3000`.

The API allows developers to:

- Create, read, update, and delete products
- Create, read, update, and delete categories
- Create, read, update, and delete orders
- Process payments using Stripe

## Technologies Used

- Node.js
- Mongoose
- Stripe payment method
- Express

## Contributing

Contributions are always welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b my-new-feature`
3. Make changes and commit them: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
