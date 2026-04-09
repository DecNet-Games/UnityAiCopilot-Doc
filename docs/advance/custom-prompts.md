---
layout: default
title: Custom Prompts
parent: Advanced Setup
nav_order: 1
permalink: /docs/advance/custom-prompts
---

# ✍️ Customizing Brody's Personality

Want Brody to code in a specific style? Or follow your studio's internal naming conventions? You can edit his **Core Instructions**.

## How to Edit
1.  Navigate to `Assets/DecNetGames/BrodyAI/Editor/Core/PromptBuilder.cs`.
2.  Locate the section titled `SystemMessage`.
3.  Add your own rules.

### Example Custom Rule:
> "Always use underscores for private fields (e.g., `_myVariable`) and never use `var` for simple types."

---

## 📸 Technical View
![Editing Prompts](https://via.placeholder.com/700x400/1a1a1a/ffffff?text=Visual+of+PromptBuilder.cs+Code+Structure)
*Directly influence Brody's decision-making logic.*
