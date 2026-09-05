# Interview Question Creator

An LLM-powered application for generating interview questions from uploaded source documents. This project is a compact example of a document-to-question workflow: ingest a PDF, prepare text context, send it through an LLM prompt, and expose the result through a simple web interface.

## What It Demonstrates

- Document ingestion from PDF sources
- Prompt design for structured interview-question generation
- Python application packaging with `setup.py`
- Basic web interface for interacting with the model workflow
- A small, readable foundation for extending into a fuller RAG-style interview-preparation tool

## Repository Structure

| Path | Purpose |
| --- | --- |
| `app.py` | Main application entry point |
| `src/helper.py` | Helper utilities for loading and preparing document content |
| `src/prompt.py` | Prompt template and generation instructions |
| `templates/index.html` | Web UI template |
| `data/` | Sample PDF inputs |
| `research/` | Experiment notes and notebook work |

## Tech Stack

- Python
- Flask-style web application flow
- Public LLM API integration
- PDF/document processing

## Setup

```bash
conda create -n interview python=3.10 -y
conda activate interview
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

## Portfolio Notes

This is a smaller learning/project repository. For deeper examples of production-oriented GenAI architecture, see:

- [ResearcherAI](https://github.com/chan4kum/ResearcherAI)
- [ScholarOps-AI](https://github.com/chan4kum/ScholarOps-AI)
- [aiorg-local-ai-engineering-org](https://github.com/chan4kum/aiorg-local-ai-engineering-org)
