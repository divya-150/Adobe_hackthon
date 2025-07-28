# 🧠 Adobe India Hackathon 2025 – Round 1B

This repository contains the solution for **Round 1B** of the **Adobe India Hackathon 2025**. The objective is to analyze PDF documents using a defined **persona** and **job-to-be-done**, and generate a structured JSON output containing:

- Metadata
- Ranked relevant sections
- Subsection analysis

---

## 🚀 Features

- Extracts headings and text from PDF documents
- Ranks sections based on TF-IDF relevance to the persona/job
- Performs fine-grained paragraph-level analysis
- Outputs a structured JSON result

---
## 📂 Project Structure
```
Adobe_hackthon/
├── app/
│ ├── main.py # Entry script to run processing
│ ├── io_utils.py # I/O helpers for JSON and directories
│ ├── heading_detection.py # Extracts structured sections from PDFs
│ ├── ranker.py # TF-IDF ranking logic for sections and subsections
├── input/
│ └── challenge1/
│ ├── persona_job.json # Persona + Job to be done
│ ├── *.pdf # PDFs for Challenge 1
│ └── challenge2/
│ └── challenge3/
├── output/
│ └── challenge1/
│ └── challenge2/
│ └── challenge3/
├── Dockerfile # Docker image definition
├── requirements.txt # Python dependencies
└── README.md # This file
```
## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/divya-150/Adobe_hackthon.git
cd Adobe_hackthon
