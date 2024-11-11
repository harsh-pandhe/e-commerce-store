# 🛒 E-Commerce Store

Welcome to **E-Commerce Store** – a feature-packed online shopping platform! This app is built with the powerful MERN stack, offering both an **Admin Panel** and a **Shopping Store** with an integrated **rating system**. Whether you’re managing products or shopping for the latest deals, this app has got you covered!

## 🚀 Features You'll Love

- **🔒 Secure User Authentication**: Sign up and log in securely with JWT and `bcryptjs`.
- **🛒 Shopping Store**:
  - **Product Listings**: View and browse a variety of products.
  - **Product Details**: View detailed information about a product.
  - **Add to Cart**: Add items to your cart for easy checkout.
  - **Checkout**: A smooth and secure checkout experience with PayPal.
  - **Search**: Find products quickly with the search functionality.
  - **Product Reviews & Ratings**: Customers can rate and review products.
- **🧑‍💻 Admin Panel**:
  - **Admin Dashboard**: Manage products and view site analytics.
  - **Product Management**: Create, update, or delete products.
  - **Order Management**: View and manage customer orders.
  - **User Management**: Manage customer accounts.
  

## 🛠️ Tech Stack

### Frontend
- **React** + **Vite**: Fast, modern, and a joy to code with.
- **Tailwind CSS**: For a sleek, mobile-friendly design.
- **Radix UI**: To make UI components pop.
- **Axios**: For seamless HTTP requests.

### Backend
- **Node.js** & **Express**: Fast, reliable, and perfect for handling all those API calls.
- **MongoDB**: Scalable, NoSQL database to store everything securely.
- **Mongoose**: Making data interaction a breeze.
- **Cloudinary**: For image storage that’s easy and reliable.
- **PayPal SDK**: To make payments a walk in the park.

## 🚧 Getting Started

### Prerequisites

Make sure you have **Node.js** and **npm** installed, and your **MongoDB** instance set up.

### Installation Steps

1. **Clone the Repo**:
   ```bash
   git clone https://github.com/harsh-pandhe/e-commerce-store.git
   cd e-commerce-store
   ```

2. **Backend Setup**:
   ```bash
   cd server
   npm install
   ```

   Create a `.env` file with your configuration:
   ```dotenv
   # Server configuration
   PORT=5000
   MONGO_URI="<your_mongo_uri>"
   CORS_ORIGIN="http://localhost:5173"

   # Cloudinary configuration
   CLOUD_NAME="<your_cloudinary_name>"
   API_KEY="<your_cloudinary_api_key>"
   API_SECRET="<your_cloudinary_api_secret>"

   # PayPal configuration
   PAYPAL_MODE="sandbox"  # Change to "live" for production
   PAYPAL_CLIENT_ID="<your_paypal_client_id>"
   PAYPAL_CLIENT_SECRET="<your_paypal_client_secret>"
   ```

   **Important**: Replace the placeholder values (e.g., `<your_mongo_uri>`, `<your_cloudinary_api_key>`) with your actual credentials.

3. **Run the server**:
   ```bash
   npm run dev
   ```

4. **Frontend Setup**:
   ```bash
   cd ../client
   npm install
   ```

   Run the development server:
   ```bash
   npm run dev
   ```

## 🔒 Security Best Practices

- **Never share** your real `.env` file publicly or commit it to version control.
- Add `.env` to your `.gitignore` to keep it from being pushed to your repository.
- Use secret management services like **GitHub Secrets**, **AWS Secrets Manager**, or **dotenv-cli** for enhanced security.

## 🤝 Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to help make this app even better.

## 📝 License

This project is licensed under the **ISC License**.

## 👨‍💻 Author

Built with ❤️ by **Harsh Pandhe**. Feel free to connect or share your thoughts!

