---
layout: default
title: Specialized Agents
parent: Features
nav_order: 1
permalink: /docs/features/agents
---

# 🤖 Specialized Agents

Brody AI operates through multiple "Agents," each with a specific personality and prompt set. This specialization ensures that Brody doesn't get confused between design and debugging.

---

## 🏗️ The Architect
Built for high-level structure. The Architect focuses on SOLID principles and clean code.
*   **Skillset**: Interface design, design patterns (Singleton, Observer), file organization.
*   **Tone**: Strict, technical, and structural.

## 🛠️ The Fixer (Auto-Fix)
The most used agent. It focuses on the current state of your project.
*   **Skillset**: Analyzing error logs, finding missing references, solving compilation issues.
*   **Hook**: Deeply integrated with the Unity Console.

## ⚔️ The Security Guard
Analyzes your scripts for potential crashes or bad practices before you even hit Play.
*   **Skillset**: Detecting `GetComponent` in `Update`, infinite loops, and heavy GC allocations.

---

## 🎨 Changing Agent Models
You can mix and match.
1. Go to **Settings > Specialized Agents**.
2. Assign **Claude 3.5 Sonnet** to the *Architect* (Best for logic).
3. Assign **GPT-4o Mini** to the *Fixer* (Fast and cheap).

![Agent Selection](https://via.placeholder.com/600x350/1a1a1a/ffffff?text=Agent+Selection+Dropdown+Screenshot)
