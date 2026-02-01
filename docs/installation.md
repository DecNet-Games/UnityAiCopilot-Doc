---
layout: default
title: Installation
nav_order: 2
parent: Docs
---

# Installation
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 📦 Requirements
*   **Unity Version**: 2021.3 (LTS) or higher.
*   **Internet Access**: Required for API calls (OpenAI, Claude, etc.).
*   **Offline Mode**: Requires locally running Ollama instance.

## 📥 Import the Package
1.  **Download** the `UnityAICoPilot` package.
2.  **Drag and Drop** the folder into your project's `Assets` directory (`Assets/UnityAICoPilot`).
3.  **Wait for Compilation**. The tool is self-contained and will not modify your existing project settings.

> [!NOTE]
> No additional dependencies or packages from the Package Manager are required. Everything is included.

## 🛠️ Post-Install Check
After importing, you should see a new menu item:
`Tools > Unity AI CoPilot`

If you do not see this menu, check the Console for compilation errors. Ensure you are not using a restricted Unity platform (e.g., restricted Console platforms) that might block Editor scripts.

[Next: Quick Start Guide](./quick-start.html){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
