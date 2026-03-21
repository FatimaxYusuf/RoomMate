# Contributing to RoomMate

Thank you for your interest in contributing to **RoomMate** — an open-source hotel reservation system. This document explains how to get involved.

> [!NOTE]
> Contributions of all sizes are welcome, including code improvements, documentation updates, bug reports, and feature suggestions.

---

## Ways to Contribute

You can contribute to RoomMate in several ways:

- Report bugs through [GitHub Issues](https://github.com/FatimaxYusuf/ITSE476_project/issues)
- Suggest new features or improvements
- Fix existing issues and submit a pull request
- Improve the documentation or FAQ
- Join the discussion on [GitHub Discussions](https://github.com/FatimaxYusuf/ITSE476_project/discussions)

---

## Before You Start

Before making changes, please:

- Check the [open issues](https://github.com/FatimaxYusuf/ITSE476_project/issues) to see whether your idea or bug is already being tracked
- Open an issue first for major changes so the approach can be discussed before implementation

---

## How to Contribute

### 1. Fork the repository

Click **Fork** on the top-right of the repository page to create your own copy.

### 2. Clone your fork

```bash
git clone https://github.com/YOUR_USERNAME/ITSE476_project.git
cd ITSE476_project
```

### 3. Create a new branch

Use a clear and descriptive branch name.

```bash
git checkout -b fix/issue-description
```

or

```bash
git checkout -b feature/feature-name
```

### 4. Make your changes

Keep your work focused. Each branch should address one issue, feature, or improvement.

### 5. Write a clear commit message

Use the following format:

```text
type: short description
```

Examples:

```text
fix: correct room availability check
feat: add email validation to user registration
docs: update FAQ with cancellation steps
```

### 6. Push your branch

```bash
git push origin your-branch-name
```

### 7. Open a Pull Request

Go to the original repository and open a **New Pull Request**. Clearly describe what you changed and why.

---

## Code Standards

Contributors are expected to follow these standards:

- Java code should use standard naming conventions  
  - `camelCase` for variables and methods  
  - `PascalCase` for classes
- New logic should include corresponding JUnit tests
- Do not commit compiled files such as `*.class` or `bin/` directories
- Keep methods short, clear, and focused
- Add Javadoc comments to public methods when appropriate

---

## Code of Conduct

This project follows a simple standard: **be respectful**.

Harassment, discrimination, or hostile communication of any kind will not be tolerated. Please follow the project’s Code of Conduct in all discussions, issues, and pull requests.

---

## Questions

If you have questions, you can:

- Open a thread on [GitHub Discussions](https://github.com/FatimaxYusuf/ITSE476_project/discussions)
- Check the [FAQ](FAQ.md)
