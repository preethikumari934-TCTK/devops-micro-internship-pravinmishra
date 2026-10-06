# Assignment 5 — Connecting Claude to the Outside World

Part of the DevOps Micro Internship (DMI) with Agentic AI

---

## Purpose

In this assignment, you will connect Claude Code to external systems using MCP (Model Context Protocol). You will configure the GitHub MCP server, securely store credentials, verify the connection, and run a live query that proves Claude is accessing real-time GitHub data.

---

# Task 1 — Create a GitHub Personal Access Token

## Goal

Generate a GitHub Personal Access Token (PAT) that will be used for MCP authentication.

### Evidence

#### Screenshot 1 — GitHub token creation page showing the selected scopes (`repo`, `read:user`) — token value must NOT be visible
<img width="944" height="526" alt="Screenshot 2026-10-05 160753" src="https://github.com/user-attachments/assets/48b451d6-b227-48a6-9638-97e14079d3e1" />
<img width="950" height="535" alt="Screenshot 2026-10-05 160907" src="https://github.com/user-attachments/assets/3e782b5c-36a7-4aee-86fe-f1e7d63feed3" />


---

# Task 2 — Create .mcp.json at the Project Root

## Goal

Create and configure the `.mcp.json` file to define the GitHub MCP server.

### Evidence

#### Screenshot 2 — `.mcp.json` open in VS Code showing the full configuration

<img width="717" height="507" alt="image" src="https://github.com/user-attachments/assets/6e9208dd-c0ee-44ff-8a19-1f784945f856" />


---

# Task 3 — Add Your Token to settings.local.json

## Goal

Store your GitHub token securely in `.claude/settings.local.json` and ensure it is not committed to version control.

### Evidence

#### Screenshot 3 — `settings.local.json` open in VS Code showing the `env` section — **blur or cover the actual GitHub token value**

<img width="667" height="407" alt="image" src="https://github.com/user-attachments/assets/5126bf4e-a8a0-4e6a-9b0a-b20754ca311c" />

---

# Task 4 — Verify the Connection with /mcp

## Goal

Confirm that the GitHub MCP server is successfully connected inside Claude Code.

### Evidence

#### Screenshot 4 — `/mcp` output showing `github: connected`

<img width="947" height="485" alt="image" src="https://github.com/user-attachments/assets/6382cc3a-c758-47b5-af2b-ba6bcfd70e56" />

---

# Task 5 — Run a Live GitHub Query

## Goal

Verify MCP functionality by retrieving real-time data from your GitHub account using Claude Code.

### Evidence

#### Screenshot 5 — Claude's response showing the GitHub MCP tool call and the retrieved README.md content.

<img width="461" height="398" alt="image" src="https://github.com/user-attachments/assets/63b12942-3246-44e0-a525-5e3fc1b33c53" />

---


# Submission Instructions

- Ensure `.mcp.json` is committed to your GitHub repository
- Ensure `.claude/settings.local.json` is NOT committed (must be gitignored)
- Confirm token value is hidden in all screenshots
- Add all required screenshots to your submission
- Push final changes to your forked repository

---

## GitHub Repository URL

Paste your forked repository URL here:

`https://github.com/preethikumari934-TCTK/devops-micro-internship-pravinmishra

 https://github.com/preethikumari934-TCTK/Ultimate-Agentic-DevOps-with-Claude-Code
## Security Confirmation

Confirm below:

- [ ] `settings.local.json` is added to `.gitignore`
- [ ] GitHub token is NOT exposed in repository or screenshots

---

# Completion Checklist

- [✅] GitHub PAT created with correct scopes (`repo`, `read:user`)
- [✅] `.mcp.json` created at project root
- [✅] `.claude/settings.local.json` contains token (hidden in screenshot)
- [✅] `.claude/settings.local.json` is NOT committed
- [✅] `/mcp` shows GitHub connection as active
- [✅] Live GitHub query returns real repository data
- [✅] All required screenshots added
- [✅] GitHub repository URL included
- [✅] MCP achievement shared on Facebook or WhatsApp Status
- [✅] Screenshot 6 added showing the published post/status

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.

---

## 📌 Resources

- 🌐 DMI Official Website: https://dmi.pravinmishra.com?utm_source=github&utm_medium=readme  
- 🎓 University: https://university.pravinmishra.com?utm_source=github&utm_medium=readme  
- 💬 Discord Community: https://discord.pravinmishra.com?utm_source=github&utm_medium=readme  
- 📝 Blog: https://dmi.pravinmishra.com/blog?utm_source=github&utm_medium=readme  
- ▶️ YouTube Playlist: https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 Pravin Mishra (LinkedIn): https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 CloudAdvisory (LinkedIn): https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) — Agentic AI Track.*
