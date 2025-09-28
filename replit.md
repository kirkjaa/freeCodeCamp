# Overview

freeCodeCamp.org is an open-source educational platform that provides a comprehensive curriculum for learning web development, data science, and programming. The platform offers interactive coding challenges, certification projects, and a complete learning management system. It features a full-stack architecture with a React/Gatsby frontend, Fastify backend API, and MongoDB database, supporting multiple languages and serving millions of learners worldwide.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React with Gatsby for static site generation and client-side routing
- **State Management**: Redux for global application state
- **Styling**: CSS with PostCSS processing, responsive design principles
- **Testing**: Vitest for unit tests, Playwright for end-to-end testing
- **Build System**: Webpack with Monaco Editor integration for code editing
- **Internationalization**: React-i18next for multi-language support

## Backend Architecture
- **Framework**: Fastify with TypeScript for high-performance API
- **Database ORM**: Prisma for MongoDB interaction with replica set configuration
- **Authentication**: OAuth2 integration with session-based authentication
- **Validation**: TypeBox and Joi for request/response validation
- **Security**: CSRF protection, rate limiting, and CORS handling
- **Monitoring**: Sentry for error tracking and Pino for structured logging

## Challenge System
- **Content Management**: Markdown-based curriculum with YAML frontmatter
- **Code Execution**: Browser-based code runners for JavaScript, Python, and other languages
- **Testing**: Automated test suites for challenge validation
- **Progress Tracking**: User progress persistence with local storage fallback

## Data Storage
- **Primary Database**: MongoDB with replica set configuration
- **Caching**: Browser local storage for user progress and code
- **File Storage**: Static assets and curriculum content in filesystem
- **Session Management**: Secure HTTP-only cookies with CSRF protection

## Development Workflow
- **Package Management**: PNPM with workspace configuration
- **Code Quality**: ESLint, Prettier, and Stylelint with pre-commit hooks
- **Containerization**: Docker Compose for local development environment
- **CI/CD**: GitHub Actions for automated testing and deployment

# External Dependencies

## Third-Party Services
- **Payment Processing**: Stripe for donation handling and subscription management
- **Email Services**: AWS SES for transactional emails and notifications
- **Search**: Algolia for curriculum and content search functionality
- **Feature Flags**: GrowthBook for A/B testing and feature rollouts
- **Error Monitoring**: Sentry for real-time error tracking and performance monitoring

## Educational Integrations
- **Microsoft Learn**: Integration for C# certification programs and trophy verification
- **CodeAlly**: External platform integration for database and container-based projects
- **Certificate Generation**: Automated certification system with verification links

## Development Tools
- **Code Editing**: Monaco Editor for in-browser code editing experience
- **Testing Infrastructure**: Playwright for comprehensive browser testing
- **Email Testing**: MailHog for local email testing and verification
- **Bundle Analysis**: Webpack Bundle Analyzer for performance optimization

## Authentication Providers
- **OAuth2**: Support for multiple authentication providers
- **Session Management**: Secure session handling with HttpOnly cookies
- **CSRF Protection**: Token-based CSRF protection for form submissions