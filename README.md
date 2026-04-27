# Lazy Loading support with Syncfusion components in React

This repository shows how to load Syncfusion components (for example Grid and Calendar) on demand rather than bundling all component code up front. The project uses route-level code splitting and a small asynchronous loader to import component modules only when their routes are visited, which reduces initial load time.

## Features

- Lazy loads Syncfusion Grid and Calendar components to reduce initial bundle size
- Route-level code splitting so only route-specific components are fetched when needed
- Small async loader wrapper for consistent error and loading state handling
- Preserves responsive behavior and feature parity with eagerly-loaded components
- Demonstrates on-demand registration of Syncfusion modules to avoid unnecessary imports

## Prerequisites

Refer to the Syncfusion React getting started documentation for setup and licensing: https://ej2.syncfusion.com/react/documentation/introduction/

## Installation and Run

Install the project dependencies:
```bash
npm install
```

To Build the project:
```bash
npm run build
```

To Start the development server:
```bash
npm run start
```
