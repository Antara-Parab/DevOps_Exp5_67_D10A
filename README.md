# 🚀 DevOps Lab — Experiment 5
### Distributed Version Control System (DVCS) with Git & GitHub

![DevOps](https://img.shields.io/badge/Subject-DevOps%20Lab-orange?style=for-the-badge&logo=azuredevops)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📌 Practical Overview

* **Student:** Antara Aditi Ajit Parab
* **Roll No:** 67
* **Division:** D10A
* **Collaborator:** Tanvi
* **Institution:** Vidya Prasarak Mandal's Polytechnic, Thane

This repository contains the practical coursework for **DevOps Lab Experiment 5**, focusing on **Distributed Version Control Systems (DVCS)** using **Git** and cloud-hosted collaboration on **GitHub**.

---

## 🎯 Objectives

1. Understand the core principles of Distributed Version Control Systems (DVCS) vs. Centralized VCS.
2. Initialize, track, stage, commit, and sync project files using the Git command-line interface (CLI).
3. Demonstrate collaborative workflows on remote GitHub repositories (pushing, pulling, and multi-user branch management).

---

## 💡 Key Concepts

### 1. What is Git?
> **Git** is an open-source, distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Every developer's working copy of the code is also a full-fledged repository that can contain the complete history of all changes.

### 2. What is GitHub?
> **GitHub** is a cloud-based hosting service and collaboration platform for Git repositories, enabling distributed teams to share code, review pull requests, and manage issues.

---

## 🛠️ Git Architecture & Workflow

```text
+------------------+       git add        +------------------+
|                  | -------------------> |                  |
| Working Directory|                      |   Staging Area   |
|                  | <------------------- |  (Index/Cache)   |
+------------------+     git checkout     +------------------+
         |                                         |
         |                                         | git commit
         |                                         v
         |     git pull / fetch           +------------------+
         +------------------------------- |                  |
                                          | Local Repository |
         +------------------------------- |      (.git)      |
         |         git push               +------------------+
         v                                         |
+------------------+                               | git push
|                  | <-----------------------------+
| Remote Repository|
|     (GitHub)     |
+------------------+
```

---

## 📝 Essential Git Commands Practiced

```bash
# Initialize a local Git repository
git init

# Check the status of modified and untracked files
git status

# Stage specific changes for the next commit
git add <filename>

# Stage all updated files
git add .

# Record staged changes to the repository history
git commit -m "Commit message explaining changes"

# Link local repository to a remote GitHub repository
git remote add origin https://github.com/Antara-Parab/DevOps_Exp5_67_D10A.git

# Push committed changes to the main branch
git push -u origin main

# Pull the latest changes from the remote repository
git pull origin main
```

---

## 🤝 Collaborative Activity

As part of this experiment:
1. Contributor files (`Antara_example.txt`) were authored and pushed to demonstrate single-author commits.
2. Pair collaboration (`Antara_Tanvi`) was conducted to simulate team workflows, remote synchronization, and conflict-free merging.

---

## 📁 Repository Structure

```text
DevOps_Exp5_67_D10A/
│
├── README.md               # Detailed experiment documentation and guide
├── Notes.txt               # Key DVCS definitions & revision notes
├── Antara_example.txt      # Contributor verification file
└── Antara_Tanvi            # Collaborative pair verification file
```

---

## 📄 License & Academic Integrity
This repository is created for educational and laboratory submission purposes under the curriculum of VPM's Polytechnic, Thane.
