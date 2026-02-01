---
layout: default
title: Specialized Agents
parent: Features
nav_order: 1
permalink: /docs/features/agents
---

# Specialized Agents

Unity AI CoPilot isn't just one bot. It's a team of specialized agents, each fine-tuned for a specific task. To switch agents, navigate to **Tool Settings > Specialized Agents**.

---

## 🏗️ Architect Agent
**Role:** High-level system design and file structure planning.
*   **Best For:** "Plan a new Inventory System", "Create a folder structure for a racing game".
*   **Behavior:** Focuses on pure C# interfaces, abstract classes, and project hierarchy. Does not write implementation details.

## 🛠️ AutoFix Agent
**Role:** The bug hunter.
*   **Best For:** Fixing console errors instantly.
*   **Behavior:** When you click "Fix Issue" in the Console, search for the error, analyze the stack trace, and apply a patch.
*   **Capabilities:**
    *   Reads the compile error.
    *   Reads the relevant script file.
    *   Proposes a `diff` to fix the issue.

## 🛡️ Code Safety Agent
**Role:** Quality Assurance and Security.
*   **Best For:** "Review this script for bugs", "Optimize this loop".
*   **Behavior:** strictly analyzes code for:
    *   Infinite loops.
    *   Memory leaks.
    *   Deprecated Unity APIs.
    *   Inefficient `GetComponent` or `FindObjectOfType` calls in `Update`.

## 📜 Scene Agent
**Role:** Hierarchy and GameObject manipulation.
*   **Best For:** "Create a cube and place it at (0,0,0)", "Find all enemies and make them red".
*   **Behavior:** Generates **Editor Scripts** that execute immediately to modify the Scene. It does NOT generate runtime scripts for this agent.

---

## Configuring Agents
You can assign different LLMs to different agents.
*   **Example:** Use expensive **GPT-4o** for the *Architect* (needs high logic), but cheap **GPT-4o-mini** for the *AutoFixer* (needs speed).
