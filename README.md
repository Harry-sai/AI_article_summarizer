# AI Article Summarizer

**Take an article heading & link and get a concise AI-generated summary.**

This project extracts content from an article (via a URL) and uses natural language processing to produce a readable summary. It combines a scraper, summarizer logic, API endpoints, and a simple UI to make summarization fast and accessible.

---

## 🔍 Project Overview

This summarizer is designed to:

- Fetch article content from a given URL
- Extract meaningful text from HTML
- Generate a coherent, concise summary using AI-powered logic
- Provide results via CLI and API
- (Optional) Display results in a minimal UI

**Key modules**

| File | Purpose |
|------|---------|
| `scraper.py` | Fetches & parses article text from a URL |
| `summarizer.py` | Core summarization logic |
| `api.py` | Exposes HTTP API for external requests |
| `main.py` | CLI entry point / orchestrator |
| `ui.py` | Simple interactive UI (if included) |
| `summarize_article.ipynb` | Notebook for testing/experiments |

---

## 🚀 Features

✔ Extract article text from a link  
✔ Summarize long articles into short, readable outputs  
✔ Modular Python architecture  
✔ API for integration with other tools  
✔ Notebook for testing and refining summarization behavior

---

## 🛠️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/Harry-sai/AI_article_summarizer.git
cd AI_article_summarizer
