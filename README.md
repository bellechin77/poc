# 📝 Playwright Blog Application Test Suite (TypeScript)

This project showcases a **Proof of Concept (PoC)** using **Playwright** with **TypeScript** to automate testing for a blog application. The tests cover:
- Searching for articles
- Opening articles
- Posting comments
- Verifying that comments are displayed correctly

The tests are built using the **Page Object Model (POM)** for better maintainability and scalability.

---

## 🚀 **Features**

- ✅ Interactions with web elements (buttons, inputs, forms)
- ✅ Usage of specific locators (`getByRole`, `getByLabel`, `getByPlaceholder`)
- ✅ Handling parent-child relationships (comments under blog posts)
- ✅ Structured Page Object Model (POM) for modularity
- ✅ Assertions with auto-retry and non-retry behaviors
- ✅ Use of `async/await` for handling asynchronous operations
- ✅ Debugging tools and error handling
- ✅ Test lifecycle hooks (`beforeEach`, `afterEach`)
- ✅ Built-in fixtures (`page`, `browser`, `context`)

---

## 📂 **Project Structure**

/tests
  ├── articlePage.ts          // Page Object for interacting with articles
  ├── commentPage.ts          // Page Object for handling comments
  ├── blog.spec.ts            // The actual test file
  ├── playwright.config.ts    // Playwright configuration (test setup, retries, reports)


