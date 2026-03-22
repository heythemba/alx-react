# alx-react

A React-based School Dashboard application that demonstrates core React concepts including props, components, and state management.

## Overview

This project is a learning management system (LMS) dashboard built from scratch using React without create-react-app. It showcases a school portal with the following features:

- **Header**: Displays the school logo and "School dashboard" title
- **Notifications**: Shows a list of notifications (e.g., new courses, new resumes) with the ability to toggle visibility via the `displayDrawer` prop
- **Login**: A login form with email and password fields for user authentication
- **CourseList**: A table displaying available courses with their credit values (ES6, Webpack, React)
- **Footer**: Displays copyright information with dynamic year and school name

## Project Structure

```
.
├── 0x00-Webpack/          # Webpack configuration tasks
├── 0x02-react_props/      # React props tasks
│   ├── task_0/            # Basic React setup
│   ├── task_2/            # Component props
│   ├── task_3/            # Advanced props
│   └── task_4/            # Latest implementation
│       └── dashboard/
│           ├── src/
│           │   ├── App/
│           │   ├── CourseList/
│           │   ├── Footer/
│           │   ├── Header/
│           │   ├── Login/
│           │   ├── Notifications/
│           │   └── utils/
│           └── config/
```

## Technology Stack

- **React**: UI library for building components
- **Webpack**: Module bundler for development and production builds
- **Jest**: Testing framework
- **Babel**: JavaScript compiler for React JSX support

## Getting Started

### Install Dependencies

```bash
cd 0x02-react_props/task_4/dashboard
npm install
```

### Run Development Server

```bash
npm start
```

### Build for Production

```bash
npm run build
```

### Run Tests

```bash
npm test
```

### Run Tests in Watch Mode

```bash
npm run test-watch
```

## Key Concepts Demonstrated

- **React Components**: Modular UI components (Header, Footer, Notifications, Login, CourseList)
- **Props**: Passing data between parent and child components
- **PropTypes**: Type checking for component props
- **Conditional Rendering**: Displaying Login or CourseList based on `isLoggedIn` prop
- **CSS Modules**: Component-scoped styling
- **Webpack Configuration**: Custom build setup without create-react-app
- **Jest Testing**: Unit tests for components and utilities

## Components

| Component | Description |
|-----------|-------------|
| `App` | Main application container |
| `Header` | School logo and title |
| `Footer` | Copyright information |
| `Notifications` | Notification panel with toggleable drawer |
| `Login` | User login form |
| `CourseList` | Table of available courses |
| `CourseListRow` | Individual row in the course table |
| `NotificationItem` | Individual notification item |
