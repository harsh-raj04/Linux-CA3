# Reflection Report – GitHub Collaboration Practical (Task E)

**Name:** Harsh Raj  
**Date:** April 9, 2025  
**GitHub Collaboration Practical – Duration: 2 Hours**

---

## 🧑‍💻 Accounts Used

- **Account A:** `harsh-raj04` (Original Repository Owner)
- **Account B:** `harsh7992` (Collaborator via Fork and PR)

---

## ✅ Workflow Summary

### 🔹 Task A – Create & Explore GitHub Repository (Account A)
- Created a public repository: `Linux-CA3`.
- Added a descriptive README.
- Starred and watched the repository.
- Created a sample issue.

### 🔹 Task B – Local Setup & Remote Linking (Account A)
- Initialized a local Git repository.
- Created a sample file (`main.py`) and committed it.
- Added GitHub remote and successfully pushed using `git push origin main`.

### 🔹 Task C – Cloning and Modifying (Account A)
- Cloned the original repo locally.
- Added a new file (`taskC_note.txt`) with content.
- Committed and pushed changes.
- Verified commit on GitHub.

### 🔹 Task D – Collaboration via Fork, Branch, PR (Account B → A)
- Forked the repository from Account A using Account B.
- Cloned the fork locally (`harsh7992/Linux-CA3`).
- Created a new branch: `feature-update`.
- Added `contribution.txt` to simulate a contribution.
- Committed and pushed to Account B’s fork.
- Faced a **permission error**; resolved by re-setting the remote and authenticating with Account B.
- Opened a **pull request** to the original repository (`harsh-raj04/Linux-CA3`).
- Switched back to Account A, reviewed and **merged the PR**.

---

## ⚠️ Challenges Faced

- Encountered `non-fast-forward` errors when pushing — resolved using:
  ```bash
  git pull origin main --allow-unrelated-histories
