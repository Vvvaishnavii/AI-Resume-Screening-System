# AI-Resume-Screening-System
# 🚀 AI-Powered Resume Screening System

An automated system that evaluates candidate resumes against a job description,
produces explainable relevance scores, and maintains structured hiring insights.

## ✨ Key Highlights
- Continuous resume ingestion from Google Drive
- OCR-enabled PDF processing (handles scanned resumes)
- AI-based evaluation using Claude
- Deterministic weighted scoring (0–100)
- Explainable output (strengths, gaps, reasoning)
- Automated Google Sheets reporting

## 🏗 Architecture Overview
The system runs as a scheduled workflow and processes new resumes without manual intervention.


## 📂 Repository Contents
- `workflow/n8n-workflow.json` → n8n workflow definition
- `docs/system-design.md` → Detailed design & explanation

## 🛠 Tools & Technologies
- n8n (workflow orchestration)
- Google Drive API
- Google Sheets API
- Claude AI (Anthropic)
- OCR-based PDF text extraction

## 📌 Notes
This project focuses on system design, automation logic, and explainability rather than UI.
