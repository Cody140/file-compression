# File-compression

Welcome to our project! This document serves as a guide for contributing to the project efficiently and effectively. We use a branching strategy and conventional commits to ensure our project's history is readable and manageable.

## Getting Started

First, make sure you have cloned the repository to your local machine:

```bash
git clone https://github.com/AndrejsMihailicenko/file-compression.git
cd file-compression
```

## Branching Strategy
For every new feature, bug fix, or improvement, create a new branch from the latest version of the main branch:

```bash
git checkout main
git pull origin main
git checkout -b feature/your-feature-name
```
Branch names should be descriptive and reflect the work being done. We recommend prefixes like feature/, bugfix/, or hotfix/, followed by a brief description.

## Making Changes and Committing
After making your changes, commit them using conventional commit messages. This helps in generating meaningful changelogs and understanding the purpose of changes at a glance.

Here are the basic commit types you should use:

feat: A new feature<br>
fix: A bug fix<br>
docs: Documentation only changes<br>
style: Code formatting, semi-colons, etc.<br>
refactor: Neither fixes a bug nor adds a feature<br>
perf: Improves performance<br>
test: Adding missing tests<br>
chore: Changes to the build process or auxiliary tools<br>
Example commit message:
```
bash
Copy code
git commit -m "feat: add user login functionality"
```
## Submitting Pull Requests
Once your changes are committed, push the branch to the remote repository:

```bash
git push origin feature/your-feature-name
```
Then, go to the repository on GitHub and create a new pull request.<br>
The pull request should be from your new branch to the main branch.<br>
Provide a clear and concise description of what your changes do.
