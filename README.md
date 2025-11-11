# Evaluate Software Engineer Skills

A comprehensive guide to evaluating software engineers across different technologies and experience levels (Junior, Mid, Senior).

## Table of Contents

- [Overview](#overview)
- [Experience Levels](#experience-levels)
- [Mobile Technologies](#mobile-technologies)
  - [Flutter](#flutter)
  - [React Native](#react-native)
  - [Android Kotlin + Jetpack Compose](#android-kotlin--jetpack-compose)
  - [Kotlin Multiplatform (KMP)](#kotlin-multiplatform-kmp)
  - [iOS Native](#ios-native)
- [Web Frontend](#web-frontend)
  - [ReactJS](#reactjs)
  - [NextJS](#nextjs)
- [Backend](#backend)
  - [NestJS](#nestjs)
  - [ExpressJS](#expressjs)
  - [Laravel](#laravel)
- [Database](#database)
  - [MySQL](#mysql)
  - [NoSQL](#nosql)
- [Assessment Methodology](#assessment-methodology)
- [Scoring Guidelines](#scoring-guidelines)

---

## Overview

This repository provides structured evaluation criteria for assessing software engineer skills across multiple technology stacks. Each technology includes specific evaluation points tailored to Junior, Mid, and Senior experience levels.

## Experience Levels

### Junior Developer
- 0-2 years of experience
- Focuses on learning fundamentals and best practices
- Requires guidance and supervision
- Implements well-defined features

### Mid-Level Developer
- 2-5 years of experience
- Works independently on features
- Understands architecture and design patterns
- Mentors junior developers
- Makes technical decisions within scope

### Senior Developer
- 5+ years of experience
- Designs system architecture
- Drives technical decisions
- Leads projects and teams
- Mentors team members at all levels
- Considers scalability, performance, and maintainability

---

## Mobile Technologies

### Flutter

#### Junior Level
**Core Skills:**
- [ ] Understands Dart basics (null safety, async/await)
- [ ] Can create basic UI with common widgets (Container, Text, Column, Row)
- [ ] Knows StatefulWidget vs StatelessWidget
- [ ] Can handle user input and basic navigation
- [ ] Understands widget lifecycle

**Assignment Ideas:**
1. Build a simple todo list app with add/delete functionality
2. Create a profile page with forms and validation
3. Implement a list view with API data fetching
4. Build a simple calculator app

**Evaluation Criteria:**
- Clean code structure
- Proper widget composition
- Basic state management
- UI responsiveness
- Error handling basics

#### Mid Level
**Core Skills:**
- [ ] Proficient with state management (Provider, Riverpod, or BLoC)
- [ ] Implements custom animations and transitions
- [ ] Handles complex navigation patterns
- [ ] Integrates REST APIs and handles responses
- [ ] Writes unit and widget tests
- [ ] Understands platform channels
- [ ] Implements responsive layouts for different screen sizes

**Assignment Ideas:**
1. Build an e-commerce app with cart, products, and checkout
2. Create a social media feed with infinite scroll and caching
3. Implement a dashboard with charts and real-time updates
4. Build an offline-first app with local database

**Evaluation Criteria:**
- State management implementation
- Code organization and architecture
- Testing coverage
- Performance optimization
- Error handling and edge cases
- API integration patterns

#### Senior Level
**Core Skills:**
- [ ] Architects scalable Flutter applications
- [ ] Creates custom widgets and packages
- [ ] Optimizes performance (build optimization, lazy loading)
- [ ] Implements advanced state management solutions
- [ ] Designs and implements CI/CD pipelines
- [ ] Expert in platform-specific integrations
- [ ] Knowledge of app deployment and maintenance
- [ ] Implements accessibility features

**Assignment Ideas:**
1. Design a modular architecture for a multi-tenant app
2. Create a reusable component library with documentation
3. Implement a complex feature with offline sync
4. Optimize an existing app's performance
5. Design a microservices integration strategy

**Evaluation Criteria:**
- Architecture design and scalability
- Performance optimization techniques
- Code reusability and maintainability
- Testing strategy (unit, widget, integration)
- Documentation quality
- CI/CD implementation
- Security considerations

---

### React Native

#### Junior Level
**Core Skills:**
- [ ] Understands JavaScript/TypeScript basics
- [ ] Can create basic components with JSX
- [ ] Knows React hooks (useState, useEffect)
- [ ] Implements basic styling with StyleSheet
- [ ] Handles basic navigation (React Navigation)

**Assignment Ideas:**
1. Build a weather app consuming a public API
2. Create a note-taking app with local storage
3. Implement a contact list with search functionality
4. Build a simple news reader app

**Evaluation Criteria:**
- Component structure
- Props and state management
- Basic styling
- Navigation implementation
- Code readability

#### Mid Level
**Core Skills:**
- [ ] Proficient with React hooks and custom hooks
- [ ] Implements state management (Redux, MobX, Zustand)
- [ ] Handles complex navigation patterns
- [ ] Integrates native modules
- [ ] Implements animations (Reanimated)
- [ ] Writes Jest and React Native Testing Library tests
- [ ] Handles platform-specific code

**Assignment Ideas:**
1. Build a chat application with real-time messaging
2. Create a fitness tracking app with charts
3. Implement a payment flow with third-party SDK
4. Build a media player app with background playback

**Evaluation Criteria:**
- State management patterns
- Code architecture
- Testing approach
- Animation implementation
- Native module integration
- Performance considerations

#### Senior Level
**Core Skills:**
- [ ] Architects scalable React Native applications
- [ ] Creates bridge modules for native functionality
- [ ] Optimizes performance (memoization, virtualization)
- [ ] Implements advanced animations and gestures
- [ ] Expertise in debugging native issues
- [ ] Designs and implements build pipelines
- [ ] Knowledge of app store deployment
- [ ] Implements code push and OTA updates

**Assignment Ideas:**
1. Design a hybrid architecture for web and mobile
2. Create a custom native module with Swift/Kotlin
3. Implement a complex state synchronization system
4. Optimize a poorly performing app
5. Design a white-label app architecture

**Evaluation Criteria:**
- System architecture design
- Native bridge implementation
- Performance optimization
- Build and deployment strategy
- Code quality and maintainability
- Security implementation
- Team leadership approach

---

### Android Kotlin + Jetpack Compose

#### Junior Level
**Core Skills:**
- [ ] Understands Kotlin basics (null safety, lambdas, extension functions)
- [ ] Can create basic UI with Compose
- [ ] Knows composable functions and state
- [ ] Implements basic navigation with Navigation Compose
- [ ] Understands Activity and Fragment lifecycle

**Assignment Ideas:**
1. Build a task management app
2. Create a simple shopping list app
3. Implement a BMI calculator
4. Build a quote of the day app with API

**Evaluation Criteria:**
- Kotlin code quality
- Composable structure
- State management basics
- Navigation flow
- UI/UX implementation

#### Mid Level
**Core Skills:**
- [ ] Proficient with Jetpack Compose (LazyColumn, animations, gestures)
- [ ] Implements MVVM architecture with ViewModel
- [ ] Uses Kotlin Coroutines and Flow
- [ ] Integrates Room database
- [ ] Implements dependency injection (Hilt/Koin)
- [ ] Writes unit and UI tests
- [ ] Handles configuration changes

**Assignment Ideas:**
1. Build a movie app with TMDB API
2. Create a expense tracker with local database
3. Implement a music player with media controls
4. Build a real-time stock tracking app

**Evaluation Criteria:**
- Architecture implementation (MVVM/MVI)
- Coroutines and Flow usage
- Database implementation
- Dependency injection
- Testing coverage
- Error handling
- Material Design adherence

#### Senior Level
**Core Skills:**
- [ ] Architects complex Android applications
- [ ] Implements multi-module architecture
- [ ] Expertise in Compose performance optimization
- [ ] Creates custom Compose components
- [ ] Implements advanced navigation patterns
- [ ] Designs CI/CD with Gradle
- [ ] Knowledge of Android security best practices
- [ ] Implements background processing (WorkManager)

**Assignment Ideas:**
1. Design a modular app architecture with feature modules
2. Create a custom design system with Compose
3. Implement a complex offline-first sync system
4. Optimize an app's startup time and memory usage
5. Design a plugin-based architecture

**Evaluation Criteria:**
- Architecture design and modularity
- Performance optimization
- Custom component creation
- Build configuration
- Security implementation
- Testing strategy
- Documentation and code review practices

---

### Kotlin Multiplatform (KMP)

#### Junior Level
**Core Skills:**
- [ ] Understands Kotlin basics
- [ ] Knows expect/actual declarations
- [ ] Can create shared business logic
- [ ] Understands platform-specific implementations
- [ ] Basic knowledge of Gradle configuration

**Assignment Ideas:**
1. Create a shared data model library
2. Build a shared networking layer
3. Implement shared validation logic
4. Create a shared preferences wrapper

**Evaluation Criteria:**
- Code sharing approach
- Platform-specific implementations
- Module organization
- Basic testing

#### Mid Level
**Core Skills:**
- [ ] Proficient with KMP architecture patterns
- [ ] Implements shared ViewModels/Presenters
- [ ] Uses Ktor for networking
- [ ] Implements SQLDelight for shared database
- [ ] Handles platform-specific UI bindings
- [ ] Writes shared tests
- [ ] Configures Gradle for multiple targets

**Assignment Ideas:**
1. Build a cross-platform app with shared business logic
2. Create a shared authentication system
3. Implement a shared caching layer
4. Build a shared analytics framework

**Evaluation Criteria:**
- Shared code architecture
- Platform integration
- Dependency injection in KMP
- Testing shared code
- Build configuration
- Code reusability percentage

#### Senior Level
**Core Skills:**
- [ ] Designs KMP architectures for enterprise apps
- [ ] Creates reusable KMP libraries/SDKs
- [ ] Optimizes build times and configurations
- [ ] Implements CI/CD for multiple platforms
- [ ] Expertise in platform interoperability
- [ ] Designs plugin architectures
- [ ] Knowledge of KMP limitations and workarounds

**Assignment Ideas:**
1. Design a complete KMP app architecture
2. Create a KMP SDK for third-party integration
3. Implement a complex state management system
4. Design a migration strategy from native to KMP
5. Optimize a KMP project's build and runtime performance

**Evaluation Criteria:**
- Architecture design
- Code sharing strategy
- Platform-specific optimization
- Build system design
- Documentation and API design
- Migration planning
- Team enablement approach

---

### iOS Native

#### Junior Level
**Core Skills:**
- [ ] Understands Swift basics (optionals, protocols, closures)
- [ ] Can create UI with UIKit or SwiftUI
- [ ] Knows View Controller lifecycle
- [ ] Implements basic navigation
- [ ] Handles user input and delegates

**Assignment Ideas:**
1. Build a simple todo app
2. Create a tip calculator
3. Implement a photo gallery viewer
4. Build a unit converter app

**Evaluation Criteria:**
- Swift code quality
- UI implementation
- Auto Layout or SwiftUI views
- Navigation patterns
- Code organization

#### Mid Level
**Core Skills:**
- [ ] Proficient with SwiftUI or UIKit
- [ ] Implements MVVM or similar architecture
- [ ] Uses Combine or async/await
- [ ] Integrates Core Data or Realm
- [ ] Handles networking with URLSession
- [ ] Writes XCTest unit tests
- [ ] Implements animations and transitions

**Assignment Ideas:**
1. Build a restaurant finder app with MapKit
2. Create a personal finance tracker
3. Implement a video streaming app
4. Build a fitness tracking app with HealthKit

**Evaluation Criteria:**
- Architecture implementation
- State management
- Database integration
- Networking patterns
- Testing coverage
- Memory management
- iOS design guidelines adherence

#### Senior Level
**Core Skills:**
- [ ] Architects iOS applications at scale
- [ ] Implements modular architecture
- [ ] Creates custom frameworks and libraries
- [ ] Expertise in performance optimization
- [ ] Implements CI/CD with Fastlane/Xcode Cloud
- [ ] Knowledge of App Store guidelines and submission
- [ ] Implements advanced security features
- [ ] Experience with metal or advanced graphics

**Assignment Ideas:**
1. Design a multi-module iOS app architecture
2. Create a custom framework for cross-team use
3. Implement a complex animation system
4. Optimize app performance and memory usage
5. Design an app extension architecture

**Evaluation Criteria:**
- System architecture
- Framework design
- Performance optimization
- Build and deployment automation
- Security implementation
- Code review and mentoring approach
- App Store optimization

---

## Web Frontend

### ReactJS

#### Junior Level
**Core Skills:**
- [ ] Understands JavaScript/TypeScript fundamentals
- [ ] Can create functional components
- [ ] Knows React hooks (useState, useEffect, useContext)
- [ ] Implements basic styling (CSS/SCSS)
- [ ] Handles forms and validation
- [ ] Understands component props and composition

**Assignment Ideas:**
1. Build a todo list with local storage
2. Create a weather dashboard
3. Implement a product catalog with filtering
4. Build a simple blog reader

**Evaluation Criteria:**
- Component structure
- Hook usage
- Props management
- Styling approach
- Code readability
- Basic accessibility

#### Mid Level
**Core Skills:**
- [ ] Proficient with React hooks and custom hooks
- [ ] Implements state management (Redux, Zustand, Recoil)
- [ ] Uses React Router for navigation
- [ ] Integrates REST/GraphQL APIs
- [ ] Implements responsive design
- [ ] Writes Jest and React Testing Library tests
- [ ] Optimizes performance (memoization, lazy loading)

**Assignment Ideas:**
1. Build an e-commerce site with cart and checkout
2. Create a dashboard with data visualization
3. Implement a social media feed
4. Build a real-time collaboration tool

**Evaluation Criteria:**
- State management patterns
- API integration
- Testing approach
- Performance optimization
- Responsive design
- Error handling
- Code organization

#### Senior Level
**Core Skills:**
- [ ] Architects scalable React applications
- [ ] Creates reusable component libraries
- [ ] Implements micro-frontend architecture
- [ ] Expertise in performance optimization
- [ ] Designs build and deployment pipelines
- [ ] Implements advanced patterns (render props, HOC, compound components)
- [ ] Knowledge of SEO optimization
- [ ] Implements accessibility standards (WCAG)

**Assignment Ideas:**
1. Design a component library with Storybook
2. Architect a micro-frontend application
3. Implement a complex state machine
4. Create a design system with documentation
5. Optimize a poorly performing React app

**Evaluation Criteria:**
- Architecture design
- Component reusability
- Performance metrics
- Build optimization
- Accessibility compliance
- Documentation quality
- Team leadership approach
- SEO implementation

---

### NextJS

#### Junior Level
**Core Skills:**
- [ ] Understands Next.js basics (pages, routing)
- [ ] Can create static and dynamic pages
- [ ] Knows getServerSideProps and getStaticProps
- [ ] Implements basic API routes
- [ ] Understands file-based routing

**Assignment Ideas:**
1. Build a blog with markdown content
2. Create a portfolio website
3. Implement a product listing page
4. Build a simple CMS-backed site

**Evaluation Criteria:**
- Page structure
- Data fetching methods
- Routing implementation
- API routes usage
- Basic SEO implementation

#### Mid Level
**Core Skills:**
- [ ] Proficient with Next.js 13+ features (App Router, Server Components)
- [ ] Implements ISR and SSG strategies
- [ ] Uses Next.js API routes effectively
- [ ] Implements authentication (NextAuth)
- [ ] Optimizes images and fonts
- [ ] Handles internationalization (i18n)
- [ ] Implements middleware

**Assignment Ideas:**
1. Build a SaaS application with authentication
2. Create a multi-language e-commerce site
3. Implement a headless CMS integration
4. Build a real-time analytics dashboard

**Evaluation Criteria:**
- Rendering strategy selection
- API design
- Authentication implementation
- Performance optimization
- SEO implementation
- Internationalization
- Caching strategies

#### Senior Level
**Core Skills:**
- [ ] Architects Next.js applications at scale
- [ ] Implements advanced caching strategies
- [ ] Optimizes Core Web Vitals
- [ ] Designs edge computing solutions
- [ ] Implements advanced authentication patterns
- [ ] Creates custom server configurations
- [ ] Knowledge of deployment strategies (Vercel, self-hosted)
- [ ] Implements monitoring and analytics

**Assignment Ideas:**
1. Design a multi-tenant SaaS architecture
2. Implement a global CDN strategy
3. Create a hybrid rendering system
4. Optimize an existing app for performance
5. Design a migration strategy to Next.js

**Evaluation Criteria:**
- Architecture design
- Performance optimization
- Edge computing implementation
- Security best practices
- Deployment strategy
- Monitoring and logging
- Team scaling approach
- Cost optimization

---

## Backend

### NestJS

#### Junior Level
**Core Skills:**
- [ ] Understands TypeScript basics
- [ ] Can create controllers and services
- [ ] Knows dependency injection basics
- [ ] Implements basic CRUD operations
- [ ] Understands decorators
- [ ] Can connect to a database

**Assignment Ideas:**
1. Build a REST API for a todo app
2. Create a user management system
3. Implement a simple blog API
4. Build a product inventory API

**Evaluation Criteria:**
- Project structure
- Controller design
- Service implementation
- DTO usage
- Basic validation
- Error handling

#### Mid Level
**Core Skills:**
- [ ] Proficient with NestJS modules and providers
- [ ] Implements authentication (JWT, Passport)
- [ ] Uses TypeORM or Prisma effectively
- [ ] Implements guards and interceptors
- [ ] Handles validation with class-validator
- [ ] Writes unit and e2e tests
- [ ] Implements logging and monitoring
- [ ] Uses configuration management

**Assignment Ideas:**
1. Build a multi-tenant SaaS API
2. Create a microservices system
3. Implement a file upload service
4. Build a real-time notification system

**Evaluation Criteria:**
- Architecture patterns
- Authentication/authorization
- Database design
- Middleware usage
- Testing coverage
- Error handling strategy
- API documentation
- Performance considerations

#### Senior Level
**Core Skills:**
- [ ] Architects microservices with NestJS
- [ ] Implements advanced patterns (CQRS, Event Sourcing)
- [ ] Designs GraphQL APIs
- [ ] Implements message queues (RabbitMQ, Kafka)
- [ ] Creates custom decorators and pipes
- [ ] Designs CI/CD pipelines
- [ ] Implements distributed tracing
- [ ] Knowledge of scalability patterns

**Assignment Ideas:**
1. Design a microservices architecture
2. Implement an event-driven system
3. Create a GraphQL federation setup
4. Design a rate limiting and caching strategy
5. Architect a high-availability system

**Evaluation Criteria:**
- System architecture
- Scalability design
- Performance optimization
- Security implementation
- Testing strategy
- Documentation quality
- DevOps practices
- Team leadership approach

---

### ExpressJS

#### Junior Level
**Core Skills:**
- [ ] Understands JavaScript/Node.js basics
- [ ] Can create routes and handlers
- [ ] Knows middleware concept
- [ ] Implements basic CRUD operations
- [ ] Handles request/response objects
- [ ] Can connect to databases

**Assignment Ideas:**
1. Build a REST API for a library system
2. Create a simple authentication system
3. Implement a file upload service
4. Build a URL shortener API

**Evaluation Criteria:**
- Route organization
- Middleware usage
- Error handling
- Database integration
- Code structure
- Basic validation

#### Mid Level
**Core Skills:**
- [ ] Proficient with Express middleware
- [ ] Implements authentication (JWT, sessions)
- [ ] Uses ORM/ODM (Sequelize, Mongoose)
- [ ] Implements validation and sanitization
- [ ] Handles file uploads and streaming
- [ ] Writes tests (Jest, Mocha)
- [ ] Implements logging (Winston, Morgan)
- [ ] Uses environment configuration

**Assignment Ideas:**
1. Build an e-commerce API
2. Create a social media backend
3. Implement a payment processing system
4. Build a real-time chat API

**Evaluation Criteria:**
- Code architecture
- Security implementation
- Database design
- API design patterns
- Testing approach
- Error handling
- Performance optimization
- Documentation

#### Senior Level
**Core Skills:**
- [ ] Architects Node.js/Express applications
- [ ] Implements microservices patterns
- [ ] Optimizes performance (clustering, caching)
- [ ] Designs API gateway patterns
- [ ] Implements advanced security measures
- [ ] Creates custom middleware
- [ ] Designs CI/CD pipelines
- [ ] Knowledge of scalability patterns

**Assignment Ideas:**
1. Design a microservices architecture
2. Implement a GraphQL server
3. Create a real-time bidding system
4. Design a distributed caching strategy
5. Architect a serverless API

**Evaluation Criteria:**
- System architecture
- Scalability design
- Performance optimization
- Security best practices
- Testing strategy
- DevOps implementation
- Monitoring and logging
- Team leadership

---

### Laravel

#### Junior Level
**Core Skills:**
- [ ] Understands PHP basics
- [ ] Can create routes and controllers
- [ ] Knows Blade templating
- [ ] Implements basic CRUD with Eloquent
- [ ] Understands MVC pattern
- [ ] Can create migrations

**Assignment Ideas:**
1. Build a blog with posts and comments
2. Create a contact management system
3. Implement a task management app
4. Build a simple CMS

**Evaluation Criteria:**
- Code organization
- Controller structure
- Eloquent usage
- Blade templates
- Routing patterns
- Database migrations

#### Mid Level
**Core Skills:**
- [ ] Proficient with Eloquent relationships
- [ ] Implements authentication (Laravel Sanctum/Passport)
- [ ] Uses form requests for validation
- [ ] Implements authorization policies
- [ ] Creates custom artisan commands
- [ ] Writes PHPUnit tests
- [ ] Uses queues and jobs
- [ ] Implements caching

**Assignment Ideas:**
1. Build an e-commerce platform
2. Create a multi-tenant application
3. Implement a booking system
4. Build a content management system

**Evaluation Criteria:**
- Architecture patterns
- Authentication/authorization
- Database design
- Queue implementation
- Testing coverage
- API design
- Performance optimization
- Security practices

#### Senior Level
**Core Skills:**
- [ ] Architects Laravel applications at scale
- [ ] Implements domain-driven design
- [ ] Creates Laravel packages
- [ ] Designs microservices with Laravel
- [ ] Implements event sourcing
- [ ] Optimizes query performance
- [ ] Designs CI/CD pipelines
- [ ] Knowledge of deployment strategies

**Assignment Ideas:**
1. Design a multi-tenant SaaS architecture
2. Create a reusable Laravel package
3. Implement an event-driven system
4. Design a high-traffic API system
5. Architect a headless Laravel application

**Evaluation Criteria:**
- System architecture
- Package design
- Scalability patterns
- Performance optimization
- Security implementation
- Testing strategy
- DevOps practices
- Documentation and mentoring

---

## Database

### MySQL

#### Junior Level
**Core Skills:**
- [ ] Understands basic SQL syntax (SELECT, INSERT, UPDATE, DELETE)
- [ ] Can create tables and relationships
- [ ] Knows primary and foreign keys
- [ ] Implements basic JOINs
- [ ] Understands basic indexing
- [ ] Can write simple queries

**Assignment Ideas:**
1. Design a database for a library system
2. Create tables for an e-commerce store
3. Write queries for a blog application
4. Implement a user management schema

**Evaluation Criteria:**
- Table design
- Relationship implementation
- Query correctness
- Basic normalization
- Constraint usage

#### Mid Level
**Core Skills:**
- [ ] Proficient with complex JOINs and subqueries
- [ ] Implements database normalization (3NF)
- [ ] Uses indexes effectively
- [ ] Writes stored procedures and functions
- [ ] Implements triggers
- [ ] Understands transactions and ACID
- [ ] Optimizes query performance
- [ ] Handles backup and restore

**Assignment Ideas:**
1. Design a normalized database for a multi-tenant SaaS
2. Optimize slow queries in an existing system
3. Implement audit logging with triggers
4. Create a reporting system with complex queries

**Evaluation Criteria:**
- Database design
- Normalization level
- Index strategy
- Query optimization
- Stored procedure quality
- Transaction handling
- Performance considerations

#### Senior Level
**Core Skills:**
- [ ] Designs database architecture for scale
- [ ] Implements replication and clustering
- [ ] Expertise in query optimization
- [ ] Designs partitioning strategies
- [ ] Implements sharding
- [ ] Knowledge of backup and disaster recovery
- [ ] Monitors and tunes performance
- [ ] Implements security best practices

**Assignment Ideas:**
1. Design a high-availability database architecture
2. Implement a sharding strategy for large datasets
3. Create a disaster recovery plan
4. Optimize a database for millions of records
5. Design a data warehouse schema

**Evaluation Criteria:**
- Architecture design
- Scalability planning
- Performance tuning
- High availability setup
- Security implementation
- Monitoring strategy
- Backup and recovery plan
- Capacity planning

---

### NoSQL

#### Junior Level
**Core Skills:**
- [ ] Understands NoSQL basics and types (Document, Key-Value, Graph)
- [ ] Can perform basic CRUD with MongoDB/Firebase/DynamoDB
- [ ] Knows document structure and collections
- [ ] Implements basic queries
- [ ] Understands when to use NoSQL vs SQL

**Assignment Ideas:**
1. Design a document structure for a blog (MongoDB)
2. Create a user profile system (Firebase)
3. Implement a shopping cart (Redis)
4. Build a simple key-value cache

**Evaluation Criteria:**
- Document/schema design
- Query implementation
- Data modeling
- Basic indexing
- Technology selection

#### Mid Level
**Core Skills:**
- [ ] Proficient with document modeling
- [ ] Implements aggregation pipelines (MongoDB)
- [ ] Uses indexes effectively
- [ ] Handles relationships in NoSQL
- [ ] Implements full-text search
- [ ] Understands consistency models
- [ ] Implements caching strategies
- [ ] Handles data migration

**Assignment Ideas:**
1. Design a social media feed system
2. Implement a real-time analytics system
3. Create a recommendation engine database
4. Build a time-series data storage

**Evaluation Criteria:**
- Data modeling approach
- Query optimization
- Aggregation usage
- Index strategy
- Consistency handling
- Performance optimization
- Caching implementation

#### Senior Level
**Core Skills:**
- [ ] Designs NoSQL architectures at scale
- [ ] Implements sharding and replication
- [ ] Expertise in performance optimization
- [ ] Designs multi-region strategies
- [ ] Implements eventual consistency patterns
- [ ] Knowledge of CAP theorem applications
- [ ] Monitors and tunes NoSQL databases
- [ ] Designs hybrid SQL/NoSQL systems

**Assignment Ideas:**
1. Design a globally distributed database system
2. Implement a multi-region replication strategy
3. Create a polyglot persistence architecture
4. Optimize a NoSQL database for high throughput
5. Design a data migration from SQL to NoSQL

**Evaluation Criteria:**
- Architecture design
- Scalability planning
- Consistency model selection
- Performance tuning
- Multi-region strategy
- Monitoring approach
- Migration planning
- Cost optimization

---

## Assessment Methodology

### Code Review Checklist

When evaluating submissions, consider:

1. **Functionality** (25%)
   - Does it work as expected?
   - Are all requirements met?
   - Are edge cases handled?

2. **Code Quality** (25%)
   - Is the code clean and readable?
   - Are naming conventions followed?
   - Is the code DRY (Don't Repeat Yourself)?
   - Are comments used appropriately?

3. **Architecture** (20%)
   - Is the project well-structured?
   - Are design patterns used appropriately?
   - Is the code maintainable?
   - Is there proper separation of concerns?

4. **Testing** (15%)
   - Are there adequate tests?
   - Do tests cover edge cases?
   - Is test code quality good?

5. **Performance** (10%)
   - Are there any obvious performance issues?
   - Is the code optimized appropriately for the level?
   - Are resources handled efficiently?

6. **Documentation** (5%)
   - Is there a clear README?
   - Are complex sections documented?
   - Are API endpoints documented?

### Interview Questions by Level

#### Junior
- Explain basic concepts (e.g., "What is state management?")
- Walk through your code decisions
- Describe challenges faced and solutions
- Explain the project structure

#### Mid
- Explain architecture decisions
- Discuss alternative approaches
- Describe how you would scale the solution
- Explain testing strategy
- Discuss performance considerations

#### Senior
- Discuss system architecture trade-offs
- Explain how you would handle 10x traffic
- Describe migration strategies
- Discuss team collaboration approaches
- Explain how you would mentor juniors on this project

---

## Scoring Guidelines

### Scoring Matrix

| Criteria | Junior (0-2 yrs) | Mid (2-5 yrs) | Senior (5+ yrs) |
|----------|------------------|---------------|-----------------|
| **Functionality** | Basic features work | All features work with edge cases | Complex features with excellent error handling |
| **Code Quality** | Readable with some issues | Clean and consistent | Exemplary, follows best practices |
| **Architecture** | Basic structure | Well-organized, follows patterns | Scalable, maintainable design |
| **Testing** | Basic or minimal tests | Good test coverage | Comprehensive test strategy |
| **Performance** | Works for basic use | Optimized for typical use | Optimized for scale |
| **Documentation** | Basic README | Clear documentation | Comprehensive documentation |

### Pass/Fail Criteria

#### Junior Level
- **Pass:** 60%+ overall score
- Must demonstrate:
  - Working application
  - Basic code organization
  - Fundamental understanding of the technology

#### Mid Level
- **Pass:** 70%+ overall score
- Must demonstrate:
  - All requirements completed
  - Good code quality
  - Proper architecture
  - Some testing
  - Technical depth in interviews

#### Senior Level
- **Pass:** 80%+ overall score
- Must demonstrate:
  - Exceptional code quality
  - Scalable architecture
  - Comprehensive testing
  - Performance optimization
  - Strong technical leadership in interviews

### Time Expectations

- **Junior Assignment:** 4-8 hours
- **Mid Assignment:** 8-16 hours
- **Senior Assignment:** 16-24 hours

Allow candidates to complete assignments within 1-2 weeks based on availability.

---

## How to Use This Guide

1. **Select the Technology:** Choose the tech stack relevant to your position
2. **Choose the Level:** Pick Junior, Mid, or Senior based on the role
3. **Assign the Task:** Use the suggested assignments or create similar ones
4. **Evaluate:** Use the evaluation criteria and scoring guidelines
5. **Interview:** Ask level-appropriate questions about their solution
6. **Score:** Use the scoring matrix to make a decision

### Tips for Success

- Tailor assignments to your specific needs
- Allow candidates to ask clarifying questions
- Focus on code quality over feature completeness
- Consider partial credit for good attempts
- Provide feedback to candidates

---

## Contributing

Feel free to contribute additional:
- Technology stacks
- Assignment ideas
- Evaluation criteria
- Interview questions

---

## License

This evaluation guide is open source and can be freely used and modified for hiring purposes.