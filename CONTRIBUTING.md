# Spam-Emails-Classification-approaches
---
## Quick start
This quick start guide outlines the git/github process to add a new feature to the project.

1. Clone the repository :

```bash
# https
git clone https://github.com/amdjedbens/Spam-Emails-Classification-approaches
```

Or

```bash
# ssh
git clone git@github.com:amdjedbens/Spam-Emails-Classification-approaches.git
```

2. Make a separate branch :

```bash
git branch {YourBranchName} # Branch Example: LinearRegression_branch

# Switch between different branches via
git checkout {OtherBranch} # git checkout main: to switch to main branch.
```
3. Make changes locally.
4. Add the changed files:
```bash
git add NotebookName
```
5. Commit your changes
```bash
git commit
# Make sure to add a "clear" and "explanatory" commit message, with details if necessary.
```
6. Push your changes:
```bash
git push origin {YourBranchName} # git push origin LinearRegression_branch
```
7. Make a pull request on Github.

### Important note:

**Always** pull from origin before making local changes :

```bash
git pull origin main
```

