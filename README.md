# Playwright examples

Practice suite for core Playwright interactions, with Allure reporting.

Tests run against public demo apps: [UI Testing Playground](http://uitestingplayground.com/), [The Internet](https://the-internet.herokuapp.com/), jQuery UI demos and playwright.dev.

## What's covered

| Spec | Scenario |
|---|---|
| `lesson2_click.spec.js` | Button click with class change; checkbox and radio selection |
| `lesson2_checkbox.spec.js` | Checking and unchecking checkboxes |
| `lesson2_fill.spec.js` | Filling a login form and submitting it |
| `lesson2_hover.spec.js` | Hover reveals an image caption |
| `lesson2_press.spec.js` | Keyboard input updates a button label |
| `lesson2_screenshot.spec.js` | Page and element screenshots |
| `example.spec.js` | Title and navigation smoke checks |

Tests are annotated with Allure metadata: epic, feature, story, severity, tags and steps.

## Stack

Playwright Test · JavaScript · Allure (`allure-playwright`) · Chromium

## Run

```bash
npm install
npx playwright install chromium

npm test              # run all tests
npm run test:allure   # run, generate and open the Allure report
```
