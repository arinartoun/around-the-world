

# React + Leaflet + JavaScript + Vite App + React-Router (Context + useReducer)
<img width="1920" height="889" alt="screencapture-localhost-5173-app-cities-2026-06-26-15_42_57" src="https://github.com/user-attachments/assets/b3f3b299-13ac-409e-8d45-0e547ed4acd1" />

## Overview

This project is a modern React/Leaflet application built with **Vite** and **JavaScript**, using the **Context API** and **useReducer** for global state management and **React-Router** for handling routes.

Instead of external state libraries, the application relies on React’s built‑in tools to manage and share state across components in a predictable and scalable way.

The architecture focuses on:

- Clear separation of concerns
- Maintainable component structure
- Fast development with Vite

---

## Tech Stack

- **React** – UI library for building components
- **JavaScript** – Static typing for safer and more maintainable code
- **Vite** – Fast development server and build tool
- **React-Router** - managing the routes
- **Context API** – Global state sharing
- **useReducer** – Predictable state transitions
- **Leaflet** - opensource map

---

## Why Context + useReducer?

This project uses **Context + useReducer** as a lightweight alternative to state management libraries like Redux.

Benefits include:

- Centralized state logic
- Predictable updates through actions
- Easier debugging
- Built-in React solution with no extra dependencies


---

## Project Structure

Example structure used in the project:

src/
components/ → Reusable UI components  
 context/ → Context providers and reducers  
 hooks/ → Custom React hooks  
 pages/ → Page-level components  
 App.jsx → Main application component  
 main.jsx → Application entry point

State logic typically lives inside the **context folder**, where reducers and provider components are defined.

## Getting Started

### 1. Clone the repository

```
git clone <repository-url>
cd <project-folder>
```

### 2. Install dependencies

```
npm install
```

### 3. Run the development server
```
npm run server
```

```
npm run dev
```

The app will run at:

```
http://localhost:5173
```

---

## Build for Production

To build the optimized production bundle:

```
npm run build
```

Preview the production build locally:

```
npm run preview
```

---

## Key Concepts Used
### Leaflet
provides a map feature using openstreetmap

### React-Router
used to manages routes and protects them

### Context API

Used to provide global state to the entire component tree without prop drilling.

### useReducer

Manages complex state transitions using explicit actions and a reducer function.


---

## Possible Improvements

Future improvements could include:

- Splitting reducers into multiple modules
- Adding custom hooks for cleaner context usage
- Persisting state with localStorage
- Adding tests with Vitest or React Testing Library

---
