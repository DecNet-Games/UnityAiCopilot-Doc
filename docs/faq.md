---
layout: default
title: FAQ
nav_order: 10
---

# Frequently Asked Questions

## 💰 Cost & Licensing

### Is there a monthly subscription?
**No.** Unity AI CoPilot is a one-time purchase (or free if you use the open-source version). We do not charge any monthly fees.

### Do I need to pay for API keys?
Yes and No.
*   **Official APIs** (OpenAI, Anthropic) require you to pay for usage.
*   **Free Options**: You can use **OpenRouter** (free models) or **Ollama** (local models) for $0 cost.

## 🔒 Privacy & Security

### Is my code sent to a server?
*   If you use **OpenAI/Claude**: Yes, snippets of code relevant to your prompt are sent to their APIs for processing.
*   If you use **Ollama (Local)**: **No.** Your code never leaves your machine.

### Where are my API keys stored?
Keys are stored in Unity's `EditorPrefs` on your local machine. They are **never** sent to our servers.

## 🔧 Troubleshooting

### The window is blank or stuck?
Try `Tools > Unity AI CoPilot > Reset Settings` to clear corrupted configurations.

### "Connection Refused" with Ollama?
Ensure Ollama is running (`ollama serve`) and accessible at `http://localhost:11434`.
