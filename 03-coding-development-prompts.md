# 💻 Coding & Development Prompts (30 Prompts)

---

## Debugging & Problem Solving

### 1. Universal Debugger
```
I have a bug in my [LANGUAGE] code. Help me fix it.

Code:
[PASTE CODE]

Expected behavior: [WHAT IT SHOULD DO]
Actual behavior: [WHAT IT DOES INSTEAD]
Error message (if any): [PASTE ERROR]
Environment: [OS, LANGUAGE VERSION, FRAMEWORK]

Please:
1. Identify the root cause
2. Explain WHY it's broken (not just how to fix it)
3. Provide the corrected code
4. Suggest how to prevent this type of bug in the future
5. Add relevant error handling if missing
```

### 2. Performance Optimizer
```
Optimize this code for performance:

[PASTE CODE]

Language: [LANGUAGE]
Current performance issue: [SLOW/MEMORY/CPU]
Scale: [DATA SIZE/REQUEST VOLUME]
Constraints: [ANY LIMITATIONS]

Please:
1. Profile the bottlenecks (explain what's slow and why)
2. Provide optimized version
3. Explain each optimization with Big O analysis
4. Benchmark comparison (estimated before/after)
5. Trade-offs of the optimization (readability, memory, etc.)
```

### 3. Error Message Decoder
```
I'm getting this error and I don't understand it:

[PASTE FULL ERROR MESSAGE/STACK TRACE]

Context:
- Language/Framework: [WHAT]
- What I was doing: [ACTION]
- What I've tried: [ATTEMPTS]

Please:
1. Explain the error in plain English
2. Identify the most likely cause
3. Provide step-by-step fix
4. Show how to add proper error handling for this case
5. List related errors I might encounter
```

## Code Generation

### 4. API Endpoint Builder
```
Create a REST API endpoint for [FUNCTIONALITY].

Stack: [LANGUAGE + FRAMEWORK]
Database: [DB TYPE]
Auth: [AUTH METHOD]

Endpoint details:
- Method: [GET/POST/PUT/DELETE]
- Path: [/api/v1/...]
- Request body/params: [DESCRIBE]
- Response format: [DESCRIBE]
- Error cases: [LIST]

Include:
1. Route handler with input validation
2. Database query/operation
3. Error handling with proper HTTP status codes
4. Authentication/authorization middleware
5. Rate limiting suggestion
6. Unit test for the endpoint
7. OpenAPI/Swagger documentation
```

### 5. Database Schema Designer
```
Design a database schema for [APPLICATION].

Database type: [PostgreSQL/MySQL/MongoDB/etc.]
Main entities: [LIST ENTITIES]
Relationships: [DESCRIBE]
Expected scale: [USERS/DATA VOLUME]

Provide:
1. Table/collection definitions with data types
2. Primary and foreign keys
3. Indexes (with justification)
4. Constraints and validations
5. Migration script
6. Sample queries for common operations
7. Scaling considerations
```

### 6. Authentication System
```
Implement authentication for [APPLICATION TYPE].

Stack: [FRAMEWORK]
Auth method: [JWT/SESSION/OAUTH/PASSKEYS]
Providers: [EMAIL, GOOGLE, GITHUB, etc.]

Build:
1. Registration flow with email verification
2. Login with password hashing
3. Token generation and refresh
4. Protected route middleware
5. Password reset flow
6. Rate limiting on auth endpoints
7. Security headers and CSRF protection

Include security best practices comments throughout.
```

### 7. CRUD Generator
```
Generate a complete CRUD module for [ENTITY].

Stack: [LANGUAGE + FRAMEWORK + ORM]
Entity: [NAME]
Fields: [LIST WITH TYPES]
Relations: [ANY RELATED ENTITIES]

Generate:
1. Model/Schema definition
2. Create operation (with validation)
3. Read (single + list with pagination, filtering, sorting)
4. Update (partial update support)
5. Delete (soft delete option)
6. Service layer (business logic)
7. Controller/Route handlers
8. Unit tests for each operation
9. API documentation
```

### 8. CLI Tool Builder
```
Build a CLI tool in [LANGUAGE] that [FUNCTIONALITY].

Tool name: [NAME]
Commands: [LIST]
Options/flags: [LIST]

Requirements:
1. Argument parsing with help text
2. Colored output
3. Progress indicators for long operations
4. Configuration file support
5. Error handling with helpful messages
6. Interactive mode where appropriate
7. Man page or --help documentation

Example usage:
[SHOW EXPECTED CLI USAGE]
```

## Code Review & Refactoring

### 9. Code Reviewer
```
Review this code as a senior developer:

[PASTE CODE]

Language: [LANGUAGE]
Context: [WHAT THE CODE DOES]
Team level: [JUNIOR/MID/SENIOR]

Review for:
1. Bugs and potential issues
2. Security vulnerabilities
3. Performance concerns
4. Code style and consistency
5. SOLID principles adherence
6. Error handling completeness
7. Test coverage gaps
8. Documentation needs

For each issue found:
- Severity: Critical / Major / Minor / Suggestion
- Line reference
- Explanation
- Suggested fix
```

### 10. Refactoring Guide
```
Refactor this code following clean code principles:

[PASTE CODE]

Language: [LANGUAGE]
Pain points: [WHAT'S WRONG WITH IT]
Constraints: [BACKWARDS COMPATIBILITY, etc.]

Refactoring goals:
1. Improve readability
2. Reduce complexity (cyclomatic complexity target: < 10)
3. Extract reusable functions
4. Add proper types/interfaces
5. Follow [DESIGN PATTERN] if applicable
6. Improve naming (variables, functions, classes)

Provide:
- Refactored code
- Explanation of each change
- Before/after complexity comparison
- Migration guide if API changes
```

### 11. Legacy Code Modernizer
```
Modernize this legacy code:

[PASTE CODE]

From: [OLD FRAMEWORK/PATTERN]
To: [MODERN FRAMEWORK/PATTERN]
Language: [LANGUAGE + VERSION]

Steps:
1. Identify deprecated patterns
2. Replace with modern equivalents
3. Add TypeScript types (if JS)
4. Convert callbacks to async/await
5. Use modern APIs and syntax
6. Add error boundaries
7. Include migration notes for the team
```

## Architecture & Design

### 12. System Design Prompt
```
Design a system for [APPLICATION].

Requirements:
- Users: [EXPECTED SCALE]
- Features: [LIST MAIN FEATURES]
- Performance: [LATENCY/THROUGHPUT REQUIREMENTS]
- Budget: [STARTUP/ENTERPRISE]

Provide:
1. High-level architecture diagram (describe components)
2. Technology stack recommendations with justification
3. Database design (SQL vs NoSQL decision)
4. API design (REST vs GraphQL)
5. Caching strategy
6. Message queue needs
7. Deployment architecture (cloud services)
8. Scaling strategy (horizontal vs vertical)
9. Monitoring and observability plan
10. Cost estimate (monthly)
```

### 13. Microservices Decomposition
```
Decompose this monolithic application into microservices:

[DESCRIBE THE MONOLITH]

Current pain points: [LIST]
Team size: [NUMBER]
Deployment frequency: [CURRENT]

Provide:
1. Service boundaries (bounded contexts)
2. API contracts between services
3. Data ownership per service
4. Communication patterns (sync vs async)
5. Shared infrastructure needs
6. Migration strategy (strangler fig pattern)
7. Testing strategy for distributed system
```

### 14. Design Pattern Advisor
```
I'm building [FEATURE] and I'm not sure which design pattern to use.

Context:
- Language: [LANGUAGE]
- Problem: [DESCRIBE THE CHALLENGE]
- Current approach: [WHAT I'M DOING NOW]
- Scale: [EXPECTED GROWTH]

Please:
1. Recommend the most appropriate design pattern(s)
2. Explain why this pattern fits my case
3. Show implementation with my specific code
4. Discuss trade-offs vs alternative patterns
5. Common mistakes when implementing this pattern
```

## Testing

### 15. Unit Test Generator
```
Write comprehensive unit tests for this code:

[PASTE CODE]

Language: [LANGUAGE]
Test framework: [JEST/PYTEST/JUNIT/etc.]

Test cases to cover:
1. Happy path (normal operation)
2. Edge cases (empty input, null, boundary values)
3. Error cases (invalid input, exceptions)
4. Integration points (mocked dependencies)

For each test:
- Descriptive test name (should read like documentation)
- Arrange-Act-Assert pattern
- Clear assertions with good error messages
- Mock setup where needed

Also provide:
- Test file organization
- Coverage report expectations
- CI/CD integration snippet
```

### 16. E2E Test Scenarios
```
Write end-to-end test scenarios for [FEATURE].

Application type: [WEB/MOBILE/API]
Test framework: [CYPRESS/PLAYWRIGHT/SELENIUM]
User journey: [DESCRIBE THE FLOW]

Scenarios:
1. Happy path (complete user journey)
2. Validation errors (form submissions)
3. Network failures (offline, slow connection)
4. Authentication edge cases
5. Cross-browser considerations

For each scenario:
- Given/When/Then format
- Test code implementation
- Setup/teardown needs
- Assertions to verify
```

## DevOps & Infrastructure

### 17. Docker Configuration
```
Create Docker configuration for [APPLICATION].

Stack: [LIST ALL SERVICES]
Development needs: [HOT RELOAD, DEBUG, etc.]
Production needs: [PERFORMANCE, SECURITY]

Provide:
1. Dockerfile (multi-stage, production-optimized)
2. docker-compose.yml (development)
3. docker-compose.prod.yml (production)
4. .dockerignore
5. Health check configuration
6. Volume mounts for development
7. Network configuration
8. Environment variable handling
9. Image size optimization tips
```

### 18. CI/CD Pipeline
```
Create a CI/CD pipeline for [PROJECT].

Platform: [GITHUB ACTIONS/GITLAB CI/JENKINS]
Language: [LANGUAGE]
Deploy target: [AWS/GCP/VERCEL/etc.]

Pipeline stages:
1. Lint and format check
2. Unit tests with coverage
3. Integration tests
4. Security scanning (dependencies + SAST)
5. Build
6. Deploy to staging
7. Smoke tests on staging
8. Deploy to production
9. Post-deploy verification

Include:
- Branch protection rules
- Environment secrets management
- Rollback strategy
- Notification setup
```

### 19. Infrastructure as Code
```
Write IaC for deploying [APPLICATION] to [CLOUD PROVIDER].

Tool: [TERRAFORM/PULUMI/CDK]
Services needed: [LIST]
Budget: [MONTHLY LIMIT]
Region: [WHERE]

Provide:
1. Compute resources (right-sized)
2. Database setup (with backups)
3. Networking (VPC, security groups)
4. CDN and DNS
5. Monitoring and alerts
6. Auto-scaling rules
7. Cost estimation
8. Security best practices
```

## Documentation

### 20. API Documentation
```
Write comprehensive API documentation for these endpoints:

[PASTE API ROUTES OR OPENAPI SPEC]

Format: [OPENAPI 3.0/MARKDOWN/SLATE]

For each endpoint include:
1. Description and use case
2. Authentication requirements
3. Request format (with example)
4. Response format (with example)
5. Error responses (all possible codes)
6. Rate limiting info
7. Code examples (curl, JavaScript, Python)
8. Changelog/versioning notes
```

### 21. README Generator
```
Write a comprehensive README.md for [PROJECT].

Project: [NAME]
Type: [LIBRARY/APP/CLI/API]
Language: [LANGUAGE]
Purpose: [WHAT IT DOES]

Sections:
1. Project name + badges (build, coverage, npm/pypi)
2. One-line description
3. Demo GIF/screenshot placeholder
4. Features list
5. Quick start (install + first use in < 2 minutes)
6. Full documentation link
7. Configuration options
8. Examples (3-5 common use cases)
9. API reference
10. Contributing guide
11. License
12. Acknowledgments

Tone: Welcoming, clear, no jargon without explanation.
```

### 22. Code Comment Writer
```
Add comprehensive comments to this code:

[PASTE CODE]

Language: [LANGUAGE]
Audience: [JUNIOR DEVS/TEAM/OPEN SOURCE]

Comment types to add:
1. File header (purpose, author, date)
2. Function/method docstrings (params, returns, throws, examples)
3. Complex logic explanations (WHY, not WHAT)
4. TODO/FIXME for known issues
5. Section dividers for long files

Do NOT comment obvious code. Focus on business logic reasoning and non-obvious decisions.
```

## Frontend

### 23. React Component Builder
```
Build a React component for [FEATURE].

Component: [NAME]
Type: [FUNCTIONAL/CLASS]
Styling: [CSS MODULES/TAILWIND/STYLED-COMPONENTS]
State management: [HOOKS/REDUX/ZUSTAND]

Requirements:
- Props interface (TypeScript)
- Responsive design (mobile-first)
- Accessibility (ARIA attributes, keyboard nav)
- Loading and error states
- Animation/transitions
- Unit tests
- Storybook story

Include performance optimizations (memo, useMemo, useCallback where appropriate).
```

### 24. CSS/Tailwind Layout Solver
```
I need help creating this layout:

[DESCRIBE OR SKETCH THE LAYOUT]

Approach: [CSS GRID/FLEXBOX/TAILWIND]
Responsive breakpoints: [MOBILE/TABLET/DESKTOP]
Browser support: [MODERN ONLY/LEGACY]

Provide:
1. HTML structure
2. CSS/Tailwind classes
3. Responsive behavior at each breakpoint
4. Edge cases (content overflow, long text, etc.)
5. Accessibility considerations
```

## Security

### 25. Security Audit Prompt
```
Perform a security audit on this code:

[PASTE CODE]

Language: [LANGUAGE]
Type: [WEB APP/API/MOBILE]

Check for:
1. Injection vulnerabilities (SQL, XSS, CSRF)
2. Authentication weaknesses
3. Authorization bypass risks
4. Sensitive data exposure
5. Insecure dependencies
6. Cryptographic issues
7. Error handling (information leakage)
8. Input validation gaps

For each finding:
- OWASP category
- Severity (Critical/High/Medium/Low)
- Proof of concept (how to exploit)
- Remediation code
```

### 26. Secure Code Template
```
Write secure code for [FUNCTIONALITY].

Language: [LANGUAGE]
Security requirements: [LIST ANY SPECIFIC]

Include:
1. Input sanitization and validation
2. Parameterized queries (no string concatenation)
3. Proper error handling (no stack traces to users)
4. Authentication checks
5. Rate limiting
6. Logging (without sensitive data)
7. CORS configuration
8. Security headers

Follow OWASP Top 10 guidelines. Comment each security measure.
```

## Data & Integration

### 27. Web Scraper Builder
```
Build a web scraper for [WEBSITE/DATA].

Language: [PYTHON/NODE.JS]
Target: [URL]
Data to extract: [LIST FIELDS]
Output format: [JSON/CSV/DATABASE]

Include:
1. Request handling with proper headers
2. Rate limiting (respectful scraping)
3. Error handling and retries
4. Data parsing and cleaning
5. robots.txt compliance check
6. Pagination handling
7. Anti-detection measures (user agent rotation)
8. Data validation
9. Storage/export

Ethical considerations: Check terms of service, respect rate limits, only scrape public data.
```

### 28. Data Pipeline Builder
```
Design a data pipeline for [USE CASE].

Source: [WHERE DATA COMES FROM]
Transformations: [WHAT NEEDS TO HAPPEN]
Destination: [WHERE DATA GOES]
Frequency: [REAL-TIME/HOURLY/DAILY]
Volume: [DATA SIZE]

Provide:
1. Architecture diagram (describe)
2. ETL/ELT code
3. Data validation rules
4. Error handling and dead letter queue
5. Monitoring and alerting
6. Backfill strategy
7. Testing approach
```

### 29. Regex Generator
```
Write a regex pattern for [REQUIREMENT].

What to match: [DESCRIBE PATTERN]
Language: [LANGUAGE - regex flavors differ]
Examples that should match: [LIST]
Examples that should NOT match: [LIST]

Provide:
1. Regex pattern
2. Explanation of each part
3. Test cases (match and no-match)
4. Edge cases considered
5. Performance notes (backtracking risks)
6. Alternative approach if regex is too complex
```

### 30. Migration Script Writer
```
Write a data migration script for [MIGRATION].

From: [SOURCE - old schema/system]
To: [DESTINATION - new schema/system]
Data volume: [ROWS/SIZE]
Downtime budget: [ZERO/MINUTES/HOURS]

Include:
1. Pre-migration validation
2. Backup procedure
3. Migration script (batched for large data)
4. Data transformation logic
5. Rollback script
6. Post-migration verification
7. Performance estimates
8. Runbook for the migration team
```
