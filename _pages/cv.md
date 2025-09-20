---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.A. Computer Science, UC Berkeley — Expected 2027

Work & Research Experience
======
* **Undergraduate Research Assistant, Sky Lab** — UC Berkeley
  * July 2025 – Present
  * Conducting research on multi-agent and AI systems, focusing on large language model function calling ability.
  * Added local inference support for open-source models like Qwen3 and Kimi-K2-Instruct for the Gorilla LLM benchmarking framework.
  * Designed multimodal evaluation tasks and reasoning-trace datasets to stress-test model performance.
  * Exploring memory management for large ML systems, specifically policies to optimize KV-cache hit rates.

* **Course Staff, CS161 – Computer Security** — UC Berkeley EECS
  * Summer 2025 – Present
  * Lead weekly discussions and office hours for 400+ students, covering memory safety, cryptographic protocols, and secure system design.
  * Debug student code, review security implementations, and grade assignments.

* **Software Engineer, Admittere – AI-Powered College Application Assistant** — Berkeley, CA
  * June 2025 – Present
  * Launched an AI assistant guiding students through Common App essays via a retrieval-augmented generation (RAG) pipeline.
  * Designed a multi-tenant Supabase backend with pgvector similarity search and serverless functions for sub-100ms retrieval.
  * Built a React + TypeScript front-end with OAuth authentication and Stripe billing.

* **Software Engineer, realstudio.ai** — Berkeley, CA
  * Jan 2024 – Aug 2024
  * Engineered a full-stack AI image generation platform with adjustable resolution and prompt control, scaling to 1,000+ concurrent users.
  * Integrated LemonSqueezy for subscription billing and automated plan management.
  * Fine-tuned Stable Diffusion v2 with DPO for realism and implemented Docker-based CI/CD pipelines.

Projects
======
* **In-Simulated Self-Driving Car Model** — Keras, CV (Mar–May 2025)
  * Built a CNN to predict steering angles from camera images; applied normalization, cropping, and dropout, reducing MSE by 20%.

* **Multi-Camera People Counting & Occupancy Analytics** — OpenCV, YOLO, Flask (Mar–May 2025)
  * Designed a real-time system with YOLO + SORT to count people via ID tracking and line-crossing; added ROI cropping, perspective correction, and smoothing to avoid double counts.

* **Secure File Sharing System** — Go, Cryptography (Feb–Apr 2025)
  * Implemented hybrid encryption with MACs and digital signatures, ensuring authenticated access and resilience against database compromise.

* **RISC-V CPU Simulator** — Logisim (Aug–Dec 2024)
  * Designed a pipelined simulator with hazard detection and forwarding for registers, memory, and control flow.

Technical Skills
======
* **Programming Languages**: Python, C, C++, Go, Java, TypeScript, SQL
* **Machine Learning & AI**: PyTorch, TensorFlow, Keras, Scikit-learn, CUDA programming, RAG pipelines, multimodal dataset design, Stable Diffusion fine-tuning
* **Systems & Tools**: Docker, Supabase (pgvector, RLS), PostgreSQL, Flask, NumPy, Pandas, React, Tailwind, CI/CD pipelines

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
