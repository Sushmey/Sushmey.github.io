---
title: Projects
permalink: /projects/
layout: single
classes: wide
author_profile: true
# Each project becomes a card. Use image (a screenshot in assets/portfolio/)
# or icon (a Font Awesome class, e.g. fa-robot). image wins if both are set.
projects:
  - title: "Personal AI Agent"
    icon: fa-robot
    description: "Locally hosted on Ollama, multi-tenant, with Telegram and email, 15+ tools, and human-in-the-loop purchasing."
    tags: ["Ollama", "LLM", "Agentic", "Telegram", "Google APIs"]
    url: https://proxyagent.netlify.app

  - title: "BudgetIQ"
    icon: fa-credit-card
    description: "Credit card transaction analysis tool built with Flask, Cloud Run, Vertex AI, and RabbitMQ."
    tags: ["Flask", "Cloud Run", "Vertex AI", "RabbitMQ"]
    url: https://github.com/Sushmey/nikhil-sushmey-project

  - title: "Better Call RAGs"
    icon: fa-scale-balanced
    description: "Legal Q&A over the Cambridge Law Corpus, built with LangChain."
    tags: ["LangChain", "RAG", "Python"]
    url: https://github.com/Sushmey/Better-Call-RAGs

  - title: "Long-Term Semantic Memory Engine"
    icon: fa-brain
    description: "RAG over your notes, with chunking and deduplication stored in Pinecone."
    tags: ["Pinecone", "RAG", "Embeddings"]
    url: https://github.com/Sushmey/Digital-Twin

  - title: "VibeMax"
    icon: fa-music
    description: "Vibe-based music search that takes text and image input to find music based on emotion."
    tags: ["Streamlit", "Multimodal", "Search"]
    url: https://vibemax.streamlit.app
---

A selection of projects I've worked on.

{% include portfolio-grid.html %}
