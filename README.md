# 🤖 WhatsApp AI Customer Support & Student Intake System

<p align="center">
  <img src="assets/demo.gif" width="850" alt="WhatsApp AI Automation Demo">
</p>

<p align="center">
  <b>Automating Student Support. Qualifying Leads. Empowering Consultants.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI-AI_Agent-412991?style=for-the-badge&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/WhatsApp-Cloud_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white">
  <img src="https://img.shields.io/badge/Google_Sheets-Database-34A853?style=for-the-badge&logo=googlesheets&logoColor=white">
</p>

## 💡 About the Project

An AI-powered WhatsApp automation system designed for study abroad consultancies.

It handles student inquiries, answers study-abroad questions, collects student information, evaluates academic profiles, and automatically categorizes potential leads.

**The goal:** Reduce repetitive work for admission counselors and help them focus on serious student inquiries.

## ⚡ What Does It Automate?

<table>
<tr>
<td width="50%" align="center">

### 💬 AI Customer Support

Instant responses to student questions about universities, tuition fees, admission requirements, IELTS/PTE, and study destinations.

</td>
<td width="50%" align="center">

### 📝 Student Intake

Automatically collects personal details, education, academic results, preferred country, English proficiency, and other relevant information.

</td>
</tr>
<tr>
<td width="50%" align="center">

### 🎯 AI Profile Assessment

Automatically evaluates student profiles and categorizes them into four qualification levels.

</td>
<td width="50%" align="center">

### 🔔 Smart Notifications

Sends notifications for Good and Elite profiles through Discord, Telegram, and Gmail.

</td>
</tr>
</table>

## 🔄 How It Works

```mermaid
flowchart TD
    A(["📱 Student WhatsApp Message"]) --> B["WhatsApp Cloud API"]
    B --> C["⚙️ n8n Automation"]
    C --> D["🧠 OpenAI AI Agent"]
    D --> E{"Student Intent"}
    E -->|"General Question"| F["💬 AI Customer Support"]
    E -->|"Interested Student"| G["📝 Collect Student Details"]
    G --> H["🎯 AI Profile Assessment"]
    H --> I{"Classification"}
    I --> J["🏆 Elite"]
    I --> K["🟢 Good"]
    I --> L["🟡 Average"]
    I --> M["🔴 Weak"]
    J --> N["📊 Google Sheets"]
    K --> N
    L --> N
    M --> N
    J --> O["🔔 Team Notifications"]
    K --> O
    O --> P["Discord • Telegram • Gmail"]
```

## 🎯 Student Qualification System

Every submitted student profile is automatically evaluated and assigned to one of four categories.

```mermaid
flowchart TD
    A["Student Profile"] --> B["AI Evaluation"]
    B --> C["Profile Classification"]
    C --> D["🏆 ELITE"]
    C --> E["🟢 GOOD"]
    C --> F["🟡 AVERAGE"]
    C --> G["🔴 WEAK"]
    D --> H["Google Sheets + Team Alerts"]
    E --> H
    F --> I["Google Sheets"]
    G --> I
```

| Profile | Google Sheets | Team Notification |
|---|---|---|
| 🏆 Elite | Elite Tab | Discord, Telegram, Gmail |
| 🟢 Good | Good Tab | Discord, Telegram, Gmail |
| 🟡 Average | Average Tab | Database Update |
| 🔴 Weak | Weak Tab | Database Update |

*These are internal lead-prioritization categories, not visa approval predictions.*

## 🛠️ Technology Stack

<p align="center">
  <a href="https://n8n.io/">
    <img src="https://cdn.simpleicons.org/n8n/EA4B71" width="55" height="55" alt="n8n"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/openai.svg"
     width="55"
     height="55"
     alt="OpenAI"/>
  &nbsp;&nbsp;&nbsp;
  <a href="https://developers.facebook.com/docs/whatsapp/cloud-api">
    <img src="https://cdn.simpleicons.org/whatsapp/25D366" width="55" height="55" alt="WhatsApp Cloud API"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.google.com/sheets/about/">
    <img src="https://cdn.simpleicons.org/googlesheets/34A853" width="55" height="55" alt="Google Sheets"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.gmail.com/">
    <img src="https://cdn.simpleicons.org/gmail/EA4335" width="55" height="55" alt="Gmail"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://discord.com/">
    <img src="https://cdn.simpleicons.org/discord/5865F2" width="55" height="55" alt="Discord"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://telegram.org/">
    <img src="https://cdn.simpleicons.org/telegram/26A5E4" width="55" height="55" alt="Telegram"/>
  </a>
</p>

<p align="center">
  <sub>
    n8n &nbsp; • &nbsp; OpenAI &nbsp; • &nbsp; WhatsApp Cloud API &nbsp; • &nbsp; Google Sheets &nbsp; • &nbsp; Gmail &nbsp; • &nbsp; Discord &nbsp; • &nbsp; Telegram
  </sub>
</p>

## 🎥 Complete Workflow Demonstration

<p align="center">
  <a href="YOUR_YOUTUBE_VIDEO_URL">
    <img src="YOUR_VIDEO_THUMBNAIL_URL" width="90%" alt="Watch Complete Workflow Demonstration">
  </a>
  <br>
  <b>▶ Watch the Complete Project Demo</b>
  <br>
  <sub>See AI customer support, student intake, profile classification, database updates, and team notifications in action.</sub>
</p>

## 🚀 Business Value

- Reduced repetitive inquiries handled manually by counselors.
- Automated student information collection.
- Organized student profiles in separate categories.
- Faster identification of promising leads.
- Centralized student records and internal notifications.

## 👨‍💻 Developed By

**Moiz Qadeer**  
AI Automation Engineer | n8n Workflow Developer

Building intelligent automation systems that solve real business problems.

💼 [LinkedIn](https://www.linkedin.com/in/moizqadeer/)  

---

<p align="center">
  <b>Built using n8n, OpenAI & WhatsApp Cloud API</b>
</p>
