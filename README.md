🚀 AI News Automation (n8n + Llama 3)
Overview

This project is an end-to-end AI automation system that:

Collects latest AI updates from multiple sources (RSS feeds)
Processes and merges content
Uses Llama 3 (via Ollama) to generate concise summaries
Sends real-time updates directly to Telegram
🔧 Tech Stack
n8n – Workflow automation
Ollama (Llama 3) – AI summarization
RSS Feeds – Data sources (HuggingFace, Reddit, etc.)
Telegram API – Notification delivery
⚙️ Workflow Architecture

Pipeline:
Schedule Trigger
RSS Feeds (Multiple Sources)
Merge Data
Data Cleaning & Formatting
AI Summarization (Llama 3)
Filtering (Relevant Updates Only)
Send to Telegram
✨ Key Features
Multi-source AI news aggregation
Automated summarization using LLMs
Real-time delivery system
Fully modular workflow (easy to extend)
Low-code + AI integration
📈 Why this project matters

This project demonstrates:

Ability to design end-to-end automation systems
Integration of AI models into real workflows
Understanding of data pipelines + orchestration
Practical use of LLMs beyond chat interfaces
🛠️ Setup Instructions
Install n8n

Install Ollama and pull Llama 3:

ollama run llama3

Import workflow JSON:

workflows/ai-news-workflow.json
Configure:
RSS URLs
Telegram Bot Token
Ollama endpoint
📬 Output Example
🚀 AI Update:
OpenAI releases new multimodal model...

Summary:
Short crisp summary generated via Llama 3.
