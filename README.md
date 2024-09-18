# 3D Portfolio Website

This project is a 3D portfolio website built using React and Three.js. The site showcases various moving 3D models to create an interactive and visually appealing presentation of your work. The combination of modern web technologies and creative 3D design makes this portfolio dynamic and engaging.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Description](#project-description)
- [Folder Structure](#folder-structure)

## Features

- **Interactive 3D Models**: Various moving 3D models, built with Three.js, are integrated into the portfolio to create an immersive user experience.
- **Smooth Animations**: Powered by @react-spring/three for smooth and interactive animations.
- **Responsive Design**: The portfolio is fully responsive and works across a variety of devices and screen sizes.
- **Contact Form**: A functional contact form powered by EmailJS, allowing visitors to send messages directly from the portfolio.
- **Timeline Component**: Utilizes a vertical timeline to highlight significant projects or achievements in a visually appealing manner.

## Technologies Used

- **React**: For building the portfolio’s user interface.
- **Three.js**: For creating and rendering 3D models.
- **@react-three/fiber**: A React renderer for Three.js, making it easier to work with 3D models in the React environment.
- **@react-three/drei**: A collection of helpers and tools for simplifying the usage of Three.js with React.
- **@react-spring/three**: For handling smooth animations and transitions of 3D models.
- **Tailwind CSS**: Utility-first CSS framework used to style and lay out the portfolio.
- **React Router**: For managing different routes and navigation within the portfolio.
- **EmailJS**: To send emails directly from the contact form in the portfolio.

## Project Description

The 3D portfolio website is designed to provide a unique and interactive way to display your work and accomplishments. Utilizing React and Three.js, the website features dynamic 3D models and animations to create a more engaging user experience. The website is responsive, ensuring it looks great on all devices, and includes a functional contact form for direct communication with potential clients or employers.

### Key Libraries and Tools:

- **React**: Manages the UI and component structure.
- **Three.js**: Adds 3D graphics to enhance the portfolio experience.
- **@react-three/fiber**: Allows seamless integration of 3D elements with React.
- **@react-spring/three**: Adds animations to 3D objects for a smooth user experience.
- **React Router**: Supports navigation and routing in the portfolio.
- **EmailJS**: Sends emails directly from the site’s contact form without a backend.

## Folder Structure

```bash
portfolio-3d/
├── node_modules/           # Project dependencies
├── public/                 # Static assets (images, fonts, etc.)
├── src/
│   ├── assets/             # 3D models, images, and other assets
│   ├── components/         # React components for the UI
│   ├── constants/          # Constant values used across the app
│   ├── hooks/              # Custom hooks for state management
│   ├── models/             # 3D model configurations
│   ├── pages/              # Different pages of the portfolio
│   ├── App.jsx             # Main app component
│   ├── index.css           # Global CSS
│   ├── main.jsx            # Entry point for React
├── .env.local              # Environment variables (local)
├── .eslintrc.cjs           # ESLint configuration
├── .gitignore              # Git ignore file
├── index.html              # HTML template
├── package.json            # Project dependencies and scripts
├── README.md               # Project description and details
├── postcss.config.js       # PostCSS configuration
├── tailwind.config.js      # Tailwind CSS configuration
├── vite.config.js          # Vite configuration
```

This structure ensures the project is modular, maintainable, and optimized for performance, with React handling the UI, Three.js managing the 3D models, and Tailwind CSS providing responsive styling.
