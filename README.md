# 🤖 AI Research Assistant using n8n & Large Language Models

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--5%20Mini-10A37F?style=for-the-badge&logo=openai&logoColor=white)
![arXiv](https://img.shields.io/badge/arXiv-API-B31B1B?style=for-the-badge)
![OpenAlex](https://img.shields.io/badge/OpenAlex-API-2563EB?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

An AI-powered Research Assistant that automates literature discovery, paper summarization, research recommendation, and research insight generation using **n8n**, **GPT-5 Mini**, **arXiv API**, **OpenAlex API**, **Google Sheets**, and **Gmail**.

---

# 📖 Project Overview

Academic literature review is one of the most time-consuming stages of research. Researchers spend hours searching papers, reading abstracts, extracting key findings, identifying research gaps, and preparing literature surveys.

This project automates the complete literature review workflow using workflow automation and Large Language Models.

The AI Research Assistant can:

- 🔍 Discover research papers automatically
- 🤖 Generate AI-powered paper summaries
- 📚 Recommend relevant research papers
- 💡 Generate cross-paper research insights
- 📊 Store analyzed papers in Google Sheets
- 📧 Deliver a structured research report through Gmail

---

# 🚀 Features

- Automated research paper discovery
- AI-powered paper summarization
- Research recommendation engine
- Cross-paper insight generation
- Google Sheets integration
- Gmail integration
- End-to-end workflow automation
- Modular multi-workflow architecture

---
# 🎥 Project Demo

Watch the AI Research Assistant in action through the complete project demonstration.

📹 **Demo Video**

➡️ `presentation/AI_Research_Assistant_Demo.mp4`

The demo showcases:

- User input through the n8n form
- Automated research paper discovery
- AI-powered paper summarization
- Related paper recommendation
- Research insight generation
- Google Sheets integration
- Final AI-generated report delivered via Gmail

# 🏗️ Overall System Architecture

![Overall System Architecture](assets/system-architecture.png)

*Figure: Overall System Architecture of the AI Research Assistant.*

---

# 🔄 Workflow Overview

## Workflow 01 – Research Paper Discovery & AI Analysis

- Accepts user input through an n8n Form
- Searches research papers using the arXiv API
- Parses XML responses
- Generates AI summaries using GPT-5 Mini
- Stores analyzed papers in Google Sheets
- Invokes Workflow 02 and Workflow 03

---

## Workflow 02 – AI Related Paper Recommendation Engine

- Searches OpenAlex
- Retrieves related research papers
- Uses GPT-5 Mini to evaluate relevance
- Generates recommendation scores and reasoning

---

## Workflow 03 – Research Insight Generator

- Aggregates analyzed research papers
- Identifies research themes
- Detects trends and research gaps
- Generates final research insights
- Returns insights for report generation

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| GPT-5 Mini | AI Analysis |
| OpenAI | Large Language Model |
| arXiv API | Research Paper Search |
| OpenAlex API | Paper Recommendation |
| Google Sheets | Data Storage |
| Gmail | Email Delivery |
| HTTP Request | API Communication |
| XML Parser | XML Processing |

---

# 📂 Repository Structure

```text
AI-Research-Assistant-n8n/
│
├── assets/
│   └── system-architecture.png
│
├── docs/
│
├── presentation/
│   ├── AI_Research_Assistant_Presentation.pdf
│   └── AI_Research_Assistant_Presentation.pptx
│
├── report/
│   ├── AI_Research_Assistant_Report.pdf
│   └── AI_Research_Assistant_Report.docx
│
├── screenshots/
│   ├── workflow-01.jpeg
│   ├── workflow-02.jpeg
│   ├── workflow-03.jpeg
│   ├── user-form.jpeg
│   ├── google-sheets-output.jpeg
│   └── gmail-report.jpeg
│
├── workflows/
│   ├── workflow-01-research-paper-discovery.json
│   ├── workflow-02-paper-recommendation.json
│   └── workflow-03-research-insights.json
│
├── LICENSE
└── README.md
```

---

# 📸 Project Screenshots

## User Input Form

![User Form](screenshots/user-form.jpeg)

---

## Workflow 01 – Research Paper Discovery & AI Analysis

![Workflow 01](screenshots/workflow-01.jpeg)

---

## Workflow 02 – AI Related Paper Recommendation Engine

![Workflow 02](screenshots/workflow-02.jpeg)

---

## Workflow 03 – Research Insight Generator

![Workflow 03](screenshots/workflow-03.jpeg)

---

## Google Sheets Repository

![Google Sheets](screenshots/google-sheets-output.jpeg)

---

## Final Research Report via Gmail

![Gmail Report](screenshots/gmail-report.jpeg)

---

# 📄 Project Report

The complete project documentation is available in the **report** folder.

- AI_Research_Assistant_Report.pdf
- AI_Research_Assistant_Report.docx

---

# 🎞️ Presentation

The project presentation is available in the **presentation** folder.

- AI_Research_Assistant_Presentation.pdf
- AI_Research_Assistant_Presentation.pptx

---

# ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/palakgupta5060/AI-Research-Assistant-n8n.git
```

### 2. Import the Workflows

Import all three workflow JSON files into your n8n workspace.

### 3. Configure Credentials

Configure the following credentials:

- OpenAI
- Gmail
- Google Sheets

### 4. Activate the Workflows

Activate all three workflows.

### 5. Run the Application

Open the n8n Form, enter your research topic, and submit the request.

---

# 🎯 Sample Input

**Research Topic**

Generative AI in Healthcare

**Research Keywords**

LLMs, Medical Diagnosis, Clinical Decision Support, Healthcare AI

**Research Goal**

Analyze recent developments in Generative AI for healthcare, identify research trends, summarize findings, and recommend future research directions.

---

# 🔮 Future Scope

- Retrieval-Augmented Generation (RAG)
- Vector Database Integration
- IEEE Xplore Integration
- Springer Integration
- Semantic Search
- Citation Generator
- PDF Report Generation
- Multi-Agent AI Research Assistant

---

# 👩‍💻 Author

**Palak Gupta**

B.Tech – Electronics & Computer Engineering

Summer School – Generative AI & Large Language Models

Indian Institute of Technology Jammu

---

# 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub.
