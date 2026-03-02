# Garmin MES Tech Stack Guide

## I. Key Information

This guide covers the main packages used in the Garmin MES project, categorized by functionality. The tech stack focuses on React-based development with modern libraries for data management, UI components, styling, and utilities. Each package includes descriptions and learning resources to help developers understand and utilize them effectively.

## II. Package Summary

| Package              | Category         | Description                                                                                           |
| -------------------- | ---------------- | ----------------------------------------------------------------------------------------------------- |
| TanStack React Query | Data Fetching    | Powerful data synchronization library for server state management with caching and background updates |
| Axios                | HTTP Client      | Promise-based HTTP client for making API requests with interceptors and error handling                |
| Material-UI (MUI)    | UI Framework     | React UI framework implementing Material Design with components and theming                           |
| @mui/icons-material  | UI Icons         | Material Design icons library that integrates with MUI components                                     |
| @hello-pangea/dnd    | Drag & Drop      | Accessible drag-and-drop library for React applications                                               |
| Tailwind CSS         | Styling          | Utility-first CSS framework for rapid UI development                                                  |
| Day.js               | Date/Time        | Lightweight library for date and time manipulation                                                    |
| Notistack            | Notifications    | Snackbar notification library with Material-UI integration                                            |
| Zustand              | State Management | Simple and scalable state management solution                                                         |

## III. Main Packages

The Garmin MES project relies on several key packages for its functionality. Below is an overview of the main packages used, along with learning resources:

### TanStack React Query

A powerful data synchronization library for React that makes fetching, caching, synchronizing and updating server state in your React applications a breeze. It provides hooks for data fetching with built-in caching, background refetching, and optimistic updates.

- **Learning Resources:**
  - [Official Documentation](https://tanstack.com/query/latest)
  - [React Query Tutorial](https://tanstack.com/query/latest/docs/react/overview)

- **_FAQ_**
  - [useQuery](https://tanstack.com/query/latest/docs/framework/react/reference/useQuery)
  - [useMutation](https://tanstack.com/query/latest/docs/framework/react/reference/useMutation)

### Axios

A promise-based HTTP client for the browser and Node.js. It provides an easy-to-use API for making HTTP requests, with features like request/response interceptors, automatic JSON data transformation, and error handling.

- **Learning Resources:**
  - [Official Documentation](https://axios-http.com/)
  - [Axios API Reference](https://axios-http.com/docs/api_intro)

### Material-UI (MUI)

A popular React UI framework that implements Google's Material Design. It provides a comprehensive set of pre-built components, theming capabilities, and styling solutions for building consistent user interfaces. The project also uses @mui/icons-material for a wide range of Material Design icons that integrate seamlessly with MUI components.

- **Learning Resources:**
  - [Official Documentation](https://mui.com/)
  - [Material-UI Components](https://mui.com/material-ui/getting-started/overview/)
  - [Material Icons](https://mui.com/material-ui/material-icons/)

- **_FAQ_**
  - [How to implement Dark Mode?](https://mui.com/material-ui/customization/dark-mode/)
  - [How to customize theme?](https://mui.com/material-ui/customization/theming/)

### Tailwind CSS

A utility-first CSS framework for rapidly building custom user interfaces. It offers low-level utility classes that let you build complex designs without leaving your HTML, promoting rapid prototyping and consistent styling.

- **Learning Resources:**
  - [Official Documentation](https://tailwindcss.com/)
  - [Tailwind CSS Tutorial](https://tailwindcss.com/docs/utility-first)

- **_FAQ_**
  - [How to integrate Tailwind CSS and MUI?](https://mui.com/material-ui/integrations/tailwindcss/tailwindcss-v4/)

### Notistack

A notification library for React that provides snackbars (toasts) with Material-UI integration. It offers a simple API for displaying temporary messages to users, with features like stacking, positioning, and persistence.

**Learning Resources:**

- [Official Documentation](https://notistack.com/)
- [Notistack Demo](https://notistack.com/)

- **_FAQ_**
  - [Implement Mui with Notistack](https://mui.com/material-ui/react-snackbar/#notistack)

### Zustand

A small, fast and scalable state management solution using simplified flux principles. It provides a hook-based API for managing global state with minimal boilerplate, making it easy to share state across components.

- **Learning Resources:**
  - [Official Documentation](https://zustand-demo.pmnd.rs/)
  - [Zustand Tutorial](https://docs.pmnd.rs/zustand/getting-started/introduction)

### @hello-pangea/dnd

A modern, accessible drag-and-drop library for React that provides a powerful API for implementing drag-and-drop functionality in web applications. It's a maintained fork of react-beautiful-dnd with improved accessibility and modern React support.

- **Learning Resources:**
  - [Official Documentation](https://github.com/hello-pangea/dnd)
  - [React Beautiful DnD Migration Guide](https://github.com/hello-pangea/dnd#migration-from-react-beautiful-dnd)

### Day.js

A minimalist JavaScript library that parses, validates, manipulates, and displays dates and times. It's a lightweight alternative to Moment.js, providing immutable date operations with a simple API.

- **Learning Resources:**
  - [Official Documentation](https://day.js.org/)
  - [Day.js API Reference](https://day.js.org/docs/en/get-set/get)
