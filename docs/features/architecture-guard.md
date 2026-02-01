---
layout: default
title: Architecture Guard
parent: Features
grand_parent: Docs
nav_order: 3
---

# Architecture Guard

Ensure your project scales without technical debt.

## Core Rules
Architecture Guard enforces strict layering in your code.
For example, in a Clean Architecture setup:
*   **Domain Layer** should not reference **UI Layer**.
*   **Core** should not reference **Feature Specifics**.

## Configuration
You can define your layers in `Tools > Unity AI CoPilot > Settings > Architecture`.
Define your "Bad References" and the guard will alert you if you violate them.
