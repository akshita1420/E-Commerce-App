# E-Commerce-App

A full-stack Flutter-based eCommerce app with a Node.js backend. The app provides seamless shopping experiences with real-time updates, authentication, and payment processing.

## Features
- 🔐 User authentication (Sign Up, Login, Logout)
- 🛒 Product listings with categories
- 🏷️ Product search and filtering
- 🛍️ Shopping cart and checkout process
- 💳 Payment integration
- 📦 Order tracking and history
- 📡 Real-time updates

## Tech Stack
- **Frontend:** Flutter (Dart)
- **Backend:** Node.js with Express.js
- **Database:** MongoDB
- **State Management:** Provider / Riverpod
- **Authentication:** JWT-based authentication

## Installation
### Prerequisites
Ensure you have the following installed:
- Flutter SDK
- Node.js & npm
- MongoDB

### Backend Setup
1. Navigate to the backend folder:
   ```sh
   cd backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   npm start
   ```

### Frontend Setup
1. Navigate to the Flutter project directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   flutter pub get
   ```
3. Run the app:
   ```sh
   flutter run
   ```

## API Endpoints
| Method | Endpoint       | Description             |
|--------|---------------|-------------------------|
| POST   | /auth/signup  | User registration       |
| POST   | /auth/login   | User login              |
| GET    | /products     | Fetch all products      |
| POST   | /cart/add     | Add item to cart        |
| POST   | /order/checkout | Checkout order       |

## Contributing
Contributions are welcome! Feel free to fork the repo, create a branch, and submit a PR.

## License
This project is licensed under the MIT License.

## Contact
For queries, reach out via [GitHub Issues](https://github.com/akshita1420/E-Commerce-App/issues).
