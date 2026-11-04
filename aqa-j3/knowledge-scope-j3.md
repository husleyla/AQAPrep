# Andersen AQA J3 - Knowledge Scope (source: matrix, J3 column)


## SDLC & Testing Methodologies - J3 REQUIRED: Intermediate
Topics: Agile, Scrum, Kanban, SAFe, TDD, BDD, ATDD, shift-left

**Novice:**
• Name main SDLC models (Waterfall, Agile, Scrum, Kanban)
• Explain difference between Scrum and Kanban
• Understand TDD and BDD conceptually
• Know where testing fits in a sprint
• Know what shift-left means

**Intermediate:**
• Hands-on Agile experience: sprint ceremonies, Definition of Done, backlog refinement
• Explain shift-left testing and its impact on automation
• Describe ATDD (Acceptance Test-Driven Development) and its relation to test automation
• SAFe awareness — PI planning, automation in scaled teams
• Describe testing strategy for CI/CD continuous delivery
• Map automation types to SDLC phases: 
  when unit, API, UI, and performance tests run in delivery cycle

**Advanced:**
• Design testing processes adapted to methodology
• Adapt automation strategy to trunk-based development, feature flags, canary releases
• Describe dual-track agile, continuous testing in prod
• Coach team on integrating QA into Agile at scale
• Evaluate methodology fit for project complexity


## Estimations & Planning - J3 REQUIRED: Intermediate
Topics: Story points, planning poker, T-shirt sizing, automation ROI(Return on Investment)

**Novice:**
• Estimate own tasks for well-defined features
• Participate in planning poker
• Understand story points vs time estimates
• Know what automation ROI means conceptually

**Intermediate:**
• Independently estimate full automation tracks including setup and maintenance overhead
• Identify risk factors and communicate assumptions clearly
• Break down complex automation stories into subtasks
• Calculate basic automation ROI (time saved vs investment)

**Advanced:**
• Lead estimation for automation subsystems or full projects
• Build contingency into plans, manage uncertainty
• Present automation business case to stakeholders
• Forecast maintenance cost of test suite over time


## Test Management & Defect Tracking Ecosystem - J3 REQUIRED: Intermediate
Topics: Jira, TestRail, Xray, Zephyr, TMS/BTS API integration, dashboards

**Novice:**
• Create and manage test cases and bug reports in Jira/TestRail
• Understand severity vs priority
• Know difference between TMS (test management) and BTS (bug tracking)
• Link automated test results to test cases manually

**Intermediate:**
• Configure Xray or Zephyr to receive automated test results from API
• Use Jira REST API for basic operations (create issue, update fields, add comment)
• Build queries, boards, and dashboards in Jira
• Understand test execution cycles and test plans in TMS
• Integrate Allure or Report Portal with TMS automatically

**Advanced:**
• Design end-to-end integration: CI pipeline → test runner → TMS → auto-create BTS issue
• Evaluate and select TMS/BTS toolchain for project needs
• Automate defect creation and linking from failed tests via API
• Build custom dashboards and quality gates in reporting tools
• Define and track quality KPIs across delivery pipeline


## Test Design Techniques - J3 REQUIRED: Intermediate
Topics: Equivalence partitioning, boundary value, pairwise, decision table, risk-based

**Novice:**
• Know equivalence partitioning and boundary value analysis
• Apply checklists and basic test cases
• Distinguish positive vs negative test scenarios
• Understand what risk-based testing means

**Intermediate:**
• Apply decision table and pairwise testing techniques
• Design test cases from requirements and user stories
• Use risk-based approach to prioritize what to automate
• Know state transition diagrams and apply them
• Design data sets for data-driven automation

**Advanced:**
• Apply advanced combinatorial techniques (pairwise, orthogonal arrays) for complex parameter spaces
• Design comprehensive data-driven test strategies
• Evaluate coverage completeness against requirements
• Adapt technique selection to project risk profile
• Guide team on test design quality and coverage
• Apply mutation testing (Stryker, PITest) to measure test suite effectiveness
• Define parameterization strategy for large data-driven automation suites


## Software Engineering Practices - J3 REQUIRED: Intermediate
Topics: OOP, SOLID, DRY, KISS; code review; clean code principles

**Novice:**
• Understand OOP principles (encapsulation, inheritance, polymorphism, abstraction)
• Know SOLID principles conceptually and name them
• Follow code style guide
• Participate constructively in code review

**Intermediate:**
• Apply SOLID in automation framework design (explain with examples)
• Refactor duplicated test code using appropriate patterns
• Use static analysis tools (SonarQube, ESLint, Checkstyle)
• Write self-documenting tests (naming, structure, assertions)
• Conduct meaningful code reviews with actionable feedback

**Advanced:**
• Design maintainable, extensible automation architecture applying SOLID
• Enforce engineering standards across the team
• Introduce and justify architectural decisions with trade-off analysis
• Measure and improve code quality metrics (coverage, duplication, complexity)
• Mentor team members on clean code and engineering excellence


## Programming Language - J3 REQUIRED: Intermediate
Topics: TypeScript / JavaScript / Java / C# / Python

**Novice:**
• Data types, variables, operators, loops, conditionals
• Basic OOP: class, object, inheritance, encapsulation
• Exception handling basics (try/catch/finally)
• Collections: list, map/dict, set — usage and iteration
• Read and understand existing test code written by others

**Intermediate:**
• Generics / type hints and their value in test code
• Lambda expressions and functional style (map, filter, reduce)
• Async/await and Promises (JS/TS) or threading basics (Java/Python/C#)
• Access modifiers and encapsulation in framework design
• Write clean, independently maintainable automation code

**Advanced:**
• Advanced language features: decorators/attributes, reflection, metaclasses
• Memory management and GC awareness — impact on long test runs
• Concurrency and thread safety patterns in test infrastructure
• Module system, dependency injection in test framework context
• Optimize and profile test code performance at scale


## Design Patterns for Test Automation - J3 REQUIRED: Novice
Topics: Singleton, Factory, Page Object, Builder, Decorator, Strategy, Facade

**Novice:**
• Know what a design pattern is and why patterns exist
• Understand Singleton and its use for WebDriver initialization
• Know Factory Method conceptually
• Know Page Object pattern and implement it
• Know what an anti-pattern is and name one example 
  (e.g., hardcoded selectors, God Page Object)


## Data Structures & Algorithms - J3 REQUIRED: Novice
Topics: Arrays, maps, sets, sorting; choosing appropriate structures for test data

**Novice:**
• Know basic structures: array, list, dictionary/map, set
• Iterate, filter, and sort collections in chosen language
• Understand O(n) vs O(n²) in simple terms — 'nested loops over large data = slow'
• Choose between list and set for test data deduplication


## Automation Testing Fundamentals - J3 REQUIRED: Intermediate
Topics: Test pyramid, when to automate, ROI of automation, flaky test management

**Novice:**
• Explain what test automation is and why it's needed
• Describe the classic test pyramid (unit → integration → UI)
• Know when automation is NOT applicable
• List types: regression, smoke, sanity, E2E
• Understand what a flaky test is

**Intermediate:**
• Explain inverted pyramid and its trade-offs
• Describe automation strategy for frontend vs backend project
• Flaky tests: understand causes (timing, data, env) and mitigation strategies
• Calculate basic automation ROI
• Know the scope of functional vs non-functional automation

**Advanced:**
• Design automation strategy from scratch for a complex distributed system
• Define automation coverage targets, KPIs, and quality gates
• Evaluate automation feasibility across project types (legacy, microservices, mobile)
• Guide team on automation prioritization and phased rollout
• Architect multi-layer automation strategy aligned with delivery pipeline


## Automation Tools & Frameworks - J3 REQUIRED: Intermediate
Topics: (Selenium, Playwright, Cypress, WebdriverIO); choosing the right tool

**Novice:**
• Explain what a test framework is and what it provides
• Know the tool they've worked with (structure, hooks, runners)
• Have heard of Selenium and Playwright
• Know how to run/skip a specific test
• Know how to run tests by tag or group

**Intermediate:**
• Criteria for choosing a framework for a project
• Compare Selenium vs Playwright vs Cypress — trade-offs
• Configure hooks (before/after all, before/after each)
• Configure parallel execution in the framework
• Plug in a reporter to the framework
• Integrate framework with CI tool

**Advanced:**
• Evaluate and select full automation stack for a new project
• Extend framework capabilities with custom plugins or listeners
• Integrate framework with TMS (Xray, Zephyr, TestRail)
• Design multi-framework strategy (UI + API + mobile)
• Migrate test suite from one framework to another with minimal disruption


## Locators & Element Interaction - J3 REQUIRED: Intermediate
Topics: CSS, XPath, accessibility selectors; shadow DOM; dynamic elements

**Novice:**
• Differences between CSS and XPath selectors
• Find elements by ID, class, attribute, text
• Write basic CSS and XPath locators
• Know what querySelector is

**Intermediate:**
• Write complex XPath (axes, :not, not(contains()))
• Handle dynamic elements (partial match, contains, starts-with)
• Use accessibility selectors (aria-label, role, data-testid)
• Understand shadow DOM and how to pierce it
• Debug locator issues using browser DevTools

**Advanced:**
• Build parameterized composite locators
• Handle pseudo-elements (::before, ::after)
• Design locator strategy for an entire application (data-testid standards)
• Handle complex scenarios: canvas elements, SVG, iframe-nested shadows
• Audit and refactor brittle locator strategies in existing frameworks


## Waits & Synchronization - J3 REQUIRED: Intermediate
Topics: Implicit, explicit, fluent waits; polling strategies; avoiding flakiness

**Novice:**
• Know types of waits: implicit, explicit, Thread.sleep
• Understand why sleep is bad practice
• Know basic ExpectedConditions usage
• Know difference between implicit and explicit wait

**Intermediate:**
• Implement explicit wait with custom expected conditions
• Use fluent wait with polling interval and ignored exceptions
• Wait for AJAX requests and DOM tree loading via JSExecutor
• Diagnose and fix flakiness caused by synchronization issues
• Understand wait interaction conflicts (implicit + explicit)

**Advanced:**
• Implement custom ExpectedConditions for project-specific scenarios
• Design wait strategy for SPA frameworks (React, Angular, Vue)
• Handle race conditions in parallel test execution
• Build reusable wait utilities as part of framework core
• Profile and optimize test suite slow points caused by excessive waits


## Browser & Execution Context Management - J3 REQUIRED: Intermediate
Topics: Browser Context, Browser Profiles & State Management, Headless vs headed, Multi-browser strategy, Remote execution

**Novice:**
• Know what a browser engine is and name the main ones: Chromium/Blink, Gecko (Firefox), WebKit (Safari)
• Know how to launch a browser in Selenium (ChromeDriver, WebDriverManager) and in Playwright (chromium.launch())
• Understand what headless mode is and when it's used
• Know difference between headed and headless execution
• Have run tests locally in at least one browser

**Intermediate:**
• Configure browser options and capabilities in Selenium (ChromeOptions, FirefoxOptions: proxy, extensions, download directory, disable notifications)
• Understand Playwright's BrowserContext concept — what it is, how it differs from a plain browser instance, why it enables test isolation
• Use storageState in Playwright to persist authentication state across tests (avoid repeated login)
• Configure multi-browser execution — switch between Chromium, Firefox, WebKit in Playwright config
• Set up remote WebDriver for Selenium Grid or Selenoid
• Know how to debug flaky tests by switching from headless to headed mode
• Understand basic cross-browser differences that affect test stability (rendering, timing, CSS)

**Advanced:**
• Design browser initialization strategy for large-scale parallel execution — factory pattern, context isolation, thread-safe WebDriver management
• Implement browser-level proxy interception for request/response manipulation in tests (Playwright route(), Selenium proxy)
• Manage multiple BrowserContexts in parallel — isolate auth state, cookies, localStorage per test worker
• Design cross-browser test matrix strategy for CI: which browsers, which tests, which frequency — cost vs coverage trade-off
• Handle headless mode pitfalls in CI: viewport mismatches, missing fonts, video recording, GPU flags
• Configure and maintain Selenoid/Moon cluster or Selenium Grid for distributed execution
• Evaluate browser execution strategy for the project: local vs Grid vs Selenoid vs cloud (BrowserStack, LambdaTest) — based on scale, cost, and CI requirements


## BDD / TDD / DDT - J3 REQUIRED: Novice
Topics: Cucumber, Reqnroll; data-driven patterns; Gherkin syntax

**Novice:**
• Know what BDD is and why teams use it
• Understand Gherkin syntax: Feature, Scenario, Given/When/Then
• Know what TDD means conceptually
• Name popular BDD frameworks (Cucumber, Reqnroll)


## API Test Automation - J3 REQUIRED: Intermediate
Topics: REST, GraphQL, WebSocket; contract testing (Pact); schema validation

**Novice:**
• Know REST principles: HTTP methods, status codes, idempotency
• Send requests and inspect responses in Postman or curl
• Understand JSON structure and basic serialization
• Know difference between REST and SOAP
• Know what WebSocket is conceptually
• Know why mocks/service virtualization are used (isolating tests from unstable/unavailable dependencies)
• Set up a basic static mock response in WireMock/MSW from an example

**Intermediate:**
• Write automated API tests using RestAssured / Axios / Python requests
• Validate response body, headers, and JSON schema
• Handle authentication in API tests (API key, Bearer token)
• Test GraphQL queries and mutations
• Understand CORS and its impact on API testing
• Know what Contract Testing is and why it's needed
• Configure mocks for multiple scenarios (success/error/latency/edge cases)
• Know the difference between mock, stub, and service virtualization, and when to use each
• Integrate a mock server into the test pipeline (start/stop as part of test setup)

**Advanced:**
• Design API test framework with retry, auth handling, and reporting layers
• Implement Consumer-Driven Contract Testing with Pact
• Test gRPC services using proto stubs and gRPC testing tools
• Design API mock/stub strategy for isolated testing (WireMock, MockServer)
• Balance mock-based tests with contract testing to avoid false confidence from over-mocking
• Manage service virtualization for complex cases (stateful behavior, latency injection, dependency chaos testing)
• Test API security basics: OWASP API Top 10 awareness, rate limiting, injection


## Authorization & Authentication Testing - J3 REQUIRED: Novice
Topics: OAuth 2.0, JWT, SSO, API keys; token handling in automation

**Novice:**
• Know what OAuth 2.0 is and what problem it solves
• Know what JWT is: header, payload, signature structure
• Know what OpenID Connect (OIDC) adds on top of OAuth 2.0
• Know difference between authentication and authorization


## Parallel Execution & Scalability - J3 REQUIRED: Novice
Topics: Parallel config (TestNG/pytest-xdist/Playwright); thread safety; sharding; Selenium Grid

**Novice:**
• Know that parallel execution exists and understand its benefits
• Run basic parallel tests using framework configuration
• Understand what thread safety means conceptually


## Test Data Management - J3 REQUIRED: Novice
Topics: Data factories, fixtures, Faker; test data isolation; cleanup strategies; GDPR in test data

**Novice:**
• Understand why test data management matters
• Use config-file or hardcoded test data
• Know what data isolation means for parallel tests
• Use basic Faker library to generate test data


## Loggers, Reporters & Metrics - J3 REQUIRED: Novice
Topics: Allure, ExtentReports; screenshot/video on failure; test execution dashboards

**Novice:**
• Know why test reporting is needed
• Connect Allure reporter to test framework
• Read Allure/HTML reports and identify failures
• Attach screenshots on test failure


## Version Control System - J3 REQUIRED: Novice
Topics: Git: branching strategies, merge/rebase, PR workflows

**Novice:**
• Clone, commit, push, pull, branch, switch
• Know .gitignore and basic Git config
• Understand what a pull request is
• Know how to make a local branch remote


## CI/CD Pipelines - J3 REQUIRED: Novice
Topics: Jenkins, GitHub Actions, GitLab CI; pipeline configuration; test stage integration

**Novice:**
• Know what CI/CD is and why it matters
• Understand pipeline stages: build → test → report → deploy
• Have seen GitHub Actions or Jenkins in practice
• Know difference: Continuous Delivery vs Continuous Deployment


## Virtualization & Containerization - J3 REQUIRED: Novice
Topics: Docker, Docker Compose; Kubernetes basics; Selenoid/Moon

**Novice:**
• Know difference between virtualization and containerization
• Pull and run Docker containers
• Understand image vs container
• Know Docker Hub and public registries


## TestOps - J3 REQUIRED: Novice
Topics: Test infrastructure management; parallel execution; environment provisioning

**Novice:**
• Know what TestOps is and how it differs from DevOps
• Understand test environment provisioning at a conceptual level
• Know what synthetic monitoring means


## Cloud Testing Platforms - J3 REQUIRED: Novice
Topics: BrowserStack, Sauce Labs, AWS Device Farm, LambdaTest, real devices, cloud grid, cost model

**Novice:**
• Know that cloud testing platforms exist and their purpose
• Understand difference: emulator vs simulator vs real device
• Know popular platforms: BrowserStack, Sauce Labs, AWS Device Farm


## Package Management & Build Tools - J3 REQUIRED: Novice
Topics: npm/yarn, Maven/Gradle, pip; dependency management; reproducible builds

**Novice:**
• Know why package managers are needed
• Install dependencies: npm install, pip install, mvn install
• Understand package.json basics (scripts, dependencies)
• Know what a lock file is


## Mobile Automation - J3 REQUIRED: Novice
Topics: Appium, Detox, XCUITest/Espresso; mobile-specific locators and gestures

**Novice:**
• Know types of mobile apps: native, hybrid, web
• Know what Appium is and how it works
• Understand mobile locators: ID, Accessibility ID, XPath
• Know difference between Android and iOS automation approaches


## Performance Testing - J3 REQUIRED: Novice
Topics: JMeter, k6, Gatling; load/stress/spike scenarios; analyzing results

**Novice:**
• Know types of performance testing: load, stress, soak, spike
• Know goals of performance testing
• Name at least one tool: JMeter, k6, or Gatling
• Know what VUs (virtual users) and RPS mean


## Databases & Data Validation - J3 REQUIRED: Novice
Topics: SQL/NoSQL querying for test verification; data integrity checks; test data setup/teardown

**Novice:**
• Know types of databases: relational vs non-relational
• Write basic SELECT, INSERT, UPDATE, DELETE
• Know primary key, foreign key concepts
• Understand why DB validation matters in automation


## AI-Assisted Test Automation - J3 REQUIRED: Novice
Topics: AI-driven test generation, self-healing locators, visual AI testing (Applitools); prompt engineering for test code

**Novice:**
• Know AI tools exist for test generation: Copilot, ChatGPT
• Have used AI to help write or review a test
• Understand AI output requires human review
• Know that AI-generated tests/code must always be reviewed before merging, never trusted blindly
• Recognize hallucinated or meaningless AI output (fake APIs/selectors, weak or missing assertions)


## Security Automation Awareness - J3 REQUIRED: Novice
Topics: SAST, DAST, OWASP ZAP, SonarQube, OWASP API Top 10, CVE scanning, secret scanning, SBOM

**Novice:**
• Know what SAST and DAST mean and name one tool for each (SonarQube, OWASP ZAP)
• Understand OWASP API Top 10 at a conceptual level
• Know what dependency CVE scanning is and why it matters
• Know what secret scanning in git pipelines means
