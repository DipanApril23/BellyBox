# Food Ordering App(BellyBox)

## Overview
The **Food Ordering App** is a full-fledged React-based web application that allows users to browse a variety of dishes, add them to their cart, and place orders seamlessly. Built using modern React concepts, this project showcases efficient state management, optimized performance, and smooth user experience.

## Features
- **Browse Restaurants & Dishes**: View a list of restaurants and their menus.
- **Search & Filter**: Find specific dishes or filter based on cuisine.
- **Cart Management**: Add, remove, and update items in the cart.
- **User Authentication**: Sign in and sign up using Firebase authentication.
- **Checkout & Payments**: Place orders using an integrated payment gateway.
- **Order Tracking**: View past orders and track real-time delivery updates.
- **Dark Mode Support**: Toggle between light and dark themes.

## Tech Stack
### Frontend
- **React 18**: Core framework
- **React Router**: Navigation and page routing
- **Redux Toolkit**: Global state management
- **React Context API**: Local state sharing
- **React Hooks**: useState, useEffect, useContext, useReducer, useMemo, etc.
- **React Lazy & Suspense**: Code-splitting for performance
- **Tailwind CSS**: Responsive UI design
- **Axios**: API requests handling
- **Framer Motion**: Smooth animations

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/food-ordering-app.git
cd food-ordering-app
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start Development Server
```bash
npm start
```
Open `http://localhost:1234` in your browser.

### 4. Environment Variables (Optional for Backend)
Create a `.env` file and add:
```
REACT_APP_API_URL=your_backend_url
REACT_APP_FIREBASE_KEY=your_firebase_api_key
```

## Project Structure
```
food-ordering-app/
│── public/
│── src/
│   ├── components/   # Reusable UI components
│   ├── pages/        # Individual pages (Home, Cart, Orders)
│   ├── context/      # React Context API setup
│   ├── redux/        # Redux store & slices
│   ├── hooks/        # Custom React hooks
│   ├── utils/        # Utility functions
│   ├── assets/       # Images & Icons
│   ├── App.js        # Main component
│   ├── index.js      # Entry point
│── package.json
│── README.md
```

## Key React Concepts Used
- **Functional Components** for modular design
- **Hooks (useState, useEffect, useReducer, useMemo, etc.)** for state & effects
- **React Context API + useContext** for global state sharing
- **Redux Toolkit** for scalable state management
- **React Router** for seamless navigation
- **Lazy Loading & Suspense** for performance optimization
- **Debouncing & useMemo** for efficient search and filter
- **Protected Routes** for user authentication

## Future Improvements
- Implement WebSockets for real-time order tracking
- Add push notifications for order status updates
- Improve animations and micro-interactions

## Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes: `git commit -m 'Added new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Open a pull request.

## License
This project is licensed under the MIT License.

##Author
Dipan MAJUMDER

