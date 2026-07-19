# Contribution Guide 

 This guide will walk you through the complete workflow for contributing code to this repository.

---

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Cloning the Repository](#cloning-the-repository)
3. [Switching to Develop Branch](#switching-to-develop-branch)
4. [Creating a Feature Branch](#creating-a-feature-branch)
5. [Making Changes](#making-changes)
6. [Committing Changes](#committing-changes)
7. [Pushing to GitHub](#pushing-to-github)
8. [Creating a Pull Request from VS Code](#creating-a-pull-request-from-vs-code)
9. [Best Practices](#best-practices)

---

## Prerequisites

Before you start, make sure you have:

| Tool | Installation Link |
|------|-------------------|
| **Git** | [Download Git](https://git-scm.com/downloads) |
| **VS Code** | [Download VS Code](https://code.visualstudio.com/) |
| **GitHub Account** | [Sign up](https://github.com/) |
| **GitHub Pull Request Extension** | [Install from VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) |

---

## Cloning the Repository

**Open your terminal and run:**

```bash
git clone https://github.com/KingsCreatives/aws-cloud-webapp-deployment.git
```

**Then open the project in VS Code:**
```bash
cd aws-cloud-webapp-deployment
code .
```

---

## Switching to Develop Branch

**In your terminal, run:**

```bash
git checkout develop
```

**Pull the latest changes:**
```bash
git pull origin develop
```

---

## Creating a Feature Branch

**In your terminal, run:**

```bash
git checkout -b feature/your-feature-name
```

**Example:**
```bash
git checkout -b feature/fix-header-styling
```

---

## Making Changes

**Step 1:** Open the file you want to edit in VS Code

**Step 2:** Make your changes

**Step 3:** Save the file (`Ctrl+S`)

**Tip:** Check your changes in the **Source Control** panel (`Ctrl+Shift+G`)

---

## Committing Changes

**Step 1:** Stage your changes:
```bash
git add .
```
*Or stage specific files:*
```bash
git add src/index.html
```

**Step 2:** Commit with a clear message:
```bash
git commit -m "Your clear commit message"
```

**Example:**
```bash
git commit -m "Fix header alignment on mobile devices"
```

---

## Pushing to GitHub

**Push your branch to GitHub:**

```bash
git push origin feature/your-feature-name
```

**Example:**
```bash
git push origin feature/fix-header-styling
```

---

## Creating a Pull Request from VS Code

**Step 1:** Open the **Source Control** panel (`Ctrl+Shift+G`)

**Step 2:** Click the **"GitHub Pull Request"** icon in the left sidebar (looks like a merge/PR icon)

**Step 3:** Click **"Create Pull Request"**

**Step 4:** Fill in the PR details:

| Field | Instructions |
|-------|--------------|
| **Title** | Clear, descriptive title (e.g., "Fix header styling on mobile") |
| **Description** | Explain what you changed and why |
| **Base** | `develop` (target branch) |
| **Compare** | `feature/your-branch-name` (your branch) |

**Example PR Description:**
```
## What I Changed
- Fixed header alignment on mobile devices
- Added responsive breakpoints for tablets
- Updated CSS styles

## Why This Matters
Improves user experience on mobile devices
```

**Step 5:** Click **"Create"**

**Step 6:** Click **"Submit"**

---

## Best Practices

| Practice | Do | Don't |
|----------|-------|----------|
| **Branch Naming** | `feature/add-login-page` | `my-branch` |
| **Commit Messages** | `git commit -m "Fix header alignment"` | `git commit -m "Update"` |
| **PR Size** | Small, focused changes | Huge files with many changes |
| **Code Review** | Request reviews from team members | Merge without approval |
| **Testing** | Test locally before pushing | Push without testing |

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| **"Branch already exists"** | Use a unique branch name |
| **"Merge conflict"** | Pull latest `develop` and resolve conflicts |
| **"Permission denied"** | Ensure you have access to the repository |
| **VS Code can't find GitHub** | Install GitHub Pull Request extension |

---

<div align="center">



</div>
