# Shell-scripting-mini-project
Followed Abhishek veeramalla's Lecture for this Project 

# GitHub Read Access Lister

This Bash script uses the GitHub API to list users who have **read access** to a specific GitHub repository.

---

## 💡 What It Does

- Accepts a **repository owner** and **repository name** as input.
- Authenticates using your **GitHub username and personal access token**.
- Calls the GitHub API to get a list of **collaborators**.
- Filters and displays users who have **read access** (`permissions.pull == true`) to the repository.
- Helps you audit who can view (but not necessarily write to) a given GitHub repo.

---

## 🔧 Requirements

- `bash`
- `curl`
- [`jq`](https://stedolan.github.io/jq/) – for parsing JSON
- A **GitHub Personal Access Token** with access to view collaborators on the repo

---

## 🛠️ Setup

1. **Clone the repository** 

   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo

