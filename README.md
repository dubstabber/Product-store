# Product Store

A modern full-stack e-commerce application for managing product inventory with complete CRUD functionality.

## 🔗 Live Demo

**[View Live Demo](https://product-store-55i3.onrender.com)** - Check out the deployed application!

## 🚀 Features

- **Product Management**: Create, read, update, and delete products
- **Responsive Design**: Mobile-first interface built with Chakra UI
- **State Management**: Efficient state handling with Zustand
- **User Feedback**: Toast notifications for operation status
- **Dynamic UI**: Smooth transitions and hover effects
- **Real-time Updates**: Instant UI updates after CRUD operations

## 🛠️ Tech Stack

### Frontend

- **React 19**: Latest React for building the UI
- **Vite**: Lightning-fast build tool and development server
- **Chakra UI**: Component library for beautiful, accessible UI
- **Zustand**: Lightweight state management
- **React Router**: Navigation and routing
- **Framer Motion**: Animation library for smooth transitions

### Backend

- **Node.js**: JavaScript runtime for server-side code
- **Express 5**: Fast, unopinionated web framework
- **MongoDB**: NoSQL database for data storage
- **Mongoose**: MongoDB object modeling for Node.js
- **RESTful API**: Structured endpoints for data operations

## 📋 API Endpoints

| Method | Endpoint          | Description           |
| ------ | ----------------- | --------------------- |
| GET    | /api/products     | Retrieve all products |
| POST   | /api/products     | Create a new product  |
| PUT    | /api/products/:id | Update a product      |
| DELETE | /api/products/:id | Delete a product      |

## 🚦 Getting Started

### Prerequisites

- Node.js (v16+)
- MongoDB

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/dubstabber/Product-store.git
   cd Product-store
   ```

2. Install dependencies

   ```bash
   npm install
   cd frontend && npm install
   ```

3. Environment Setup
   Create a `.env` file in the root directory with:

   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   ```

4. Start the development servers

   ```bash
   # Start backend server
   npm run dev

   # In a separate terminal, start frontend
   cd frontend && npm run dev
   ```

## 🌐 Deployment

The application is configured for easy deployment:

```bash
# Build for production
npm run build

# Start production server
npm start
```

## 🏗️ Project Structure

```
product-store/
├── backend/
│   ├── config/       # Database configuration
│   ├── controllers/  # Request handlers
│   ├── models/       # Data models
│   ├── routes/       # API routes
│   └── server.js     # Express application
├── frontend/
│   ├── public/       # Static assets
│   └── src/
│       ├── components/ # Reusable UI components
│       ├── pages/      # Application pages
│       ├── store/      # State management
│       ├── App.jsx     # Application entry
│       └── main.jsx    # React rendering
└── package.json     # Project dependencies and scripts
```

## 🙏 Acknowledgments

- [React Documentation](https://react.dev/)
- [Express Documentation](https://expressjs.com/)
- [Chakra UI](https://chakra-ui.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)
