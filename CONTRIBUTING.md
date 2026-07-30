# Contributing to Awesome ForgeCoders

First off, thank you for taking the time to contribute! 🎉

Awesome ForgeCoders is a community-driven repository. Every resource, tutorial, and tool listed here is added by developers like you. By contributing, you help make the developer ecosystem more accessible to everyone.

Please read through the guidelines below to get started.

---

## 🗺️ Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [How Can I Contribute?](#-how-can-i-contribute)
- [Resource Format Guidelines](#-resource-format-guidelines)
- [Contribution Example (Step-by-Step)](#-contribution-example-step-by-step)
- [Commit Message Guidelines](#-commit-message-guidelines)
- [Pull Request Checklist](#-pull-request-checklist)

---

## 🤝 Code of Conduct

By participating in this project, you agree to maintain a respectful, welcoming, and inclusive environment. Please treat all contributors with kindness and respect.

---

## 🛠️ How Can I Contribute?

### 1. Suggesting New Resources
If you know of an awesome tutorial, documentation site, book, or interactive playground that isn't listed, please add it!
*   Ensure the resource is of high quality and free of spam or paywalls (unless it is a highly-reputable industry standard like Three.js Journey).
*   Search the existing repository to ensure the resource is not already listed.

### 2. Improving Documentation
If you spot typos, broken links, formatting issues, or outdated references, feel free to submit a fix.

---

## 📝 Resource Format Guidelines

To keep the list clean and uniform, please follow this format when adding resources:

```markdown
*   [Resource Name](URL) - A brief, clear description (1-2 sentences) of what the resource teaches or provides.
```

- **Capitalization**: Capitalize the first letter of the description and end it with a period.
- **Sorting**: Try to insert resources alphabetically within their respective category section, or at the end of the list if sorting is not strictly enforced.

---

## 🚀 Contribution Example (Step-by-Step)

Here is a practical walkthrough of how to contribute a resource:

### Step 1: Fork the Repository
Click the **Fork** button at the top-right of the [Awesome ForgeCoders GitHub page](https://github.com/ForgeCoders/awesome-forgecoders) to create a copy of the repository under your own GitHub account.

### Step 2: Clone Your Fork
Clone the repository to your local machine using Git:
```bash
git clone https://github.com/YOUR-USERNAME/awesome-forgecoders.git
cd awesome-forgecoders
```

### Step 3: Create a Branch
Create a new branch with a descriptive name for your change:
```bash
git checkout -b feat/add-python-resource
```

### Step 4: Make Your Changes
Open `README.md` in your text editor. Find the appropriate section (e.g., `# Python` under `## Languages & Runtimes`), and add your resource following the format guidelines.

For example:
```diff
  ### Python
  *   [Python official Documentation](https://docs.python.org/3/) - The official, definitive reference for the Python programming language.
  *   [Real Python](https://realpython.com/) - High-quality, in-depth tutorials and articles for Pythonistas of all levels.
+ *   [LearnPython.org](https://www.learnpython.org/) - An interactive Python tutorial offering free coding lessons for beginners.
  *   [The Hitchhiker’s Guide to Python](https://docs.python-guide.org/) - An opinionated guide to the installation, configuration, and daily usage of Python.
```

### Step 5: Commit and Push
Commit your changes with a clean commit message and push the branch to your fork:
```bash
git add README.md
git commit -m "docs: add LearnPython.org to Python resources"
git push origin feat/add-python-resource
```

### Step 6: Create a Pull Request
Go to your fork's page on GitHub. You will see a banner suggesting you to **Compare & pull request**. Click it, fill out the Pull Request template, and submit!

---

## 💬 Commit Message Guidelines

We recommend using clear, descriptive commit messages. Using semantic prefixes (inspired by Conventional Commits) is highly appreciated:
- `docs: ...` for updating documentation or adding resources (e.g., `docs: add Next.js tutorials`)
- `fix: ...` for fixing links or typos (e.g., `fix: repair broken link to Pro Git book`)
- `style: ...` for formatting adjustments (e.g., `style: fix list indentation in README`)

---

## ✅ Pull Request Checklist

Before submitting your PR, please make sure to double-check the following:
- [ ] The link works and uses HTTPS.
- [ ] The description is concise, accurate, and grammatically correct.
- [ ] No duplicate links have been introduced.
- [ ] The change is added to the correct category section.
