---
layout: default
title: Auto-Fix Engine
parent: Features
nav_order: 2
permalink: /docs/features/auto-fix
---

# 🛠️ Auto-Fix Engine

One of Brody's most unique strengths is the ability to fix errors *inside* your editor without you lifting a finger.

## How it Works
When a compilation or runtime error occurs in the Unity Console, Brody provides a **"Fix with Brody"** button next to the error.

1.  **Selection**: Brody reads the exact line and file mentioned in the stack trace.
2.  **Analysis**: He looks at the surrounding code to understand *why* the error happened.
3.  **Patching**: Brody generates a `diff` and asks for your permission to apply it.

---

## 📸 Media Guide
![Auto Fix Button](https://via.placeholder.com/700x300/1a1a1a/ffffff?text=Screenshot+of+Unity+Console+with+Fix+Button)
*The seamless integration between the Unity Console and Brody AI.*

> [!TIP]
> **Pro Tip**: If the fix isn't perfect, you can hit "Retry" and give Brody more info (e.g., "The variable should be private instead").
