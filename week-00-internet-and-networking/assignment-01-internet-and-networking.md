# Week 00 - Internet and Networking

Part of the DevOps Micro Internship (DMI) with Agentic AI

---

# 🧑‍💻 Task 1: Using ChatGPT as Your Learning Assistant

## Scenario

You're new to DevOps and will frequently encounter technical questions. ChatGPT can be your learning companion.

## Your Task

Write a clear ChatGPT prompt to help you understand:

> "What is a protocol in networking? Explain with a simple real-life example."

Take a screenshot of your interaction showing:

* Your detailed prompt (with clear expectations)
* ChatGPT's simplified response with an example

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![Task 1 Screenshot](<img width="1071" height="718" alt="image" src="https://github.com/user-attachments/assets/a19e4d11-e39a-46fa-a48f-13f7ebfb75a5" />



Replace `task-1-chatgpt.png` with your actual screenshot file name.

---

## What I Learned (2–3 lines)

I have learned here that what is protocol and protocol in Networking

---

# 🌐 Task 2: Internet and Networking

## Scenario

Your friend is launching an online bookstore named **EpicReads**.

He asked you to explain how users globally can access his website hosted in Finland.

## Your Task

Write a short explanation (**100–150 words**) that includes:

* Packet Switching
* IP Address
* TCP/IP
* HTTP/HTTPS

💡 **Tip:** You may use ChatGPT (as demonstrated in Task 1) to refine your explanation.

## Answer
Packet switching is a method of sending data across a network by dividing it into small packets. These packets may take different routes but are reassembled when they reach their destination. An IP address identifies each device on a network, helping routers direct packets to the correct location. TCP/IP is the group of rules that makes internet communication possible: IP handles addressing and routing, while TCP helps ensure packets arrive accurately and in the right order. HTTP, or Hypertext Transfer Protocol, allows web browsers and servers to exchange pages, images, and other content. HTTPS is the secure form of HTTP. It encrypts data exchanged between a browser and website, helping protect private details such as passwords, banking information, and personal messages.

---

# 🏗️ Task 3: Application Architecture & Stack

## Scenario

EpicReads bookstore has two application versions:

### Two-Tier Application

* Frontend
* Database

### Three-Tier Application

* Frontend
* Backend
* Database

## Your Task

* Draw simple diagrams (hand-drawn or tool-based such as draw.io)
* Label each layer clearly
* List at least two common technologies or tools used for each layer
* Submit a screenshot or photo clearly showing your own drawing

## Diagram Screenshot / Photo

Save your diagram image in the `screenshots` folder and update the file name below.

![Application Architecture Diagram](<img width="484" height="264" alt="image" src="https://github.com/user-attachments/assets/e16f0514-215f-44aa-a52b-c79748b33eab" />

)


Replace `task-3-diagram.png` with your actual diagram file name.

---

## Technologies Used

### Frontend

*React.js (or Vue.js / Angular)
*HTML5 & CSS3 (with JavaScript)

### Backend

*Node.js (Express framework)
*Python (Django or Flask framework)
### Database

*Python (Django or Flask framework)
*MongoDB (or Microsoft SQL Server)
---

# 🌍 Task 4: Domain Name & DNS (Basic Concepts)

## Scenario

Your friend's bookstore **EpicReads** is currently accessible through:

```text
52.172.142.222:3000
```

He purchased the domain:

```text
epicreads.com
```

## Your Task

In **50–100 words**, explain in your own words:

1. What is DNS (Domain Name System)?
2. Which DNS record type should be used to connect the domain to the given IP, and why?

## Answer

DNS (Domain Name System) acts as the phonebook of the internet, translating human-friendly domain names (like epicreads.com) into machine-readable IP addresses (like 192.0.2.1).To connect a domain directly to an IP address, you must use an A record (Address record) for IPv4 addresses or an AAAA record for IPv6 addresses. This specific record type is required because its sole purpose in the DNS system is to map a static hostname directly to its corresponding physical server IP address, allowing user traffic to find your application.Would you like me to write out the exact DNS configuration line for your domain name and server IP address, or do you need to check if your IP address requires an A or an AAAA record?
---

# 💻 Task 5: Visual Studio Code Setup (Hands-on)

## Your Task

Install Visual Studio Code (if not already installed).

Take a screenshot of your VS Code environment showing:

* Terminal open inside VS Code
* Running a basic command:

### Windows

```powershell
dir
```

### Linux / macOS

```bash
pwd
ls
```

* Your selected VS Code theme clearly visible

⚠️ **Important:** The screenshot must show your username or another identifiable detail to confirm it is your environment.

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![VS Code Setup Screenshot](<img width="1846" height="996" alt="image" src="https://github.com/user-attachments/assets/9416d93d-1e6a-4d96-83bf-fba645f9609c" />

)


Replace `task-5-vscode.png` with your actual screenshot file name.

---

# 🔗 Task 6: Publish Your Assignment as a LinkedIn Post

## Objective

Publishing on LinkedIn helps you:

* Build your professional online presence
* Reinforce your learning
* Document your DevOps journey publicly

## Your Task

Summarize your answers from Tasks 1–5 into a LinkedIn post.

Clearly structure your post into the following sections:

* ChatGPT
* Internet & Networking
* App Architecture
* DNS
* VS Code Setup

Use the credit note that matches your track:

Add the following credit note at the end of your post **(If you are DMI Cohort 3 student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 3 — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=cohort3**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Add the following credit note at the end of your post **(If you are DMI Self-paced track student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=self-paced**

Add the following credit note at the end of your post **(If you are DMI Campus student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Campus — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=campus**

**Tag [Pravin Mishra](https://www.linkedin.com/in/pravin-mishra-aws-trainer/) in your LinkedIn post, then tag Lead Co-Mentor — [Anjana Muthunayake](https://www.linkedin.com/in/anjana-muthunayake/).**

Hashtags:

#DMIByPravinMishra #AgenticAI #DevOps

Replace `YOUR-GITHUB-USERNAME` with your GitHub username — that link is your public DMI progress page (your graded badge page).
---

## LinkedIn Post URL

Paste your LinkedIn post URL here:

```text
https://www.linkedin.com/posts/preethi-paswan-936338437_dmibypravinmishra-agenticai-devop-share-7505835320337432576-iCOL/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAG43wjoBaOXJzGbgjU7z0g8GDP9Pfyg3mHQ
```

---

## LinkedIn Post Backup Copy

Paste the full text of your LinkedIn post here:

LinkedIn post backup copy:
I’m excited to share what I have learned so far in my DevOps journey. These early topics helped me understand how AI tools, networking, application design, and development environments work together in real-world software projects.
ChatGPT
I learned that ChatGPT can be a useful learning partner for explaining technical topics, brainstorming ideas, improving writing, and solving problems step by step. It is most effective when I ask clear questions and verify important information rather than relying on it blindly.
Internet & Networking
I learned that packet switching divides data into small packets that travel through a network and are reassembled at the destination. Every device uses an IP address for identification. TCP/IP provides the rules for reliable communication, while HTTP and HTTPS enable browsers and servers to exchange website data securely.
App Architecture
I compared two-tier and three-tier applications. In a two-tier architecture, the frontend communicates directly with the database. In a three-tier architecture, the backend sits between the frontend and database, handling business logic, security, APIs, and data processing. This structure makes applications easier to maintain and scale.
DNS
DNS works like the internet’s phonebook. It converts a human-readable domain name, such as a website URL, into an IP address that computers can use to locate the correct server.
VS Code Setup
I set up VS Code as my development environment and learned how it helps developers write, organize, edit, and manage project files. Extensions, the terminal, and version-control integration make development more efficient.
special thanks to Pravin Mishra and Lead Co-Mentor Anjana Muthunayake
P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 3 — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/preethikumari934-TCTK.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=cohort3
#DMIByPravinMishra #AgenticAI #DevOp

---

# Reflection – Week 0

### What did you find easy?

I found it easy to understand the basic concepts of internet networking, such as IP addresses, packet switching, and the purpose of HTTP/HTTPS. Creating simple application architecture diagrams was also clear once I understood the role of each layer.
---

### What was difficult?

The most difficult part was connecting all the concepts together and explaining them in simple words. I also found it challenging to remember the differences between two-tier and three-tier architecture and to organize my work clearly.
---

### What will you improve next week?

Next week, I will practise explaining technical concepts more confidently and create more diagrams to strengthen my understanding. I will also spend more time using VS Code and learning how backend services, databases, and DNS work together.

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.


## 📌 Resources

- 🌐 **DMI Official Website:** https://dmi.pravinmishra.com?utm_source=github&utm_medium=readme  
- 🎓 **University:** https://university.pravinmishra.com?utm_source=github&utm_medium=readme  
- 💬 **Discord Community:** https://discord.pravinmishra.com?utm_source=github&utm_medium=readme  
- 📝 **Blog:** https://dmi.pravinmishra.com/blog?utm_source=github&utm_medium=readme  
- ▶️ **YouTube Playlist (DMI Cohort 3):** https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 **Pravin Mishra (LinkedIn):** https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 **CloudAdvisory (LinkedIn):** https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) — Agentic AI Track*
