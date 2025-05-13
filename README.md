# n8n Template Guide

This repository contains reusable n8n workflow templates and configuration examples. It's intended to help automate tasks by providing plug-and-play workflows, especially for integrating APIs, handling webhooks, and automating email/notification flows.

## 🔧 How to Use

1. Clone or download this repository.
2. Open [n8n](https://n8n.io/) (self-hosted or cloud).
3. Go to **Workflows > Import** and paste the JSON template from the `.json` files here.
4. Customize nodes like Webhook, Email, HTTP, etc. with your credentials.

## 📂 Contents

- `templates/`: JSON files for each workflow.
- `docs/`: Notes and step-by-step guides (coming soon).

## 📌 Requirements

- n8n installed locally or via Docker
- Your own API keys (for Email, Telegram, etc.)

## 🚀 Example Templates

- Telegram bot alert workflow
- AI summarizer via HuggingFace
- Gmail + Google Drive automation

## 🧾 License

See [LICENSE](LICENSE) for more info.
