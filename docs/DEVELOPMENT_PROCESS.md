# Development Process

## Overview
This project follows a collaborative development workflow involving **mnyon-grandkru** and **gktreviewer**.

## Workflow

### 1. Branch Naming
- `feature/<description>` - New features
- `fix/<description>` - Bug fixes
- `refactor/<description>` - Code refactoring
- `docs/<description>` - Documentation updates

### 2. Making Changes
1. Create a new branch from `main`:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and commit them:
   ```bash
   git add .
   git commit -m "Description of changes"
   ```

3. Push your branch to remote:
   ```bash
   git push -u origin feature/your-feature-name
   ```

### 3. Pull Requests
1. Open a Pull Request on GitHub as **mnyon-grandkru**
2. Request review from **gktreviewer**
3. Fill out the PR template if one exists

### 4. Code Review Process
- All changes require approval from **gktreviewer** before merging
- Reviewer will:
  - Review code for correctness
  - Check for code quality and style
  - Verify tests pass
  - Leave comments if changes are needed
- Approval format: **LGTM** (Looks Good To Me)

### 5. Merging
- After receiving LGTM from **gktreviewer**, **mnyon-grandkru** merges the PR
- Squash and merge preferred for clean history
- Delete branch after merging

### 6. Keeping Feature Branches Updated
- When `main` is updated, feature branches are automatically rebased
- To manually rebase your feature branch onto latest `main`:
  ```bash
  git checkout feature/your-feature-name
  git fetch origin
  git rebase origin/main
  ```

## Testing
- Run tests before submitting PR:
  ```bash
  # Add your test command here
  ```

## Deployment
- Deployment steps go here (if applicable)

## Questions?
Reach out to **mnyon-grandkru** or **gktreviewer** for clarifications.
