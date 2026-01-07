# Forever E-Commerce Full Stack Application

This is a full-stack e-commerce application consisting of a Frontend (customer facing), an Admin Panel (for management), and a Backend API.

## Project Structure

- **frontend**: The customer-facing e-commerce website built with React and Vite.
- **admin**: The admin dashboard for managing products, orders, and users, built with React and Vite.
- **backend**: The REST API server built with Node.js, Express, and MongoDB.

## Tech Stack

### Frontend & Admin
- **Framework**: React.js with Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router DOM
- **HTTP Client**: Axios
- **Notifications**: React Toastify

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JSON Web Tokens (JWT)
- **Image Storage**: Cloudinary
- **Payments**: Stripe, Razorpay
- **Other Tools**: Multer (file uploads), Bcrypt (hashing), Validator, Cors, Dotenv

## Setup Instructions

### 1. Backend Setup

Navigate to the `backend` directory:
```bash
cd backend
```

Install dependencies:
```bash
npm install
```

Create a `.env` file in the `backend` directory with the following variables:
```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password
```

Start the server:
```bash
npm run server
# or
npm start
```

### 2. Frontend Setup

Navigate to the `frontend` directory:
```bash
cd frontend
```

Install dependencies:
```bash
npm install
```

Create a `.env` file in the `frontend` directory:
```env
VITE_BACKEND_URL=http://localhost:4000
```

Start the development server:
```bash
npm run dev
```

### 3. Admin Panel Setup

Navigate to the `admin` directory:
```bash
cd admin
```

Install dependencies:
```bash
npm install
```

Create a `.env` file in the `admin` directory:
```env
VITE_BACKEND_URL=http://localhost:4000
```

Start the development server:
```bash
npm run dev
```

## Credits

This project structure is based on the "Forever" e-commerce project.
- **Tutorial**: [Project Setup Tutorial](https://youtu.be/x7nOy8JNna4)
- **Source**: [GreatStack.dev](https://greatstack.dev/source-code)
