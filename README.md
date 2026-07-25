# 🤖 AI Research Assistant using n8n & Large Language Models

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--5%20Mini-10A37F?style=for-the-badge&logo=openai&logoColor=white)
![arXiv](https://img.shields.io/badge/arXiv-API-B31B1B?style=for-the-badge)
![OpenAlex](https://img.shields.io/badge/OpenAlex-API-2563EB?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

An AI-powered Research Assistant that automates literature discovery, paper summarization, research insight generation, and recommendation using **n8n**, **GPT-5 Mini**, **arXiv API**, **OpenAlex API**, **Google Sheets**, and **Gmail**.

---

# 📖 Project Overview

Academic literature review is one of the most time-consuming phases of research. Researchers spend hours searching papers, reading abstracts, extracting key findings, and identifying research gaps.

This project automates the complete literature review workflow using workflow automation and Large Language Models.

The AI Research Assistant performs:

- 🔍 Automatic research paper discovery
- 🤖 AI-powered paper summarization
- 📚 Related paper recommendation
- 💡 Cross-paper research insight generation
- 📊 Google Sheets storage
- 📧 Automated email report delivery

---

# 🚀 Features

- Automated research paper search
- AI-powered paper summarization
- Research recommendation engine
- Cross-paper insight generation
- Google Sheets integration
- Gmail integration
- End-to-end workflow automation
- Modular multi-workflow architecture

---

# 🏗️ System Architecture

```text
                User Form
                    │
                    ▼
      Workflow 1 – Research Paper Discovery
                    │
         ┌──────────┴──────────┐
         ▼                     ▼
     arXiv API           Workflow 2
         │               Recommendation
         ▼                     │
 GPT-5 Mini Analysis      OpenAlex API
         │                     │
         ▼                     ▼
 Google Sheets          GPT Recommendation
         │
         ▼
      Aggregate
         │
         ▼
 Workflow 3 – Research Insight Generator
         │
         ▼
 GPT-5 Mini Final Report
         │
         ▼
 Gmail Delivery
```

---

# 🔄 Workflow Overview

### Workflow 01 – Research Paper Discovery & AI Analysis

- Accepts user research requests through an n8n form
- Retrieves research papers using the arXiv API
- Generates AI summaries using GPT-5 Mini
- Stores results in Google Sheets
- Invokes the recommendation and insight workflows

---

### Workflow 02 – AI Related Paper Recommendation Engine

- Searches OpenAlex
- Evaluates paper relevance
- Generates AI recommendations
- Produces relevance scores and recommendations

---

### Workflow 03 – Research Insight Generator

- Combines analyzed papers
- Identifies research themes
- Detects trends and research gaps
- Generates the final research insights

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
| Gmail | Report Delivery |
| HTTP Request | API Communication |
| XML Parser | XML Processing |

---

# 📂 Repository Structure

```text
AI-Research-Assistant-n8n/
│
├── assets/
├── docs/
├── presentation/
├── report/
├── screenshots/
├── workflows/
├── LICENSE
└── README.md
```

---

# 📸 Project Screenshots

## User Input Form

![User Form](screenshots/user-form.jpeg)

---

## Workflow 01

![Workflow 01](screenshots/workflow-01.jpeg)

---

## Workflow 02

![Workflow 02](screenshots/workflow-02.jpeg)

---

## Workflow 03

![Workflow 03](screenshots/workflow-03.jpeg)

---

## Google Sheets Output

![Google Sheets](screenshots/google-sheets-output.jpeg)

---

## Email Report

![Email Report](screenshots/gmail-report.jpeg)

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

### 2. Import Workflows

Import all three workflow JSON files into n8n.

### 3. Configure Credentials

Configure:

- OpenAI
- Gmail
- Google Sheets

### 4. Activate Workflows

Activate all workflows.

### 5. Run

Open the n8n Form and submit your research topic.

---

# 🎯 Sample Input

**Research Topic**

Generative AI in Healthcare

**Keywords**

LLMs, Medical Diagnosis, Clinical Decision Support, Healthcare AI

**Research Goal**

Analyze recent developments, summarize research findings, identify trends, and recommend future research directions.

---

# 🔮 Future Scope

- Retrieval-Augmented Generation (RAG)
- Vector Database Integration
- IEEE Xplore Integration
- Springer Integration
- Semantic Search
- Citation Generator
- PDF Report Generation
- Multi-Agent AI System

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

⭐ If you found this project interesting, feel free to **Star** the repository!
