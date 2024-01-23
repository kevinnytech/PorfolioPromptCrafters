

# Architecture

This document overviews the software architecture and technologies powering the RoomZone application.

## High Level Overview

RoomZone follows a layered architectural pattern consisting of:

- User Interface Layer 
- Application Layer
- Data Layer
- Infrastructure Layer 

This separation of concerns promotes loose coupling between components.

## UI Layer

The user interface layer handles presentation and user interactions via React frontend components.

Key technologies:

- **React** - Component model for modular UI development 
- **NextJS** - Server-side rendering and tooling
- **Tailwind** - Utility-first CSS styling
- **Clerk** - User authentication UI

Delivers an intuitive, responsive, and visually appealing experience across devices.

## Application Layer

The application layer contains the core business logic and connectivity:

- **Node** - Backend runtime environment
- **API Routes** - Handles image generation, auth
- **Replicate SDK** - AI model integrations
- **Axios** - Outbound data requests

Manages application flows and integrations with external services.

## Data Layer 

The data layer persists application information: 

- **Clerk** - User accounts, sessions
- **Supabase** - User generated content

Focuses on security, resilience, scale, and access control.

## Infrastructure Layer



