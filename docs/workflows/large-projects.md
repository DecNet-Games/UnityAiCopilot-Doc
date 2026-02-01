---
layout: default
title: Large Projects
parent: Workflows
grand_parent: Docs
nav_order: 2
---

# Large Project Workflow

For projects with 100+ scripts and multiple team members.

## Recommended Settings
*   **Architecture Guard**: ENABLED. Essential to prevent spaghetti code.
*   **Rule Engine**: ENABLED. Enforce "Require Namespace" and "No Public Variables".

## Strategy
1.  **Weekly Scans**: Run the **CodebaseIndexer** once a week to ensure the AI has the latest context.
2.  **Modular Dev**: Use the AI to generate `asmdef` files for you to break up compilation times.
