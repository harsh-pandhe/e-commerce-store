# 🛒 E-Commerce Store

Welcome to **E-Commerce Store** – your modern, feature-packed shopping platform! Built using the powerful MERN stack, this app provides a seamless, responsive, and secure shopping experience. Let’s dive into what makes this app awesome!

## 🚀 Features You'll Love

- **🔒 Secure User Authentication**: Log in and sign up with encrypted passwords using JWT and `bcryptjs` – your data is safe with us.
- **🛍️ Product Management**: Add, edit, and showcase products easily. We’ve got image uploads sorted with `multer` and `cloudinary`.
- **💰 Smooth Payments**: Integrated with PayPal to handle transactions securely and effortlessly.
- **📱 Responsive Design**: Shop on the go or from your couch – optimized for both mobile and desktop with React and Tailwind CSS.
- **🌐 Routing Made Easy**: Handled by React Router on the frontend and Express on the backend.
- **🧑‍💻 State Management Simplified**: Built with `@reduxjs/toolkit` for a smoother and more predictable state management experience.

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

