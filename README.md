🎭 Playwright test project

Installation
Playwright has its own test runner for end-to-end tests, we call it Playwright Test.

Using init command
The easiest way to get started with Playwright Test is to run the init command.

# Run from your project's root directory
npm init playwright@latest
# Or create a new project
npm init playwright@latest new-project
This will create a configuration file, optionally add examples, a GitHub Action workflow and a first test example.spec.ts. You can now jump directly to writing assertions section.

Manually
Add dependency and install browsers.

npm i -D @playwright/test
# install supported browsers
npx playwright install
