---
layout: default
title: Provider Setup
nav_order: 3
permalink: /docs/providers
---

# Supported AI Providers & Setup
{: .no_toc }

Configure your "Brain". You can mix and match providers for different tasks.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 🚀 OpenRouter (Recommended)
Access every model (GPT-4, Claude 3, Llama 3) with one key. Cheapest and most flexible.
1.  **Get Key**: Sign up at [OpenRouter.ai](https://openrouter.ai/) -> Keys -> Create Key.
2.  **Unity Setup**:
    *   **Provider**: Select `OpenRouter`.
    *   **Key**: Paste the `sk-or-...` key.
    *   **Model**: Use any model ID (e.g., `anthropic/claude-3-5-sonnet`, `mistralai/mistral-large`).

---

## 🟢 OpenAI
Official access to GPT-4o, GPT-4-Turbo, and GPT-3.5.
1.  **Get Key**: [platform.openai.com/api-keys](https://platform.openai.com/api-keys).
2.  **Unity Setup**:
    *   **Provider**: `OpenAI`.
    *   **Key**: Paste `sk-...`.
    *   **Model**: `gpt-4o` or `gpt-3.5-turbo`.
> **Note**: Requires a paid OpenAI API account (distinct from ChatGPT Plus).

---

## 🟣 Anthropic (Claude)
Best for large context and complex coding.
1.  **Get Key**: [console.anthropic.com](https://console.anthropic.com/).
2.  **Unity Setup**:
    *   **Provider**: `Claude`.
    *   **Key**: `sk-ant-...`.
    *   **Model**: `claude-3-5-sonnet-20240620`.

---

## 🔵 Google Gemini
Fast and often free (tier dependent).
1.  **Get Key**: [aistudio.google.com](https://aistudio.google.com/).
2.  **Unity Setup**:
    *   **Provider**: `Gemini`.
    *   **Key**: Paste your key.
    *   **Model**: `gemini-1.5-pro` or `gemini-1.5-flash`.

---

## 🏠 Ollama (Local / Free)
Run AI on your own GPU. No internet required.
1.  **Install**: Download from [ollama.com](https://ollama.com/).
2.  **Run**: Terminal command `ollama serve`.
3.  **Pull Model**: Terminal command `ollama run llama3`.
4.  **Unity Setup**:
    *   **Provider**: `Ollama`.
    *   **URL**: Default is `http://localhost:11434`.
    *   **Model**: Type the name exactly (e.g., `llama3`).

---

## 🐳 DeepSeek
High performance coding model, very cheap.
1.  **Get Key**: [platform.deepseek.com](https://platform.deepseek.com/).
2.  **Unity Setup**:
    *   **Provider**: `DeepSeek`.
    *   **Key**: Paste key.
    *   **Model**: `deepseek-coder` or `deepseek-chat`.
