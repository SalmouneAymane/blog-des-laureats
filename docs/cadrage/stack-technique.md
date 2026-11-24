# Technical Stack & Tooling — Laureates Blog

**Project:** Laureates Blog (web and mobile article-reading application)  
**Methodology:** Agile/Scrum and TDD

## 1. Technical Requirements

- Fast-loading article lists and laureate profiles.
- Clear separation of UI, business logic, and data access.
- Protection against SQL injection, XSS, and CSRF.
- Secure author and administrator authentication.
- Responsive desktop, tablet, and mobile interface.
- Native Android access limited to reading articles.

## 2. Backend

### Laravel

Laravel with PHP is justified by the following needs of the project:

- Its MVC architecture separates presentation, application logic, and data access.
- Eloquent ORM simplifies management of the laureates, articles, categories, and users.
- Blade provides reusable server-rendered layouts for the web interface.
- Middleware centralizes administrator and author authorization.
- Built-in validation and protections against CSRF, XSS, and SQL injection address the application security requirements.
- It can be reused by the web application and the native mobile build.

### MySQL

MySQL is justified for this application because it is a suitable relational database for structured data:

- Foreign keys preserve integrity between users, articles, categories, and laureates.
- ACID transactions protect operations that modify the database.
- Its integration with Laravel and Eloquent is mature and straightforward.
- It supports both local Windows development and a production deployment.

## 3. Frontend

### Tailwind CSS

- Tailwind CSS is justified by the need for a fast, consistent, and responsive interface.
- Its utility classes reduce custom CSS while keeping the component appearance consistent.
- Responsive breakpoints support desktop, tablet, and mobile layouts.
- Vite removes unused CSS during production builds.

### Preline UI

- Preline UI is justified because it provides ready-to-use Tailwind components such as cards, menus, dialogs, and forms.
- It accelerates interface development without introducing a complex frontend framework.
- It is compatible with Tailwind CSS and Blade's server-rendered structure.

### Alpine.js

- Alpine.js is justified by the application's need for lightweight interactions.
- It handles menus, filters, modals, and notifications without a complete SPA.
- It keeps JavaScript complexity low compared with React or Vue.
- It integrates directly with Blade-rendered pages.

## 4. Mobile Development

### NativePHP

NativePHP is justified because the project only requires a native Android version for reading articles:

- It packages Laravel and PHP as an Android application without requiring a separate web server.
- It reuses the existing models, controllers, routes, Blade views, and Tailwind styles.
- It maintains one codebase for web and mobile instead of synchronizing two separate applications.
- It limits additional development to the required article browsing and reading features.

| Criterion | NativePHP | API + Flutter/React Native |
|---|---|---|
| Codebase | One | Two |
| Development | Fast | Slower |
| Maintenance | Centralized | Synchronization required |
| Fit | Optimal for reading | Oversized for this scope |

## 5. Quality and AI Tooling

### Automated Testing

- Automated testing is justified by the project's TDD methodology and the need to prevent regressions.
- PHPUnit or Pest supports the Red-Green-Refactor cycle in the Laravel ecosystem.
- Unit and feature tests verify article creation, display, filtering, and access rules.
- Tests are executed before integration and deployment.

### AI Assistance

**GitHub Copilot**

- GitHub Copilot is justified because it is integrated with the development environment and supports the project's main technologies.
- It assists with PHP/Laravel code, migrations, factories, validation, and tests.
- It reduces repetitive boilerplate while the developer remains responsible for reviewing each proposal.

**Antigravity**

- Antigravity is justified for coordinating multi-file work across the project.
- It helps generate documentation and keep models, controllers, views, routes, and tests aligned.
- It assists with repetitive terminal tasks and verification against the specifications.
