# AQA J3 Study Plan: Nov 5 - Nov 30, 2026 (~3h/day)

Daily format (3h): Theory 1h | Coding 1h 45m | Recall quiz 15m (yesterday's topics + weak spots).
Rest days (Sundays) are light: 60-90 min, quiz and review only.
Starting point (diagnosed Nov 4): Programming Language (JS) = None / early Novice. Other categories not diagnosed yet.
Re-plan whenever a day is missed: move the missed topic to the next day and drop the lowest-priority item.

## Week 1 (Nov 5-8): JavaScript foundations
- Thu Nov 5: var/let/const, scope, data types, operators, loops, conditionals. Code: 10 tiny functions in Node. (Install Node, run `node file.js`.)
- Fri Nov 6: Functions and arrow functions, arrays, map/filter/reduce, destructuring, spread, objects, Set/Map. Code: array and string tasks.
- Sat Nov 7: Promises (3 states), then/catch, callbacks vs promises, event loop order (sync, microtask, timer). Code: write and chain 3 promises.
- Sun Nov 8: LIGHT. Re-do Thursday-Saturday exercises, 15-min quiz.

## Week 2 (Nov 9-15): Async JS, classes, Playwright core
- Mon Nov 9: async/await, forgotten await, try/catch/finally, classes (constructor, inheritance, encapsulation, #private), modules (import/export). Code: LoginPage-style class.
- Tue Nov 10: `npm init playwright@latest`, first test, locators (getByRole, getByTestId, getByText, CSS), actions, assertions (expect, web-first). Code: 3 tests on a demo site.
- Wed Nov 11: Auto-wait, actionability, expect polling, why sleep is bad, waitForResponse/waitForURL, flaky causes. Code: fix a flaky test.
- Thu Nov 12: Page Object Model, hooks (beforeAll/beforeEach/afterEach), tags/grep, test.skip/only, config (projects, multi-browser, retries, reporter, workers).
- Fri Nov 13: BrowserContext (isolation vs browser), storageState login, fixtures, headed/headless/debug, trace viewer.
- Sat Nov 14: API testing with Playwright `request` (GET/POST, status, body, headers, Bearer token), schema validation basics, mocking with `page.route`.
- Sun Nov 15: LIGHT. Write one small framework (POM + fixture + API test) from memory, or review it.

## Week 3 (Nov 16-22): Intermediate theory categories (diagnose each, teach gaps)
- Mon Nov 16: Automation Fundamentals (pyramid, inverted pyramid, flaky, ROI) + Automation Tools (Selenium vs Playwright vs Cypress).
- Tue Nov 17: Locators (XPath axes, contains/starts-with, shadow DOM, DevTools) + Waits theory (implicit/explicit/fluent) + Browser and Execution Context.
- Wed Nov 18: Test Design Techniques (EP, BVA, decision table, pairwise, state transition, risk-based) + SDLC and Methodologies (Scrum/Kanban, ATDD, shift-left, SAFe, CI/CD test strategy).
- Thu Nov 19: Test Management and Defect Tracking (Jira, Xray/Zephyr, TMS vs BTS, REST API) + Estimations and Planning (story points, automation estimate, ROI formula).
- Fri Nov 20: Software Engineering Practices (OOP, SOLID with automation examples, DRY/KISS, code review, ESLint) + Design Patterns (POM, Factory, Singleton, Builder, Facade).
- Sat Nov 21: API Test Automation theory (REST, status codes, idempotency, auth, GraphQL, CORS, contract testing, mock vs stub vs virtualization) + TypeScript basics (types, interfaces, generics).
- Sun Nov 22: LIGHT. Quiz on all Intermediate categories, update progress.md.

## Week 4 (Nov 23-30): Novice blocks, then mocks
- Mon Nov 23: Novice block 1 (definitions + one example each): Git, CI/CD (GitHub Actions), Docker, npm/package.json/lock file, Parallel Execution (workers, sharding).
- Tue Nov 24: Novice block 2: BDD/TDD/Gherkin, Auth (OAuth 2.0, JWT, OIDC), Test Data (Faker, isolation), Loggers/Reporters (Allure, screenshots), Data Structures (Big-O basics, array vs set).
- Wed Nov 25: Novice block 3: TestOps, Cloud platforms, Mobile (Appium), Performance (JMeter/k6, VU, RPS), SQL basics, AI-assisted testing, Security (SAST/DAST, OWASP).
- Thu Nov 26: Weak-spot repair from progress.md + live-coding mock (JS and Playwright, 60 min).
- Fri Nov 27: FULL MOCK 1 (all categories, matrix result table).
- Sat Nov 28: Repair the top 5 fixes from Mock 1, plus a second live-coding set.
- Sun Nov 29: LIGHT. Calm session, review cheat sheet, early night.
- Mon Nov 30: FULL MOCK 2 (shorter, Intermediate categories first), final verdict and last tips.

## Priority reminder
Intermediate categories (12) come first, and JavaScript plus Playwright get the most hours. Novice topics: know the definition plus one example, and do not go deep.
