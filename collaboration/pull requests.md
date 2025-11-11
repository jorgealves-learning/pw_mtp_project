# Understanding Pull Requests on GitHub

## 📘 Overview

A **Pull Request (PR)** is a feature on GitHub that allows developers to propose changes to a repository.  
It’s a way of saying:  
> “I’ve made some modifications to the code — please review them and, if everything looks good, merge them into the main project.”

Pull requests are a core part of collaborative development. They make it easy to:
- Review code before it becomes part of the main codebase.
- Discuss proposed changes with team members.
- Track, test, and verify changes before merging.

---

## 🧩 How Pull Requests Work

A pull request is typically created after pushing changes to a **branch** in a repository.

### 1. **Fork or Branch**
- If you don’t have write access to a repository:
  - You **fork** the repository (create your own copy).
  - Make changes in your fork, and then open a PR to the original (upstream) repository.
- If you do have write access:
  - You create a **branch** in the same repository.
  - Make changes in that branch, and then open a PR to merge into the main branch (e.g., `main` or `develop`).

### 2. **Make Changes**
You commit changes (code edits, documentation updates, etc.) in your branch.  
Each commit represents a snapshot of your work.

### 3. **Open a Pull Request**
When your changes are ready, you create a **pull request**:
- Choose the **base branch** (the branch you want to merge into, usually `main`).
- Choose the **compare branch** (the branch containing your new changes).
- Add a **title** and **description** explaining the purpose of your PR.

Example:
> **Title:** Fix bug in user authentication  
> **Description:**  
> This PR fixes a logic issue where users were incorrectly logged out after refreshing the page.

### 4. **Code Review**
Team members (or maintainers) review your pull request:
- Leave **comments** or **suggestions**.
- Request **changes** or approve it.

This process improves code quality and ensures everyone understands the updates.

### 5. **Testing & Validation**
Automated tests (via GitHub Actions or other CI/CD tools) may run to check:
- Build success
- Test results
- Code style and linting
- Security checks

### 6. **Merge the Pull Request**
Once approved and all checks pass:
- The PR can be **merged** into the base branch.
- Common merge options:
  - **Merge Commit** – Keeps a full history of commits.
  - **Squash and Merge** – Combines all commits into one.
  - **Rebase and Merge** – Places commits on top of the target branch.

After merging, the branch can usually be deleted.




