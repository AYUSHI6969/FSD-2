# Experiment 2: Single Page Application with React Router & Material-UI

This experiment demonstrates the implementation of a Single Page Application (SPA) using React, React Router, and Material-UI components.

## Learning Outcomes

### 1. Single Page Application (SPA) Architecture
Understand how to build a Single Page Application that dynamically renders different components without full page reloads, providing a seamless user experience with client-side routing using React Router.

### 2. React Router Navigation
Master the implementation of client-side routing using React Router's `BrowserRouter`, `Routes`, `Route`, and `Link` components to enable smooth navigation between multiple pages while maintaining application state.

### 3. Material-UI Component Library Integration
Learn to integrate and utilize Material-UI (MUI) components such as Button, TextField, Rating, Slider, Checkbox, and Select to build professional, responsive, and accessible UI elements with minimal custom styling.

### 4. React State Management with Hooks
Develop proficiency in managing component state using React Hooks (`useState`) to handle form inputs, user interactions, and dynamic component behavior in functional React components.

### 5. Reusable Component Design Patterns
Practice building modular and reusable components that follow React best practices, including component composition, props passing, and creating self-contained feature components (Button component with multiple form elements).

## Project Structure

```
Experiment_2/
├── src/
│   ├── components/
│   │   ├── Home.jsx         - Home page component
│   │   ├── About.jsx        - About page component
│   │   ├── Contact.jsx      - Contact page component
│   │   ├── Spa.jsx          - Main routing component
│   │   └── Button.jsx       - UI components with forms
│   ├── App.jsx              - Root application component
│   ├── App.css              - Application styles
│   ├── main.jsx             - Application entry point
│   └── index.css            - Global styles
├── package.json             - Project dependencies
└── vite.config.js           - Vite configuration
```

## Technologies Used

- **React** - UI library for building components
- **React Router DOM** - Client-side routing solution
- **Material-UI** - Professional component library
- **Emotion** - CSS-in-JS styling
- **Vite** - Fast build tool and dev server
