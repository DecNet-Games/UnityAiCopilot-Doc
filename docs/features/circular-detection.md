---
layout: default
title: Circular Detection
parent: Features
grand_parent: Docs
nav_order: 2
---

# Circular Dependency Detection
{: .no_toc }

Stop infinite compilation loops before they happen.

---

## The Problem
Circular dependencies (A references B, B references A) are a common cause of:
*   Tightly coupled code (Spaghetti Code).
*   Serialization issues in Unity.
*   Hard-to-test components.

## The Solution
The **Circular Detection Agent** runs in the background when you create or modify scripts.
If it detects a cycle:
1.  It warns you in the Console.
2.  It suggests an interface or event-based decoupling strategy.

## Key Benefits
*   **Automatic**: No manual scans needed.
*   **Proactive**: Catches issues as you type.
