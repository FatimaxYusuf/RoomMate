# Contributing to RoomMate
Thank you for your interest in contributing to RoomMate — an open-source hotel reservation system. This document explains how to get involved.



## Ways to Contribute

- Report bugs via [GitHub Issues](https://github.com/FatimaxYusuf/ITSE476_project/issues)
- Suggest new features or improvements
- Fix existing issues and submit a pull request
- Improve documentation or the FAQ
- Join the discussion on [GitHub Discussions](https://github.com/FatimaxYusuf/ITSE476_project/discussions)



## Before You Start

- Check the [open issues](https://github.com/FatimaxYusuf/ITSE476_project/issues) to see if your idea or bug is already being tracked
- For large changes, open an issue first to discuss the approach before writing code



## How to Contribute

### 1. Fork the repository
Click *Fork* on the top right of the repo page to create your own copy.

### 2. Clone your fork
bash
git clone https://github.com/YOUR_USERNAME/ITSE476_project.git
cd ITSE476_project


### 3. Create a new branch
Use a descriptive branch name:
bash
git checkout -b fix/issue-description
# or
git checkout -b feature/feature-name


### 4. Make your changes
Keep changes focused. One issue or feature per branch.

### 5. Write a clear commit message
Follow this format:

type: short description

Examples:
fix: correct room availability check
feat: add email validation to user registration
docs: update FAQ with cancellation steps


### 6. Push your branch
bash
git push origin your-branch-name


### 7. Open a Pull Request
Go to the original repo and click *New Pull Request*. Describe what you changed and why.

---

## Code Standards

- Java code should follow standard naming conventions (camelCase for variables/methods, PascalCase for classes)
- All new logic must have corresponding JUnit tests
- Do not commit compiled files (*.class, bin/) — these are in .gitignore
- Keep methods short and focused; add Javadoc comments to public methods

---

## Code of Conduct

This project follows a simple standard: be respectful. Harassment, discrimination, or hostile communication of any kind will not be tolerated. See the Contributors page on the project website for the full Code of Conduct.

---

## Questions?

Open a thread on [GitHub Discussions](https://github.com/FatimaxYusuf/ITSE476_project/discussions) or check the [FAQ](FAQ.md).

