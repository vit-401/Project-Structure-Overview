# Project Structure Overview

## `src/` - Source Code
Root Directory for all application source code.

## `src/app.module.ts` - Main Module
Entry Point Module that organizes the application by importing other modules.

## `src/app.controller.ts` - Base Controller
Application's Main Controller handling the base routes.

## `src/app.service.ts` - Base Service
Provides business logic for the main application features.

## `src/app.controller.spec.ts` - Test Specification
Contains Unit Tests for the AppController.

## `src/auth/` - Authentication Module
Handles User Authentication and Authorization, including strategies for OAuth providers like Google and GitHub.

## `src/configs/` - Configuration Files
Contains configuration settings, such as Swagger configuration for API documentation.

## `src/features/` - Feature Modules
Organized by feature, e.g., security-devices and profile, each containing its controllers, services, and models relevant to specific application features.

## `src/modules/` - Shared Modules
Contains shared components like pipes and filters that can be reused across the application.

## `src/prisma.service.ts` - Prisma Service
Abstraction layer for database access using Prisma ORM.

## `src/types/` - Type Definitions
Holds custom TypeScript types and interfaces used throughout the application.

## `src/utils/` - Utilities
Utility functions and helpers, such as date converters and validators.

## `test/` - End-to-End Tests
Contains e2e tests for the application, ensuring the integrated components work together correctly.

## `swagger-static/` - Swagger UI Static Files
Static files to serve the Swagger UI, providing a visual documentation for the API.

## `tsconfig.app.json` - TypeScript Configuration
Configuration file for TypeScript compiler specific to the application code.
