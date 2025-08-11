# Contributing to Our Projects

First off, thank you for considering contributing to the **Homies Tech Innovation** community\! We are a group of passionate learners, and it's people like you who make our projects great. This document outlines our entire development process, from creating an issue to submitting a pull request.

Whether you're fixing a typo, adding a new feature, or refactoring some code, your contribution is valuable to us.

---

### 🚀 The Core Workflow

Our project management is centered around GitHub Issues and a Kanban board in **GitHub Projects**. Every piece of work, whether a new feature, a bug fix, or a refactor, is tracked as an issue.

The workflow on our Kanban board follows these stages:

- **📦 Backlog**: This is the idea box or "feature dump." All new issues are created here. They are not yet ready to be worked on.
- **✅ To Do**: The team has reviewed these issues, confirmed they are well-defined, and have no outstanding dependencies. This is the column where you should pick issues from.
- **🧑‍💻 In Progress**: Once you pick an issue, assign it to yourself and move it to this column. This signals to everyone else that the task is being actively worked on.
- **🕵️ In Review**: After completing your work and opening a Pull Request, move the related issue to this column. Be sure to link the PR in the issue.
- **🎉 Done**: Once the PR is reviewed, approved, and merged, the issue will be moved here and automatically closed.

### 🌿 Branching and Pull Requests

We follow a structured branching and pull request model to keep our codebases stable and clean.

#### Creating a Branch

All pull requests must be made from a feature branch to the `dev` branch. Pull requests made directly to the `main` branch will be rejected.

1.  **Find an Issue:** Pick an issue from the **To Do** column on our project board. Look for the `good first issue` label if you're new\!

2.  **Create Your Branch:** Create a new branch from the `dev` branch. Please use the following naming convention, which helps us understand the purpose of your work:

    - **Features:** `feature/<short-description>` (e.g., `feature/user-profile-page`)
    - **Bug Fixes:** `fix/<issue-number>-<short-description>` (e.g., `fix/42-login-button-crash`)
    - **Refactoring:** `refactor/<area-of-code>` (e.g., `refactor/api-service-layer`)
    - **Documentation:** `docs/<topic>` (e.g., `docs/pr-template-guide`)
    - **Chores (build scripts, configs, etc.):** `chore/<task-name>` (e.g., `chore/update-eslint-config`)

    <!-- end list -->

    ```bash
    # Make sure you are on the dev branch and have the latest changes
    git checkout dev
    git pull origin dev

    # Create your new feature branch
    git checkout -b feature/your-new-feature
    ```

#### Submitting a Pull Request

Once your work is complete, commit your changes and push your branch to the repository.

1.  Open a Pull Request from your branch to the `dev` branch.
2.  Fill out the PR template completely. Importantly, link the issue your PR resolves using a keyword like `Closes #123`. This ensures the issue is automatically closed when the PR is merged.
3.  Assign a reviewer from the team (refer to the project's `CODEOWNERS` file if it exists, or ask in our community chat).
4.  Move the issue card on the project board to the **In Review** column.

That's it\! Thank you again for your contribution. We look forward to collaborating with you\!
