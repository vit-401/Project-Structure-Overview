<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Structure Overview</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        h2 { color: #2E86C1; }
        ul { list-style-type: none; }
        li { margin-bottom: 10px; }
        .directory { color: #D35400; font-weight: bold; }
        .description { margin-left: 20px; }
    </style>
</head>
<body>
    <h1>Project Structure Overview</h1>
    <ul>
        <li><span class="directory">src/ - Source Code</span>
            <p class="description">Root Directory for all application source code.</p>
        </li>
        <li><span class="directory">src/app.module.ts - Main Module</span>
            <p class="description">Entry Point Module that organizes the application by importing other modules.</p>
        </li>
        <li><span class="directory">src/app.controller.ts - Base Controller</span>
            <p class="description">Application's Main Controller handling the base routes.</p>
        </li>
        <li><span class="directory">src/app.service.ts - Base Service</span>
            <p class="description">Provides business logic for the main application features.</p>
        </li>
        <li><span class="directory">src/app.controller.spec.ts - Test Specification</span>
            <p class="description">Contains Unit Tests for the AppController.</p>
        </li>
        <li><span class="directory">src/auth/ - Authentication Module</span>
            <p class="description">Handles User Authentication and Authorization, including strategies for OAuth providers like Google and GitHub.</p>
        </li>
        <li><span class="directory">src/configs/ - Configuration Files</span>
            <p class="description">Contains configuration settings, such as Swagger configuration for API documentation.</p>
        </li>
        <li><span class="directory">src/features/ - Feature Modules</span>
            <p class="description">Organized by feature, e.g., security-devices and profile, each containing its controllers, services, and models relevant to specific application features.</p>
        </li>
        <li><span class="directory">src/modules/ - Shared Modules</span>
            <p class="description">Contains shared components like pipes and filters that can be reused across the application.</p>
        </li>
        <li><span class="directory">src/prisma.service.ts - Prisma Service</span>
            <p class="description">Abstraction layer for database access using Prisma ORM.</p>
        </li>
        <li><span class="directory">src/types/ - Type Definitions</span>
            <p class="description">Holds custom TypeScript types and interfaces used throughout the application.</p>
        </li>
        <li><span class="directory">src/utils/ - Utilities</span>
            <p class="description">Utility functions and helpers, such as date converters and validators.</p>
        </li>
        <li><span class="directory">test/ - End-to-End Tests</span>
            <p class="description">Contains e2e tests for the application, ensuring the integrated components work together correctly.</p>
        </li>
        <li><span class="directory">swagger-static/ - Swagger UI Static Files</span>
            <p class="description">Static files to serve the Swagger UI, providing a visual documentation for the API.</p>
        </li>
        <li><span class="directory">tsconfig.app.json - TypeScript Configuration</span>
            <p class="description">Configuration file for TypeScript compiler specific to the application code.</p>
        </li>
    </ul>
</body>
</html>
