---
layout: default
title: Getting Started
nav_order: 1
has_children: true
permalink: /docs
---

# Getting Started

Welcome to the **Unity AI CoPilot** documentation.
This tool is designed to be your pair programmer inside Unity. It is not just a chat window; it is an agent that understands your project.

## Core Concepts

### 🧠 The Brain (Providers)
The "Brain" is the LLM (Large Language Model) that powers the agent. We support:
*   **Cloud**: OpenAI (GPT-4), Anthropic (Claude), Google (Gemini), DeepSeek.
*   **Aggregators**: OpenRouter (access to Llama 3, Mistral, etc.).
*   **Local**: Ollama (run AI on your own GPU for privacy).

### 🕵️ The Agents
The tool uses a multi-agent architecture. Different tasks are handled by different specialists:
*   **Architect**: Plans system structures.
*   **CodeSafetyAnalyzer**: Checks code for dangerous operations before you run it.
*   **AutoFixGenerator**: Reads console errors and proposes fixes.

### 🛡️ Safety & Architecture Guard
We presume that LLMs can make mistakes. That's why we include:
*   **Architecture Guard**: Prevents circular dependencies in your scripts.
*   **Safety Checks**: Warnings if AI code tries to delete assets or modify ProjectSettings.

Start with the [Installation Guide](./installation.html) to get set up.
