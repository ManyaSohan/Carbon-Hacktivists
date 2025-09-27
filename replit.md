# Carbon Coin - Sustainability Gamification Platform

## Overview

Carbon Coin is a full-stack web application that gamifies sustainability through a reward-based system. Users earn "Carbon Coins" by performing eco-friendly actions, tracking health activities, and completing educational courses. The platform features QR code scanning for waste management validation, health tracking with step counters, educational modules on AI/ML/sustainability topics, and a comprehensive reward system with real prizes. Built with a modern tech stack including React, Express.js, PostgreSQL with Drizzle ORM, and styled with Tailwind CSS and shadcn/ui components.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript, using Vite as the build tool
- **Styling**: Tailwind CSS with shadcn/ui component library for consistent design
- **State Management**: React Query (@tanstack/react-query) for server state management, local React state for UI state
- **Routing**: Wouter for lightweight client-side routing
- **Design System**: Custom theme provider supporting light/dark/night modes with CSS custom properties
- **UI Components**: Comprehensive component library including cards, forms, dialogs, navigation, and specialized components like QR scanner and animated tree visualization

### Backend Architecture
- **Framework**: Express.js with TypeScript running on Node.js
- **Database ORM**: Drizzle ORM for type-safe database operations
- **Authentication**: JWT-based authentication with bcrypt for password hashing
- **API Design**: RESTful API with /api prefix, comprehensive error handling middleware
- **Development**: Hot module replacement with Vite integration for seamless development experience

### Data Storage Solutions
- **Primary Database**: PostgreSQL configured through Drizzle ORM
- **Schema Management**: Type-safe schema definitions with Zod validation
- **Migrations**: Automated database migrations using Drizzle Kit
- **In-Memory Storage**: Fallback memory storage implementation for development/testing

### Authentication and Authorization
- **Password Security**: bcrypt hashing for secure password storage
- **Session Management**: JWT tokens stored in HTTP-only cookies for security
- **User Management**: Complete user registration and login flow with form validation
- **Authorization**: Cookie-based session validation for protected routes

### External Dependencies
- **Database**: Neon Database serverless PostgreSQL for production hosting
- **UI Framework**: Radix UI primitives for accessible component foundations
- **QR Scanning**: qr-scanner library for browser-based QR code recognition with geolocation validation
- **Fonts**: Google Fonts (Poppins, Roboto) for typography
- **Development Tools**: Replit-specific plugins for development environment integration
- **Build System**: esbuild for fast production builds, TSX for development server

### Key Features
- **Gamification**: Comprehensive badge system, streak tracking, coin rewards, and leaderboards
- **Eco Actions**: QR code scanning with geolocation verification for waste management activities
- **Health Tracking**: Step counting and workout logging with coin rewards
- **Education Hub**: Course modules for AI, ML, Cybersecurity, Carbon Emissions, and EVs
- **Rewards System**: Prize redemption for real courses, library access, and sponsored content
- **Responsive Design**: Mobile-first design with glass morphism effects and smooth animations