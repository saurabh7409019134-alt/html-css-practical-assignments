# Task 5 — Initialize and publish with GitHub

## Completed setup

The local project is initialized on `main`, has four meaningful commits, and is pushed to [the private GitHub repository](https://github.com/saurabh7409019134-alt/html-css-practical-assignments). The pushed branch and module files were confirmed in GitHub. The repository is private; invite your faculty member if they need access, or change visibility only if your course specifically requires a public repository.

## Repeatable workflow reference

## Local repository

From the project root, run `git init`, `git status`, `git add .`, then `git commit -m "docs: add assignment plan and setup guides"`. Continue with the meaningful milestones in Task 4. Check `git status` after each commit.

## GitHub repository

1. Sign in to your GitHub account in a browser and choose **New repository**.
2. Name it `html-css-practical-assignments`. Select visibility according to your faculty's instructions. Avoid initializing it with another README if your local project already has one.
3. Copy the repository URL GitHub shows you. Back in the terminal, connect it with `git remote add origin <your-repository-url>`.
4. Set the default branch and push: `git branch -M main` then `git push -u origin main`. GitHub may ask you to authenticate.
5. Open the repository URL in a browser. Verify that `README.md`, `index.html`, module folders, and docs are visible. Copy the real URL into your submission form.

**Still requires your participation:** share the repository link with your faculty, and grant them access if needed. The repository URL above is real; it is private.
