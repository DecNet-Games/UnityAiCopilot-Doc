---
layout: default
title: Mobile Projects
parent: Workflows
grand_parent: Docs
nav_order: 1
---

# Mobile Project Workflow

When working on mobile, performance is key.

## Recommended Settings
*   **Model**: Use `GPT-4o` or `Sonnet` for high-quality C# code generation that allocates less garbage.
*   **Optimization Agent**: Enable "Memory Watcher" (if available) to detect texture sizes.

## Strategy
1.  Use the **OptimizationSuggester** (built-in agent) to scan your scene.
2.  Ask: *"Check this script for GC allocations"*.
3.  The agent will rewrite LINQ queries to for-loops to save frame time.
