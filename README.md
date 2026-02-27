<p align="center">
  <img src="src/assets/Screenshot 2026-02-27 100408.png" width="600">
</p>


# Learning Progress Dashboard

## Overview

The Learning Progress Dashboard is a Single Page Application (SPA) designed to track and visualize student or user learning progress across multiple modules and activities.  

The project focuses on derived state calculations, dynamic visualizations, controlled interactions, asynchronous updates, and performance-aware component design. It demonstrates how to build a scalable and accessible dashboard system for monitoring learning metrics in a modern frontend architecture.

---

## Project Objectives

This project aims to:

- Implement a component-based architecture for dashboard systems
- Demonstrate derived state computation for performance metrics
- Handle controlled inputs for filtering and module selection
- Simulate asynchronous progress updates
- Provide route-based navigation for multiple learning categories
- Ensure accessibility and keyboard-friendly interactions
- Optimize rendering for dynamic visualizations in a performance-sensitive SPA

---

## Architecture Highlights

### Component-Based Design

The application is structured using reusable UI components such as:

- Progress Indicators
- Charts and Graphs
- Summary Cards
- Module Lists
- Filter Controls

Each component is designed for reusability, separation of concerns, and scalability.

---

### State Management Strategy

- Local state is managed using React Hooks.
- Derived state is calculated dynamically (e.g., completion percentage, average completion time).
- Global or shared state (if applicable) is managed through Context API.
- Controlled components are used for all form inputs and filtering controls.

---

### Routing

The application uses client-side routing to provide:

- Category-based learning views
- Module-specific progress pages
- Summary and analytics views

Routing enables seamless navigation without full page reloads.

---

### Derived Metrics

The dashboard calculates:

- Module completion percentage
- Overall course completion
- Average completion time
- Activity-based performance summaries

All metrics are computed from base state values to ensure consistency and maintainability.

---

### Asynchronous Behavior

The system simulates:

- Module completion updates
- Progress tracking events
- Delayed updates to mimic real-world API calls

This demonstrates handling of asynchronous logic within UI components.

---

### Performance Considerations

- Efficient re-rendering using memoization where necessary
- Derived state instead of redundant storage
- Optimized visualization updates
- Scalable structure for large module datasets

---

### Accessibility

The dashboard follows accessibility best practices:

- Proper semantic HTML structure
- ARIA labels for charts and interactive elements
- Keyboard navigability
- Focus management
- Screen-reader friendly components

---

## Major Features

- Dashboard view with overall and module-wise progress
- Reusable visualization components
- Controlled filtering and module selection
- Route-based navigation across learning categories
- Async simulation of progress updates
- Derived metrics for analytics and summaries
- Accessible and keyboard-friendly UI

---

## Technology Stack

- React (Functional Components & Hooks)
- React Router (Client-side Routing)
- Context API (if implemented)
- Vite (Build Tool)
- Modern CSS / Utility-first styling

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Deploy (if configured):

```bash
npm run deploy
```

---

## Educational Value

This project demonstrates practical implementation of:

- Derived state calculations
- Dynamic UI updates
- Performance-aware component design
- Accessible visualization
- Scalable dashboard architecture

It is designed as an academic project to strengthen understanding of modern SPA development patterns.