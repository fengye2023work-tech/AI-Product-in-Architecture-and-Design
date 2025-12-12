## AI in Architecture and Design - Natural Language Modeling

A lightweight Design–Modeling Copilot that converts simple and vague prompts into precise geometric constrains and automated model updates. The prototype eliminates repetitive manual revisions and enables rapid, controlled design iterations directly from natural language input.

## Features
- Converts simple or vague natural-language prompts into precise parametric inputs.
- Automatically regenerates 3D geometry without manual adjustments or slider tuning.
- Integrates LLM-based semantic parsing with Grasshopper logic to predict parameter updates.
- Provides a design copilot experience for architects and non-technical stakeholders, enabling controlled, low-latency model revisions from unstructured text.

## Architecture Overview
High-level explanation of workflow:
AI API → GH Python → Grasshopper → Output

<img width="890" height="474" alt="Script overview" src="https://github.com/user-attachments/assets/755ffa93-f8ea-4c60-9819-db09fc37b82a" />

## Demo
https://www.dropbox.com/scl/fi/uxrlyprjt7dnmf6r400k8/NL-Modeling.mp4?rlkey=naim21123gm8hgvvhrcu60pfa&st=60miqezd&dl=0

<img width="530" height="720" alt="demo_screenshot" src="https://github.com/user-attachments/assets/b1adf1d8-de2e-44d0-8cb4-572ba59efeba" />

## Tech Stack
Python | Grasshopper | Rhino | AI API | Git | Others

## How It Works (High Level)
1. User inputs natural language or unstructured prompt
2. LLM interprets intent and predicts parameter updates. 
3. Python maps parameters  
4. Grasshopper updates geometry using the new parameters.
5. Output delivered as model/image

## Purpose of This Repo
Prototype for AI Application PM / AI Solution Architect portfolio.  
Core code and IP are not included in this public repo.
If you are interested in hearing more about this idea, or turn it into a running business, welcome to contact me!

## Author
FENG YE 
feng.ye.2023.work@gmail.com
feng@arbitraryaesthetics.com
