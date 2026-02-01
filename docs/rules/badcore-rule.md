---
layout: default
title: BadCore Rule
parent: Rule Engine
grand_parent: Docs
nav_order: 1
---

# BadCore Rule

A predefined rule to protect your Core framework.

## Description
The **BadCore Rule** prevents feature-specific scripts from being added to the `Assets/Core` folder unless they are explicitly marked as `IsCore`.

## Why?
Keeping the Core folder clean ensures that your foundation remains reusable across multiple projects.

## Violation Fix
If the agent flags a file as violating BadCore:
1.  Move the file to a `Features/` folder.
2.  Or, if it IS core, add `// [Core]` attribute to the top of the file (if supported) or whitelist it in settings.
