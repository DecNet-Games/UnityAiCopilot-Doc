---
layout: default
title: Codebase Indexing
parent: Features
nav_order: 3
permalink: /docs/features/codebase-indexing
---

# 🔍 Codebase Indexing

Standard LLMs forget what happened in your other files. **Brody doesn't.**

## What is indexing?
Brody scans every `.cs` file in your project and creates a "map." This map includes:
*   Class relationships and inheritance.
*   Available namespaces.
*   Public methods and variables.

## Why it matters
When you ask: *"How do I spawn an enemy?"*, Brody knows you already have an `EnemyManager` class with a `Spawn()` method. He won't try to reinvent the wheel.

---

## 🛠️ Managing the Index
*   **Manual Update**: Go to **Tools > Brody AI > Re-index Codebase**.
*   **Auto-Sync**: By default, Brody re-scans the current file every time you save.

![Indexing Progress](https://via.placeholder.com/600x300/1a1a1a/ffffff?text=UI+showing+Brody+Indexing+Files)
*Brody mapping out your project's DNA.*
