# SlowScience Copilot 🧠✍️  
_A thoughtful academic research & writing assistant_

## Overview

SlowScience Copilot is an AI-powered assistant designed to support **careful, high-quality academic work** — not just fast publication.

It helps researchers and students:

- clarify research topics and questions,
- formulate strong theses and arguments,
- plan appropriate methodologies and data strategies,
- structure papers or theses,
- and critically **stress-test** their ideas before they submit or publish.

Instead of “write my paper for me”, SlowScience Copilot aims to be a **thinking partner** that nudges you toward deeper reasoning, transparency, and intellectual honesty.

---

## Features (v0 roadmap)

- ✅ Topic & research question refiner  
- ✅ Thesis & argument helper  
- ✅ Methodology planner (social sciences, AI/ML)  
- ✅ Outline generator (articles & theses)  
- ✅ Critique / red-team mode to challenge your assumptions

> Status: early-stage personal project — evolving over time.

---

## Architecture (planned)

- **Frontend:** Streamlit web app
- **Backend:** Python modules orchestrating LLM calls
- **Agents:** small “mini-experts” for:
  - question refinement,
  - methodology planning,
  - outline generation,
  - critique.
- **Model access:** pluggable LLM client (e.g. OpenAI API, or local transformers model)
- **Storage:** local JSON / SQLite for project sessions and notes

---

## Getting started (will be expanded)

Requirements:

- Python 3.10+
- A modern LLM provider (e.g. OpenAI API key) **or** a local model

Basic setup (once you clone the repo):

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
streamlit run app/streamlit_app.py
