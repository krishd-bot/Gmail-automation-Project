# 🚀 Lead Capture Automation using n8n

A simple end-to-end workflow built with **n8n** to automate lead collection.

## 📖 Overview

This automation collects user information through an n8n form, validates the submitted email address, stores the data in Google Sheets, and sends an automatic confirmation email using Gmail.

## 🔄 Workflow

```
n8n Form
      │
      ▼
IF (Validate Email)
      │
      ▼
Google Sheets
      │
      ▼
Gmail
```

## ✨ Features

- Collect user details using an n8n Form
- Validate email before processing
- Store submissions in Google Sheets
- Send automatic confirmation emails
- No manual intervention required

## 🛠️ Technologies Used

- n8n
- Google Sheets
- Gmail
- Google OAuth

## 📂 Project Structure

```
.
├── README.md
└── workflow.json
```

## 🚀 How to Use

1. Clone this repository.

```bash
git clone https://github.com/YOUR_USERNAME/n8n-lead-capture-automation.git
```

2. Open your n8n instance.

3. Import the `workflow.json` file.

4. Configure:
   - Google Sheets credentials
   - Gmail credentials

5. Execute the workflow and test the form.

## 📚 Learning Outcomes

Through this project, I learned:

- Building workflows in n8n
- Working with triggers
- Passing data between nodes
- Using IF nodes for conditional logic
- Integrating Google Sheets
- Sending automated emails with Gmail

## 🔮 Future Improvements

- OpenAI/Gemini integration
- Slack notifications
- WhatsApp notifications
- CRM integration
- Lead scoring using AI

  #screenshot
  


## 👨‍💻 Author

**Deepak Pandey**

GitHub: https://github.com/krishd-bot

---

⭐ If you found this project useful, feel free to star the repository.
