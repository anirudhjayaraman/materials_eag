# Agentic Applications Development

This repository tracks the progression and assignments for a comprehensive three-session series focused on modern LLM internals, transformer architecture, and building autonomous AI agents.

## Session 1: Foundations of Transformer Architecture
This session provided a deep dive into the core mechanics of transformer models. It established the foundational knowledge necessary to understand how Large Language Models process context, generate text, and the underlying architecture that powers them.

**Assignment:** 
As part of the requirements for Session 1, I developed **Anveeksha Daily Board Activity**, a curriculum generation pipeline and companion web application. It leverages structured generation (via Pydantic) to extract and transform nursery logs into daily, bite-sized whiteboard activities.
🔗 **[Anveeksha GitHub Repository](https://github.com/anirudhjayaraman/anveeksha-daily-board-activity)**

## Session 2: Modern LLM Internals and SFT Foundation II
This session explored the inner workings of modern LLMs in greater detail, focusing on Supervised Fine-Tuning (SFT) and the processes used to align base models into capable, instruction-following assistants. 

**Assignment:**
For the post-Session 2 assignment, I built **See Through The Hype**, a practical application that demonstrates the utilization of instruction-tuned models to process, structure, and analyze complex textual data and sentiment.
🔗 **[See-Through GitHub Repository](https://github.com/anirudhjayaraman/see-through)**

## Session 3: Developer Foundations and Your First Agent
Transitioning from theory to practical application, this session established developer foundations for building LLM-powered applications, culminating in the creation of a fully functional AI agent capable of writing and executing its own code.

**Code & Materials:**
The `s3_code` directory within this repository contains the progression of scripts developed during Session 3. The code covers:
- Core developer tools: Python REPL interaction (`code.interact()`) and debugging (`pdb`).
- Asynchronous programming patterns and avoiding common blocking mistakes.
- Foundational LLM integration using system prompts.
- Building a complete, autonomous agent capable of interacting with its environment, alongside variations for mock testing and local inference (Ollama).

For an interactive overview of the code developed in this session, check out the compiled notebook: `s3_code/demo_notebook.ipynb`.
