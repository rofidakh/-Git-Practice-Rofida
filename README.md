# Git & GitHub Practice

## Part 1: Theoretical Questions 

1. **What is the difference between Git and GitHub?**

- **Git** is a distributed version control system (DVCS) used to handle versions of code. It helps developers manage their code history, track changes, and collaborate with others. Git is free and open-source, and can be used locally without any internet connection. It also provides GUI (Graphical User Interface) tools in addition to the command line.

- **GitHub** is a cloud-based platform that hosts Git repositories and adds features to make collaboration easier, such as pull requests, issue tracking, and project boards. It is one of several hosting services for Git (others include GitLab and Bitbucket). You can use Git without GitHub, but GitHub simplifies the collaboration process and project sharing.

---

2. **Explain the difference between `git pull` and `git fetch`.**

- `git fetch` connects to the remote repository and downloads any new data (commits, branches) but does **not** automatically update your working directory or merge any changes. It’s useful when you want to inspect changes before applying them.

- `git pull` is essentially a shortcut that does both `git fetch` and `git merge`. It fetches the latest changes from the remote repository and **automatically merges** them into your current branch.

---

3. **What is the purpose of `.gitignore` file?**

- The `.gitignore` file tells Git which files or folders should be ignored and not tracked by version control. This is useful to avoid committing files like:
  - Temporary files
  - Logs
  - Python cache files like `__pycache__/` or `.pyc`

It helps keep the repository clean and prevents sensitive or unnecessary files from being uploaded.

---

4. **Describe the steps to contribute to an open-source project on GitHub.**

1. **Fork** the repository to create your own copy under your GitHub account.
2. **Clone** the forked repository to your local machine.
3. **Create a new branch** to work on a specific feature or fix.
4. **Make changes** in your branch and commit them with clear messages.
5. **Push your branch** to your forked repository.
6. **Open a Pull Request** to the original repository explaining the changes you made.
7. **Participate in the review process** if maintainers request changes.
8. Once approved, your changes will be **merged** into the main project by the maintainers.

---

## Part 2: Task Summary

This project was created to practice Git and GitHub skills through a series of practical steps. Below is a summary of what has been completed:

-  Created a GitHub repository named `Git-Practice-Rofida`.
-  Initialized the repository with a `README.md` file and cloned it locally.
-  Created a Python script named `hello.py` that prints `Hello GitHub!` and pushed it to the repository.
-  Created a new branch called `feature/info`, added a file named `info.txt` with a few lines about myself, then pushed the branch to GitHub.
-  Opened a Pull Request on GitHub and successfully merged the `feature/info` branch into `main`.
- Created and switched to a new branch called `fix/readme`, updated this `README.md` file with both the theoretical answers and this task summary, and merged the changes back to `main`.
- Bonus: Added a `.gitignore` file and included Python cache files such as `__pycache__/` and `*.pyc` to keep the repository clean.

---


