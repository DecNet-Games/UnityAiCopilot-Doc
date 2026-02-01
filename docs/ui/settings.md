---
layout: default
title: Settings Window
parent: UI Reference
nav_order: 3
---

# Settings Window
**Location**: `Tools > Unity AI CoPilot > Settings`

## Credential Vault
Securely stores your API keys. Select a provider and paste the key. 
Keys are stored in `EditorPrefs` on your local machine.

## Architecture Settings
*   **Bad References**: Define regex patterns for disallowed folder references (e.g., `Context.*` cannot reference `UI.*`).
*   **Ignored Folders**: Paths to skip during scanning (e.g., `ThirdParty/`).
