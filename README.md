Lab Brief Discription:

This lab is to gain practical experience using Git and GitHub with GitHub Desktop for version control, collaboration, and conflict resolution. Students will learn to create and manage repositories, commit changes, work with branches, and resolve merge conflicts using a GUI-based workflow.


This is branch-a and branch-b

# Git Desktop Lab

## Lab Brief Description:
This lab is to gain practical experience using Git and GitHub with GitHub Desktop for version control, collaboration, and conflict resolution. Students will learn to create and manage repositories, commit changes, work with branches, and resolve merge conflicts using a GUI-based workflow.

---

## Software Required:
- [GitHub Account](https://github.com/)
- [GitHub Desktop](https://desktop.github.com/)

---

## Lab Activities Summary:

### 1. Repository Setup
- Created a GitHub repository named `git-desktop-lab` with a `README.md`.
- Cloned the repository to local machine using GitHub Desktop.

### 2. Basic Git Operations
- Created `info.txt` with name, student ID, and course information.
- Updated `README.md` with the lab description.
- Committed changes with messages:
  - "Add info.txt with personal details"
  - "Update README.md with lab description"
- Pushed the changes to the remote GitHub repository.

### 3. Branching and Merging
- Created a new branch `feature/new-content`.
- Added `content.txt` with a short paragraph about my favorite topic (UI/UX Design).
- Committed and pushed the file.
- Created and merged a pull request from `feature/new-content` to `main`.
- Pulled changes to keep `main` updated locally.

### 4. Merge Conflict Resolution
- Created two branches: `branch-a` and `branch-b` from `main`.
- In `branch-a`, added the line:  
  `This is branch-a`  
  → committed and merged to `main`.
- In `branch-b`, added the line:  
  `This is branch-b`  
  → tried merging `main` into `branch-b` and encountered a merge conflict.
- Resolved the conflict in `README.md` using GitHub Desktop by choosing the appropriate version.
- Committed the resolved file and pushed `branch-b` to GitHub.
- Created and merged a pull request from `branch-b` into `main`.

---

## Challenges Faced:
- Experienced a merge conflict when both `branch-a` and `branch-b` modified the same line in `README.md`.  
- Used GitHub Desktop to resolve the conflict and manually edited the file to retain the preferred version.

---

## Conclusion:
This lab helped me understand the Git workflow using GitHub Desktop, including repository management, branching, and resolving conflicts visually. It strengthened my ability to collaborate effectively using version control systems.

