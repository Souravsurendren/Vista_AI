# TNEA AI Guidance System using Pre-trained LLMs

An intelligent chatbot system built to assist students with Tamil Nadu Engineering Admissions (TNEA) using Large Language Models (LLMs). This project leverages pre-trained language models to answer queries related to the counseling process, eligibility, cutoffs, college choices, and more.

---

## Table of Contents

- Overview
- Features
- Technologies Used
- Architecture
- How It Works
- Future Enhancements

---

## Overview

TNEA (Tamil Nadu Engineering Admissions) is a centralized system for undergraduate engineering admissions in Tamil Nadu. The counseling process involves a lot of information regarding:

- Rank lists
- Cut-offs for colleges/departments
- Community-based reservations
- Choice filling & counseling rounds

This project simplifies the student experience by providing a **chat-based guidance system** powered by **pre-trained LLMs (like OpenAI GPT, Meta LLaMA, etc.)** to answer all admission-related queries naturally and interactively.

---

## Features

- Natural Language Question-Answering
- Explains counseling rounds, quotas, and processes
- College & department recommendation (based on input rank/community)
- Works with pre-loaded cutoff data (optional enhancement)
- Chat interface (via CLI or Gradio/Streamlit)

---

## Technologies Used

- **Python**
- **Langchain / Transformers**
- **OpenAI API / Together.ai (Meta LLaMA models)**
- **Gradio / Streamlit** – UI
- **Pandas** – for processing cutoff data
- **FAISS / ChromaDB** (optional) – for retrieval

---
> Optionally includes a **retrieval system (RAG)** for cutoff-related questions if tabular cutoff data is integrated.

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/tnea-llm-assistant.git
cd tnea-llm-assistant

