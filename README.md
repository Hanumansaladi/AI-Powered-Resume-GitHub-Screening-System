# 🤖 AI-Powered Resume & GitHub Screening System using n8n

An AI-powered recruitment automation workflow built with **n8n**, **Groq LLM**, **GitHub API**, **Google Sheets**, and **Gmail**.

This project automates the resume screening process by analyzing candidate resumes, validating email addresses, evaluating GitHub activity, calculating AI-powered scores, storing candidate data, detecting duplicates, ranking applicants, and sending automated email notifications.

---

## 🚀 Features

- 📄 Extracts text from PDF resumes
- 📧 Validates candidate email addresses
- 👤 Extracts GitHub usernames from resumes
- 📂 Retrieves GitHub repositories using the GitHub API
- 📈 Analyzes GitHub commit history
- 🤖 Generates ATS Score using AI
- 💻 Generates GitHub Score using AI
- 🎯 Generates Confidence Score using AI
- 🏆 Calculates a Final Candidate Score
- 📊 Stores candidate information in Google Sheets
- 🔍 Detects duplicate candidate submissions
- 🥇 Calculates candidate rankings
- ✉️ Sends automated email notifications

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Groq LLM | AI-based Resume & GitHub Evaluation |
| GitHub API | Repository & Commit Analysis |
| Google Sheets API | Candidate Database |
| Gmail API | Automated Email Notifications |
| JavaScript | Custom Logic & Score Calculation |

---

## 📌 Workflow Overview

```text
Resume Submission
        │
        ▼
Extract Resume Text
        │
        ▼
Validate Email
        │
        ▼
Extract GitHub Username
        │
        ▼
Fetch GitHub Repositories
        │
        ▼
Fetch Commit History
        │
        ▼
ATS Score (AI)
        │
        ▼
GitHub Score (AI)
        │
        ▼
Confidence Score (AI)
        │
        ▼
Final Score Calculation
        │
        ▼
Check Duplicate Candidate
        │
   ┌────┴────┐
   │         │
Existing   New Candidate
   │         │
   └────┬────┘
        ▼
Update Google Sheets
        │
        ▼
Calculate Candidate Rank
        │
        ▼
Send Email Notification
```

---

## 📸 Workflow Screenshots

### Main n8n Workflow

> *(Add your workflow screenshot here after uploading it to the `images` folder.)*

```md
![Workflow](images/workflow.png)
```

### Google Sheets Output

```md
![Google Sheets](images/google-sheets.png)
```

### Email Notification

```md
![Email](images/email-notification.png)
```

---

## 📂 Repository Structure

```text
AI-Powered-Resume-GitHub-Screening-System/
│
├── workflow.json
├── README.md
└── images/
    ├── workflow.png
    ├── google-sheets.png
    └── email-notification.png
```

---

## ⚙️ Setup

1. Clone this repository.

```bash
git clone https://github.com/hanumansaladi/AI-Powered-Resume-GitHub-Screening-System.git
```

2. Import the `workflow.json` file into your n8n instance.

3. Configure the required credentials:

- GitHub API
- Groq API
- Gmail
- Google Sheets

4. Update your API keys and Sheet IDs.

5. Execute the workflow.

---

## 📚 Skills Demonstrated

- Workflow Automation
- AI Integration
- REST APIs
- GitHub API
- Resume Screening
- Prompt Engineering
- Google Sheets Automation
- Email Automation
- JavaScript
- AI-based Candidate Evaluation

---

## 🎯 Future Improvements

- Support for multiple resume formats
- Recruiter Dashboard
- Candidate Analytics
- Multi-language Resume Analysis
- AI Interview Question Generator
- Resume Recommendation Engine

---

## 👨‍💻 Author

**Hanuman Saladi**

🔗 GitHub: https://github.com/hanumansaladi

🔗 LinkedIn: https://www.linkedin.com/in/hanuman-saladi-04815a322

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!
