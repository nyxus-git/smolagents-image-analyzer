# Image Analyzer 🃏🔍

This project uses Hugging Face, OpenTelemetry, Langfuse, and SmolAgents to analyze comic character images (e.g., The Joker or Wonder Woman). It fetches images from the web, processes them using a GPT-based agent, and generates descriptive results.

---

## 🧠 Technologies Used

- `PIL` (Python Imaging Library)
- `requests` for HTTP image download
- `OpenTelemetry` + `Langfuse` for trace exporting
- `smolagents` for AI agent orchestration
- `OpenAIServerModel` (GPT-4o)
- `huggingface_hub` (optional login)

---

## 📦 Installation

Install all required packages:

```bash
pip install pillow requests opentelemetry-sdk opentelemetry-exporter-otlp smolagents huggingface_hub openinference-instrumentation-smolagents
