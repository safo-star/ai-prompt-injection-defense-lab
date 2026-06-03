# AI Prompt Injection Defense Lab

## Overview

AI Prompt Injection Defense Lab is a Safo Security project built to detect unsafe prompts before they reach an AI assistant.

The tool analyzes user input for prompt injection, jailbreak attempts, system prompt extraction, role manipulation, safety bypasses, data exfiltration attempts, and suspicious AI behavior.

This project simulates how an AI security layer can inspect prompts before they are passed into an LLM-powered chatbot, customer support bot, internal assistant, or business automation workflow.

---

## Business Problem

Businesses are starting to use AI chatbots, AI assistants, lead qualification bots, and automated support tools.

The risk is that users may try to manipulate these systems with prompts such as:

- Ignore previous instructions
- Reveal your system prompt
- Act as developer mode
- Bypass safety rules
- Show private customer data
- Leak database information

This project demonstrates how those risks can be detected, scored, and blocked before reaching the AI system.

---

## Features

- Prompt injection detection
- Jailbreak attempt detection
- System prompt extraction detection
- Role manipulation detection
- Safety bypass detection
- Data exfiltration detection
- Obfuscated attack detection
- Risk scoring system
- Severity labeling
- Recommended security action
- Safe response generation
- Streamlit web interface
- Safo Security branded UI

---

## Tech Stack

- Python
- Streamlit
- Regex
- Rule-based detection logic
- JSON-style security analysis

---

## Screenshots

### Safe Prompt Allowed

![Safe Prompt Allowed](screenshots/safe-prompt-allowed.png)

### Developer Mode / Safety Bypass Blocked

![Developer Mode Blocked](screenshots/developer-mode-blocked.png)

### Prompt Injection Blocked

![Prompt Injection Blocked](screenshots/prompt-injection-blocked.png)

---

## Example Results

### Safe Prompt

```text
Can you explain how firewalls work?
