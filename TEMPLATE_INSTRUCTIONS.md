# React + Vite + shadcn/ui Template Instructions

## Overview
This is a production-ready React template built with Vite, TypeScript, Tailwind CSS v4, and a complete shadcn/ui component library pre-installed.

## Project Structure

src/
├── components/
│   └── ui/              # All shadcn/ui components (DO NOT MODIFY)
├── hooks/
│   └── use-mobile.ts    # Mobile detection hook
├── lib/
│   └── utils.ts         # cn() utility for class merging
├── assets/              # Static assets
├── App.tsx              # Main application component (START HERE)
├── App.css              # App-specific styles
├── main.tsx             # Application entry point
└── index.css            # Global styles & CSS variables

## Available UI Components
All shadcn/ui components are pre-installed in `@/components/ui/`


## Important Notes

1. **DO NOT modify files in `src/components/ui/`** - These are shadcn/ui components and should remain unchanged.

2. **Start development in `src/App.tsx`** - This is your main entry point for building features.

3. **Create new components in `src/components/`** (not in the `ui` subfolder) for your custom components.

4. **Add new pages/routes** as needed - Consider adding `react-router-dom` if routing is required.

5. **State management** - For complex state, consider adding Zustand, Jotai, or TanStack Query as needed.

6. **API calls** - Consider adding Axios or use native fetch. TanStack Query is recommended for server state.

7. **Dependencies are pre-installed** - All shadcn/ui dependencies including date-fns, recharts, react-day-picker, etc. are ready to use.

8. **Icons** - Use Lucide React icons:
   

## Quick Start
1. Open `src/App.tsx`
2. Import needed components from `@/components/ui/`
3. Build your UI using the pre-installed shadcn/ui components
