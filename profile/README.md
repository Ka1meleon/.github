# KAIMELEON Repository Structure

## 📂 Our Repositories

### Backend Services (NestJS)

- **[kaimeleon-backend](https://github.com/Ka1meleon/kaimeleon-backend)** (TypeScript)
  - Main NestJS backend service accessible at `api.kaimeleon.com`
  - Provides core API endpoints and business logic for the platform
  - Documentation available at `api.kaimeleon.com/documentation`
  - Handles authentication, data processing, and platform-wide services

- **[kai-agent](https://github.com/Ka1meleon/kai-agent)** (TypeScript)
  - NestJS application containing all logic for MCP integrations
  - Manages connections with 3rd party tooling and our own services
  - Handles AI agent functionality, natural language processing, and automated workflows
  - Responsible for intelligent task routing and context-aware processing

- **[kai-clients](https://github.com/Ka1meleon/kai-clients)** (TypeScript)
  - NestJS service for custom client integrations
  - Accessible at `clients.kaimeleon.com/documentation`
  - Provides client-specific API endpoints and customization options
  - Manages client data models and integration points

### Frontend Applications

- **[kai-hub](https://github.com/Ka1meleon/kai-hub)** (TypeScript)
  - Centralized SaaS dashboard application
  - User interface for managing and monitoring AI integrations
  - Provides analytics, configuration controls, and system status
  - Central access point for users to interact with the KAIMELEON ecosystem

- **[kai-meeting](https://github.com/Ka1meleon/kai-meeting)** (TypeScript)
  - Ionic-based Progressive Web Application (PWA)
  - Specialized tool for recording and processing meetings
  - Captures audio, generates transcriptions, and extracts insights
  - Integrates with the broader KAIMELEON platform for data utilization

- **[brand-website](https://github.com/Ka1meleon/brand-website)** (TypeScript)
  - Public-facing marketing website
  - Showcases KAIMELEON's capabilities and service offerings
  - Entry point for new users and clients

## 🔄 System Architecture

Our platform consists of three NestJS backend services handling different aspects of the system:
- Core API functionality (`kaimeleon-backend`)
- AI and integration services (`kai-agent`)
- Client-specific customizations (`kai-clients`)

These backend services support our frontend applications, including our main dashboard (`kai-hub`) and specialized tools like our meeting recorder (`kai-meeting`).

## 📚 Documentation

- API Documentation: `api.kaimeleon.com/documentation`
- Client Integration Documentation: `clients.kaimeleon.com/documentation`
- GitHub Organization: [Ka1meleon](https://github.com/Ka1meleon)

---

<p align="center">© 2025 KAIMELEON</p>
