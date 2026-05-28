# React App Development Guidelines

## Project Overview

This is a React application built with Vite, featuring a modular component-based architecture.

## Code Style & Conventions

### File Naming

- Components: PascalCase (e.g., `Button.jsx`, `UserCard.jsx`)
- Utilities: camelCase (e.g., `formatDate.js`, `apiClient.js`)
- CSS files: Match component name or feature (e.g., `Button.css`)

### Component Structure

- Functional components only
- Use React hooks for state and side effects
- One component per file in the `src/components/` directory

### Folder Structure

- `src/components/` - Reusable components
- `src/pages/` - Page-level components (for routing)
- `src/hooks/` - Custom React hooks
- `src/utils/` - Utility functions and helpers
- `src/styles/` - Global and component-specific styles
- `public/` - Static assets

## Development Workflow

1. **Setup**: `npm install`
2. **Development**: `npm run dev` (starts dev server on port 5173)
3. **Build**: `npm run build` (creates optimized production build)
4. **Linting**: `npm run lint` or `npm run lint:fix`

## Best Practices

- Keep components small and focused
- Extract reusable logic into custom hooks
- Use meaningful variable and function names
- Comment complex logic
- Import styles at the component level
