# Next.js Project Setup and Basics

## Project Description

This project is a comprehensive introduction to setting up and working with **Next.js**, **TypeScript**, and **Tailwind CSS**. It guides you through creating a modern web application with reusable components, routing, API integration, and proper project structure. From scaffolding the application to building dynamic, responsive components, the project covers core concepts for building scalable front-end applications.

## Learning Objectives

By completing this project, you will:

- Scaffold a Next.js application with TypeScript and Tailwind CSS
- Implement basic routing using the Next.js Pages Router
- Create and reuse modular components with TypeScript interfaces
- Build interactive UI elements like modals and buttons
- Fetch and display data from external APIs (e.g., JSONPlaceholder)
- Follow best practices for project and file structure
- Manage component props and state effectively
- Build responsive layouts with navigation

## Requirements

- Node.js (v16 or later)
- npm or yarn package manager
- Basic knowledge of React and TypeScript
- Familiarity with HTML/CSS
- Git and GitHub account
- Code editor (VS Code recommended)

---

## Best Practices

### ✅ Project Structure

- Organize components by domain (e.g., `layout/`, `common/`)
- Centralize interfaces in the `interfaces/` directory
- Group pages under the `pages/` directory by routes

### ✅ Component Design

- Use modular, reusable component patterns
- Leverage TypeScript interfaces for props
- Follow the Single Responsibility Principle

### ✅ Code Quality

- Use ESLint for linting and consistency
- Maintain a clean and consistent code style
- Add meaningful comments where necessary

### ✅ Performance

- Optimize API calls
- Implement lazy loading where useful
- Use Tailwind CSS utilities for styling efficiency

### ✅ Documentation

- Maintain this README with relevant details
- Document each component's usage and props
- Write clear, descriptive commit messages

---

## Project Structure

alx-project-0x02/
├── components/
│ ├── common/
│ │ ├── Button.tsx
│ │ ├── Card.tsx
│ │ ├── PostCard.tsx
│ │ ├── PostModal.tsx
│ │ └── UserCard.tsx
│ └── layout/
│ └── Header.tsx
├── interfaces/
│ └── index.ts
├── pages/
│ ├── _app.tsx
│ ├── _document.tsx
│ ├── about.tsx
│ ├── home.tsx
│ ├── index.tsx
│ ├── posts.tsx
│ └── users.tsx
├── public/
│ └── assets/
│ └── images/
├── styles/
│ └── globals.css
├── .eslintrc.json
├── next.config.js
├── package.json
├── README.md
└── tsconfig.json

## Implementation Guide & Tasks

### 0. Initial Setup
- Create GitHub repo: `alx-project-0x02-setup`
- Scaffold project with README and initial folder structure

### 1. Next.js + TypeScript + Tailwind Setup
- Scaffold app using `npx create-next-app@latest`
- Enable TypeScript, Tailwind CSS, and ESLint
- Setup project folders and confirm running at [http://localhost:3000](http://localhost:3000)

### 2. Basic Routing
- Create `/home` and `/about` pages
- Add navigation links in `Header.tsx`

### 3. Reusable Card Component
- Create `Card.tsx` using `CardProps` interface
- Use the card in the `/home` page

### 4. Modal Component
- Create `PostModal.tsx` with a form
- Collect user input and display content dynamically on `/home`

### 5. Button Component
- Create `Button.tsx` with support for different `size` and `shape`
- Render buttons in `/about` with various props

### 6. Navigation & Layout
- Implement `Header.tsx` with links to `/home`, `/about`, and `/posts`
- Use the header component on respective pages

### 7. PostCard Component
- Create `PostCard.tsx` using `PostProps`
- Fetch and display posts from JSONPlaceholder in `/posts`

### 8. UserCard Component
- Create `UserCard.tsx` using `UserProps`
- Fetch and display user data in `/users` page

---

## Expected Outcomes

✅ A functional, well-structured Next.js app  
✅ Reusable, modular components with strong typing  
✅ Routing across multiple pages  
✅ API integration and live data display  
✅ Responsive UI built with Tailwind CSS  
✅ Clean, readable, and maintainable codebase

---
  
