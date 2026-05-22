# ProjectTracker
2026 Low Code Challenge

# TEAM NEXTLV – AI Project Tracker

<div align="center">

![Project Tracker Banner](https://img.shields.io/badge/AI-Powered_Project_Manager-4F46E5?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In_Development-22C55E?style=for-the-badge)
![Team](https://img.shields.io/badge/Team-NEXTLV-06B6D4?style=for-the-badge)

### *An AI-based project management system that analyzes team workflows and provides real-time feedback for efficient collaboration.*

</div>

---

# Overview

**AI Project Tracker** is an intelligent collaboration management platform designed to solve inefficiencies in team projects.

The system analyzes project progress, GitHub activity, task distribution, and team communication patterns to automatically generate AI-driven feedback and workflow optimization suggestions.

By combining:

* 📂 GitHub repository analysis
* 🤖 AI-based workflow feedback
* 📊 Team activity monitoring
* 📝 Document parsing & project tracking

our platform helps teams improve productivity, balance workloads, and reduce communication loss during collaborative development.

---

# Problem Statement

Many student and collaborative development projects suffer from:

| Problem                 | Description                                                                       |
| ----------------------- | --------------------------------------------------------------------------------- |
| Role Imbalance       | Certain members become overloaded while others contribute less.                   |
| Lack of Visibility   | Difficult to objectively understand project progress and individual contribution. |
| Communication Loss   | Important context and workflows are often lost during collaboration.              |
| Inefficient Feedback | Teams receive feedback too late to improve workflow efficiency.                   |

Our solution addresses these issues through **real-time AI analysis and automated feedback generation**.

---

# Key Features

## GitHub Repository Analysis

* Analyze commits, pull requests, and contribution history
* Track collaboration activity across repositories
* Monitor development workflow and participation levels

## AI Feedback Generation

* Generate automated project feedback using LLMs
* Provide workflow improvement suggestions
* Detect imbalance in workload distribution
* Recommend collaboration optimizations

## Document Parsing

* Parse project-related files automatically
* Extract meeting notes, requirements, and workflow information
* Support Markdown, PDF, Office documents, and more

## Team Workflow Monitoring

* Visualize project progress and task completion
* Monitor real-time collaboration status
* Analyze project momentum and productivity trends

---

# System Architecture

```text
User Input
   │
   ├── Project Information
   ├── GitHub Repository
   └── Team Documents
            │
            ▼
 ┌────────────────────┐
 │ Document Parser    │
 │ (Upstage API)      │
 └────────────────────┘
            │
            ▼
 ┌────────────────────┐
 │ GitHub Analysis    │
 │ GitHub API         │
 └────────────────────┘
            │
            ▼
 ┌────────────────────┐
 │ Solar LLM          │
 │ AI Feedback Engine │
 └────────────────────┘
            │
            ▼
 ┌────────────────────┐
 │ Project Tracker UI │
 └────────────────────┘
```

---

# AI Workflow

## 1️⃣ Data Collection

* Collect repository activity using GitHub API
* Gather project documents and workflow data
* Extract collaboration-related information

## 2️⃣ AI Analysis

* Analyze contribution patterns
* Detect workflow inefficiencies
* Evaluate project progress and team balance

## 3️⃣ Feedback Generation

* Generate AI-based recommendations
* Suggest workflow improvements
* Provide project management insights

---

# Upstage Integration

## Document Parser

Used to:

* Parse project planning documents
* Analyze meeting records and Markdown files
* Extract workflow-related information automatically

## Solar LLM

Used to:

* Generate AI-based collaboration feedback
* Analyze team contribution patterns
* Recommend workflow optimization strategies

---

# Team Members

| Name         | Role                     | Responsibilities                                                                         |
| ------------ | ------------------------ | ---------------------------------------------------------------------------------------- |
| Jeong Jieun  | Backend / AI Engineer         | Solar LLM integration, AI feedback system, prompt engineering, workflow analysis logic   |
| Lee Eunjin   | Backend / Infrastructure | GitHub API integration, Firebase setup, AI workflow design, backend architecture         |
| Jun Yusun | Frontend / UI            | Frontend development, UI/UX implementation, workflow visualization, web interface design |

---

# Expected Impact

## Data-Driven Team Optimization

Analyze collaboration patterns objectively and improve team productivity.

## Real-Time Workflow Feedback

Provide immediate AI-generated suggestions for better collaboration.

## Smarter Project Management

Reduce communication loss and improve project visibility.

## Efficient Team Collaboration

Support balanced workload distribution and optimized workflow management.

---

# Project Structure

```bash
AI-Project-Tracker/
├── frontend/
│   ├── pages/
│   ├── components/
│   └── assets/
│
├── backend/
│   ├── api/
│   ├── services/
│   └── github-analysis/
│
├── ai/
│   ├── llm/
│   ├── prompts/
│   └── feedback-engine/
│
├── docs/
└── README.md
```

---

# Future Plans

* Advanced contribution analytics
* AI-based performance dashboards
* Personalized collaboration recommendations
* Integration with additional project management tools
* Mobile-friendly workflow monitoring

---

# Demo

> Project Tracker Demo Presentation
>
> AI-powered workflow analysis and project management assistant.

---

# Tech Stack

<div align="center">

### Frontend

<img src="https://skillicons.dev/icons?i=html,css,js,react" />

### Backend

<img src="https://skillicons.dev/icons?i=nodejs,express,firebase" />

### AI & Data

<img src="https://skillicons.dev/icons?i=python" />

### Collaboration & Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode" />

</div>

---

# License

This project was developed for academic and educational purposes.

---

<div align="center">

### TEAM NEXTLV

*Building smarter collaboration with AI.*

</div>
