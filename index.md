---
layout: default
title: Getting Started
nav_order: 1
permalink: /
---

# Getting Started with Unity AI CoPilot
{: .fs-9 }

**Unity AI CoPilot** is a professional, paid asset that brings autonomous agents into your Editor.
{: .fs-6 .fw-300 }

---

## 🚀 Overview
This is **NOT** just a chat window. This is an agentic workflow system.
It connects Unity to powerful LLMs (GPT-4, Claude, Gemini, DeepSeek) to automate:
1.  **Coding**: Writing complex scripts from scratch.
2.  **Fixing**: Auto-detecting and fixing console errors.
3.  **Architecture**: Scanning and visualizing project dependencies.
4.  **Optimization**: Reducing garbage collection and optimizing draw calls.

## 🔑 Key Concepts
Before you start, understand these three pillars:

### 1. The Brain (Providers)
You choose the brain. We support all major providers via **Tool Settings**.
*   **Best for Logic**: GPT-4o or Claude 3.5 Sonnet.
*   **Best for Speed**: Gemini 1.5 Pro.
*   **Best for Privacy**: Ollama (Local).
*   **Best for Cost**: OpenRouter / DeepSeek.

### 2. The Agents
You don't just talk to one bot. You assign tasks to specialists:
*   `Architect`: Handles project structure and graphs.
*   `CodeSafetyAnalyzer`: Protech's your project from destructive code.
*   `AutoFixGenerator`: Lives in your console to fix errors.

### 3. The Rules
You set the laws. The **Rule Engine** ensures the AI follows your coding standards (e.g., "Always use Namespaces").

---

## 📥 Installation

1.  **Import**: Drag the `UnityAICoPilot` folder into `Assets/`.
2.  **Launch**: Go to `Tools > Unity AI CoPilot > Welcome`.
3.  **Setup Keys**: Click "Setup API Keys" and enter your credentials.

[Continue to Provider Setup](./docs/providers/setup.html){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View UI Reference](./docs/ui/overview.html){: .btn .fs-5 .mb-4 .mb-md-0 }
