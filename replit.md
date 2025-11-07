# AviateIQ - Aviation Intelligence Platform

## Overview

AviateIQ is a comprehensive aviation intelligence platform designed as a Progressive Web App (PWA) for mobile-first use. The application provides real-time flight tracking, weather monitoring, flight logging, and social features for aviation enthusiasts, pilots, and drone operators. Built with a React frontend and Express backend, the platform offers flight planning tools, aircraft tracking capabilities, and a community-driven social experience for aviation professionals and hobbyists.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **React SPA with Vite**: Modern frontend build tooling with hot module replacement for development
- **TypeScript**: Full type safety across the application stack
- **Wouter**: Lightweight client-side routing library for navigation
- **Tailwind CSS + shadcn/ui**: Utility-first styling with pre-built component library
- **TanStack Query**: Server state management with automatic caching and background updates
- **PWA Support**: Service worker implementation for offline functionality and app-like experience

### Backend Architecture
- **Express.js**: RESTful API server with middleware-based request processing
- **In-memory Storage**: Development-focused storage layer with interface for easy database migration
- **Modular Route System**: Organized API endpoints for aircraft, weather, flight logs, social posts, and alerts
- **Real-time Updates**: Polling-based data refresh for live aircraft tracking and weather information

### Data Storage Solutions
- **Drizzle ORM**: Type-safe database toolkit configured for PostgreSQL
- **Neon Database**: Serverless PostgreSQL database with connection pooling
- **Shared Schema**: Centralized type definitions shared between frontend and backend
- **Zod Validation**: Runtime type checking and schema validation for API inputs

### Authentication and Authorization
- **Session-based Authentication**: Express sessions with PostgreSQL session store
- **User Management**: Support for multiple user types (enthusiast, drone pilot, airplane, helicopter, weather balloon)
- **Privacy Controls**: Public/private visibility settings for flight logs and social posts

### External Dependencies
- **Radix UI**: Headless component primitives for accessible UI components
- **React Hook Form**: Form state management with validation
- **Date-fns**: Date manipulation and formatting utilities
- **Embla Carousel**: Touch-friendly carousel component for image galleries
- **Class Variance Authority**: Utility for component variant management

The application follows a mobile-first design philosophy with responsive layouts, touch-friendly interactions, and PWA capabilities for native app-like experience on mobile devices. The architecture supports real-time data updates through polling mechanisms and provides comprehensive aviation-specific features including flight planning, weather analysis, and social networking for the aviation community.