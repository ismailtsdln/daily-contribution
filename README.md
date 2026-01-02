# Daily GitHub Contribution Trigger

This repository is a minimal and automated setup to generate **daily GitHub contributions** using **GitHub Actions**.

It updates a small file once per day and commits the change automatically, ensuring consistent activity on the GitHub contribution graph.

---

## 🚀 How It Works

- GitHub Actions runs on a daily schedule (cron)
- A simple text file (`heartbeat.txt`) is updated with the current timestamp
- The change is automatically committed to the repository
- Each successful run generates **one contribution** on your GitHub profile

---

## 🧠 Why This Exists

This project is useful for:

- Maintaining a consistent contribution streak
- Testing GitHub Actions cron workflows
- Learning basic GitHub Actions automation
- Keeping your profile active during busy periods

> This project does **not** spam commits.  
> It generates **one clean commit per day**, which aligns with GitHub’s contribution rules.

---

## 📁 Project Structure

```text
.
├── heartbeat.txt
└── .github
    └── workflows
        └── daily.yml
