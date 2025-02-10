# Team-Project
# Team Project: Mastering Git and GitHub for Collaboration

## Overview
This project is designed to help understand the core concepts of Git and GitHub, including collaboration, branching, forking, cloning, reverting, and resetting. The goal is to enhance teamwork and version control skills.

## Steps to Complete the Assignment

### Step 1: Set Up Your Repository
1. **Create a Repository**:
   - Go to GitHub and create a repository named `team-project`.
   - Add a `README.md` file and a `.gitignore` file for your preferred language.

2. **Clone the Repository Locally**:
   ```bash
   git clone https://github.com/your-username/team-project.git
   cd team-project
   ```

3. **Make Your First Commit**:
   - Create a `main.py` file and add initial content.
   - Stage and commit the changes:
     ```bash
     git add main.py
     git commit -m "Added main.py with initial code"
     git push origin main
     ```

### Step 2: Collaborate Using Branches
1. **Create a New Branch**:
   ```bash
   git checkout -b feature/new-feature
   ```
2. **Make changes, stage, and commit**:
   ```bash
   git add .
   git commit -m "Added new feature"
   git push origin feature/new-feature
   ```
3. **Create a Pull Request (PR)**:
   - Go to GitHub, click on "Pull Requests," and create a PR for the `feature/new-feature` branch.
   - Request a review and merge the PR into `main` after approval.

### Step 3: Fork a Repository
1. **Fork a Repository**:
   - Go to a public repository and click "Fork."

2. **Clone the Forked Repository**:
   ```bash
   git clone https://github.com/your-username/forked-repo.git
   ```

3. **Make Changes and Push**:
   - Modify files, commit, and push the changes.

4. **Create a PR to the Original Repository**:
   - Click "Contribute" > "Open Pull Request" on GitHub.

### Step 4: Revert and Reset
1. **Revert a Commit**:
   ```bash
   git revert <commit-hash>
   ```
   - This creates a new commit that undoes the previous changes.

2. **Reset a Commit (Use with Caution)**:
   ```bash
   git reset --hard <commit-hash>
   ```
   - This discards all changes after the specified commit.

### Step 5: Collaboration Workflow
1. **Simulate Team Collaboration**:
   - Clone each other's repositories, create branches, make changes, and submit PRs.
   - Review and merge PRs.

2. **Resolve Merge Conflicts**:
   - Edit the same file in two different branches to create a conflict.
   - Resolve the conflict manually, stage the changes, and commit.

## Conclusion
By completing this project, you will develop a strong understanding of Git and GitHub collaboration workflows, preparing you for real-world software development teamwork.

---
For any issues, feel free to open an issue or discuss in the repository!

