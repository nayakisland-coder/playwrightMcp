# Instructions and Notes

## In this session.............
1. Install playwright
- `npm init playwright@latest`
2. Check if installed correctly
- `npx playwright --help`

## Key Callouts
- [Q1] will i get these commands in `Resources` section
 - [Ans] Yes, will attach then in `Resources` section
 - [Q1] What if the commands shown in the file changed?
 - [Ans] ALWAYS check and refer for `Resources` section

**Windows**
- For running webkit in Windows, add these in `use` object
```ts
use:  {
  ignoreHTTPSErrors: true,
}
```

## Recommended VS Code Extensions**
- vscode-icons
- Pretties- Code Formatter
- Path Intellisence
- npm intellisense
- DotENV
- JaveScript (Es6) code snippets
- .gitignore Generator


**##Next Additiona information --**



#####👌👌👌👌👌👌👌👌
// In order to see this method in a dropdown option then press  cntr+Space in Playwright.config.js

 🧱 What does a README.md usually contain?
Most projects include:
✔ Project Title
✔ Description
✔ Installation steps
✔ How to run the project
✔ Folder structure
✔ Commands
✔ Examples / screenshots
✔ Author info
For example, a simple README for your Playwright MCP project might look like:
# Playwright MCP Project

This project contains Playwright end-to-end tests with MCP (Model Context Protocol) integration.

## Installation

```bash
npm install

Running Tests
npx playwright test


Project Structure
- tests/ – All Playwright test files
- hello.js – Sample Node.js script
- package.json – Project configuration

---

# 🛠️ Where do you create README.md?

Inside your project folder:


PlayWrightMCP/ README.md package.json hello.js tests/

---

# ⭐ Why it’s important

- GitHub shows it automatically  
- Helps others understand your project  
- Helps YOU remember how things work  
- Makes your repo look professional  



> playwrightmcp@1.0.0 npx
> create-playwright

Getting started with writing end-to-end tests with Playwright:
Initializing project in '.'
? Do you want to use TypeScript or JavaScript? ...
> TypeScript
  JavaScript

  Getting started with writing end-to-end tests with Playwright:
Initializing project in '.'
√ Do you want to use TypeScript or JavaScript? · TypeScript
√ Where to put your end-to-end tests? · tests
√ Add a GitHub Actions workflow? (Y/n) · true
√ Install Playwright browsers (can be done manually via 'npx playwright install')? (Y/n) · true
Installing Playwright Test (npm install --save-dev @playwright/test)…

added 3 packages, and audited 4 packages in 2s


Inside that directory, you can run several commands:

  npx playwright test
    Runs the end-to-end tests.

  npx playwright test --ui
    Starts the interactive UI mode.

  npx playwright test --project=chromium
    Runs the tests only on Desktop Chrome.

  npx playwright test example
    Runs the tests in a specific file.

  npx playwright test --debug
    Runs the tests in debug mode.

  npx playwright codegen
    Auto generate tests with Codegen.

We suggest that you begin by typing:

    npx playwright test

And check out the following files:
  - .\tests\example.spec.ts - Example end-to-end test
  - .\playwright.config.ts - Playwright Test configuration

Visit https://playwright.dev/docs/intro for more information. ✨
[]=================
🔽 Collapse / Fold Shortcuts in VS Code (Windows)
⭐ Collapse everything in the file
- #Ctrl + K, then Ctrl + 0
Folds all foldable regions — perfect for config files like playwright.config.ts.
⭐ Collapse just the current block
- #Ctrl + Shift + [
Folds the block where your cursor is (e.g., inside projects: []).
⭐ Expand the current block
- #Ctrl + Shift + ]
⭐ Expand everything
- #Ctrl + K, then Ctrl + J

💡 Tip for Playwright config files
playwright.config.ts often has large objects (projects, use, reporter, etc.).
Using Ctrl + K → Ctrl + 0 makes it easy to collapse everything and then expand only what you need.

