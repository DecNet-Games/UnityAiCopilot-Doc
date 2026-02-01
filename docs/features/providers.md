---
layout: default
title: AI Providers
parent: Features
nav_order: 2
permalink: /docs/features/providers
---

# AI Providers

We support a wide range of AI providers to give you flexibility in cost, intelligence, and privacy.

## Supported Cloud Providers

| Provider | Setup | Best For |
|:---|:---|:---|
| **OpenAI** | API Key needed. | Standard choice. `gpt-4o` is the benchmark. |
| **Anthropic (Claude)** | API Key needed. | `claude-3-5-sonnet` is excellent for detailed coding. |
| **Google Gemini** | API Key needed. | `gemini-1.5-pro` has a massive context window (good for reading many files). |
| **DeepSeek** | API Key needed. | Affordable and extremely capable coding model (`deepseek-coder`). |

## OpenRouter (Aggregator)
**Highly Recommended.**
OpenRouter allows you to access ALL of the above (plus Meta Llama 3, Mistral, etc.) with a single API Key. 
*   It also provides access to **Free Models**.

## Local / Offline (Ollama)
For maximum privacy, you can run the AI on your own GPU using [Ollama](https://ollama.com/).

### Setup 
1.  Download Ollama.
2.  Run `ollama run mistral` (or any other model).
3.  In Unity AI CoPilot, select **Ollama** provider.
4.  Ensure `http://localhost:11434` is reachable.

> [!TIP]
> **Performance Note:** Local models depend heavily on your GPU (VRAM) and RAM. For a smooth coding experience, we recommend at least 16GB of System RAM and an NVIDIA GPU with 6GB+ VRAM.
