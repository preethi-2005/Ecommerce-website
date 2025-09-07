# Ecommerce-website
# E-commerce Website - Frontend

This is the **frontend** part of an E-commerce website built with **React**, **Vite**, **React Router**, and **Axios**.

---

## Project Structure

frontend/
├── node_modules/ # npm dependencies
├── public/ # Static assets (optional)
├── src/
│ ├── Components/ # Reusable React components (e.g., Navbar)
│ ├── pages/ # Page components (Products, Cart, Login, Signup)
│ ├── services/ # API utility (axios instance)
│ │ └── api.js # Axios config for API calls
│ ├── App.jsx # Main App component with routes
│ ├── main.jsx # ReactDOM render entry point
├── .gitignore # Git ignore rules
├── index.html # Main HTML file served by Vite
├── package.json # Project metadata & scripts
├── vite.config.js # Vite configuration file
└── README.md # Project documentation (this file)


---

## Getting Started

### Prerequisites

- Node.js (v16 or newer recommended)
- npm (comes with Node.js)

---

### Installation

1. Clone the repository or download project files.

2. Navigate to the frontend folder:

```bash
cd frontend
npm install
npm run dev
http://localhost:PORTNO
npm run build
npm run preview
VITE_API_BASE_URL=BASE URI
Dependencies

React

React DOM

React Router DOM

Axios

Vite

@vitejs/plugin-react
