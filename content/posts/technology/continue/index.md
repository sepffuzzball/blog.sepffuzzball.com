---
title: "Continue"
date: 2024-09-06
description: Visual Studio Code + Continue
menu:
  sidebar:
    name: Continue AI
    identifier: continue
    parent: Technology
    weight: 10
categories: ["Technology"]
authors:
  - name: sepffuzzball
    link: https://github.com/sepffuzzball
    image: https://github.com/sepffuzzball.png
theme: Toha
hero: continue.png
tags:
  - "technology"
  - "ai"
  - "llm"
draft: false
---

# Continue

## Feature Overview

The Continue extension for Visual Studio Code provides users with several features that help them complete tasks quickly and efficiently within their development environment. It includes a sidebar, autocompletion, AI-powered documentation search, a chat interface, and custom commands.

Sidebar: The Continue extension adds a sidebar to the left of your workspace that acts as a chat interface with the LLM. You can interact with the AI by typing natural language instructions or questions, and it will stream back the generated content.

Autocompletion: Continues autocompletion feature uses machine learning algorithms to suggest relevant code snippets based on the user's current code context. This helps users avoid boilerplate code and focus on writing actual logic.

AI-powered documentation search: You can use Continue to quickly search for any documentations, tutorials, articles etc., that you need within Visual Studio Code itself. It supports various programming languages like Python, Java, JavaScript, PHP etc.

Custom Commands: Continues allows users to define custom slash commands that are triggered using natural language instructions. This helps streamline your workflow and save time while performing repetitive tasks.

Edit Mode: The Edit mode feature is similar to the Share command but it doesn't generate a markdown file, instead it streams the code changes into side-by-side diff editor.

Comment Generator: You can use Continue to generate comments for highlighted code sections in your codebase. It uses the AI model to understand and provide meaningful comments that improve readability and understanding of the code.

Quick Commands: To use Quick command feature, press Ctrl + I (Windows) or Cmd + I (Mac). Type a command prefixed with /, followed by natural language instructions or questions. Continue will provide you with relevant suggestions and generate content based on your query.

## Installation

- Download the extension from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=continueai.continue)
- Open the command palette (Ctrl + Shift + P or Cmd + Shift + P), type "Continue: Install" and press Enter
- Continue will install the extension automatically
- Restart Visual Studio Code
- Install Ollama from [here](https://github.com/Ollama/ollama)
- Pull llama model by running `ollama pull llama3.1:latest`
- Pull llama model by running `ollama pull codeqwen:latest`
- pull llama model by running `ollama pull starcoder2:3b`
- pull llama model by running `ollama pull nomic-embed-text:latest`
- Configure Continue to use the codeqwen model by opening the settings.json file and adding the following line:
- `"continue.model": "codeqwen" 
- Restart Visual Studio Code

## Usage

- Open a file in VSCode
- Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac), type "Continue: Generate Comment", and press Enter
- Continue will generate comments for highlighted code sections.
- To use Quick Commands, press Ctrl + I (Windows) or Cmd + I (Mac). Type a command prefixed with /, followed by natural language instructions or questions. Continue will provide you with relevant suggestions and generate content based on your query.
- To view the generated comments in VSCode, open the "Continue" tab.

##### Comments

Nearly this entire post was written using Continue. That's pretty cool, isn't it?