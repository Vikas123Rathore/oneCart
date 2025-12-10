# oneCart - Full-Stack E-Commerce Platform

oneCart is a complete e-commerce solution built with modern web technologies. It features a robust backend, responsive frontend, and an admin dashboard for managing products, orders, and users.

## 🏗️ Project Structure

```
oneCart/
├── frontend/          # Customer-facing React application
├── backend/           # Express.js REST API server
├── admin/             # Admin dashboard for store management
└── .gitignore         # Git configuration
```

## 🚀 Features

### Frontend
- Product browsing and search
- Shopping cart management
- User authentication
- Order tracking
- Responsive design with Vite + React

### Backend
- RESTful API with Express.js
- MongoDB database integration
- JWT authentication
- Payment processing (Razorpay)
- Image hosting (Cloudinary)
- Order and cart management

### Admin Dashboard
- Product management
- Order management
- User management
- Analytics and reports
- Vite-powered fast development

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB account
- Cloudinary account (for image uploads)
- Razorpay account (for payments)

## 🔧 Installation

### 1. Clone the repository
```bash
git clone <repository-url>
cd oneCart
```

### 2. Setup Backend
```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory with the following variables:
```
PORT=8000
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=admin@onecart.com
ADMIN_PASSWORD=your_admin_password
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
```

### 3. Setup Frontend
```bash
cd ../frontend
npm install
```

Create a `.env` file in the `frontend` directory with API configuration.

### 4. Setup Admin Dashboard
```bash
cd ../admin
npm install
```

Create a `.env` file in the `admin` directory as needed.

## 🚀 Running the Application

### Start Backend Server
```bash
cd backend
npm run dev
```
The backend will run on `http://localhost:8000`

### Start Frontend Development Server
```bash
cd frontend
npm run dev
```
The frontend will run on `http://localhost:5173`

### Start Admin Dashboard
```bash
cd admin
npm run dev
```
The admin dashboard will run on `http://localhost:5174` (or next available port)

## 🛠️ Tech Stack

### Frontend
- **React** - UI library
- **Vite** - Build tool and development server
- **CSS** - Styling

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database
- **JWT** - Authentication
- **Cloudinary** - Image management
- **Razorpay** - Payment gateway

### Admin Dashboard
- **React** - UI library
- **Vite** - Build tool
- **CSS** - Styling

## 📁 Key Directories

### Backend Structure
- `config/` - Configuration files (DB, Cloudinary, JWT, etc.)
- `controller/` - Route controllers (auth, cart, orders, etc.)
- `middleware/` - Custom middleware for authentication and validation
- `model/` - MongoDB schemas
- `routes/` - API endpoints
- `public/` - Static files

### Frontend/Admin Structure
- `src/` - Source code
  - `component/` - Reusable React components
  - `context/` - React context for state management
  - `pages/` - Page components
  - `assets/` - Images, fonts, etc.

## 🔐 Environment Variables

**Never commit `.env` files to version control.** They are listed in `.gitignore`.

### Backend Environment Variables
- `PORT` - Server port
- `MONGODB_URL` - MongoDB connection string
- `JWT_SECRET` - Secret key for JWT tokens
- `ADMIN_EMAIL` & `ADMIN_PASSWORD` - Admin credentials
- `CLOUDINARY_*` - Cloudinary API credentials
- `RAZORPAY_*` - Razorpay payment credentials

## 📚 API Documentation

Documentation for backend API endpoints should be added here. Key endpoints include:
- Authentication routes
- Product routes
- Cart routes
- Order routes
- User routes
- Admin routes

## 🤝 Contributing

1. Create a feature branch
2. Make your changes
3. Submit a pull request

## 📝 License

Add your license information here.

## 📧 Support

For support, email support@onecart.com or open an issue in the repository.

---

**Built with ❤️ for e-commerce excellence**
