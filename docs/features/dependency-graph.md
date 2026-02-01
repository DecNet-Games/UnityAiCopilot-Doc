---
layout: default
title: Dependency Graph
parent: Features
grand_parent: Docs
nav_order: 1
---

# Dependency Graph
{: .no_toc }

Visualize your project's architecture in real-time.

---

## What is it?
The Dependency Graph scans your C# scripts and asmdef files to build a visual node-based graph of your project. It shows:
*   **Nodes**: Scripts (Classes)
*   **Edges**: References (Usage, Inheritance)

## Why use it?
*   **Refactoring**: Identify "God Classes" that are referenced by everything.
*   **Onboarding**: See how the codebase connects at a glance.
*   **Optimization**: Find unnecessary dependencies that slow down compilation.

## How to use
1.  Open `Tools > Unity AI CoPilot > Architect`.
2.  Click **"Generate Graph"**.
3.  The graph will render in the window. You can drag nodes to rearrange them.
