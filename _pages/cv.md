---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PhD researcher in LLM safety, agentic AI, and multilingual AI systems, with 8+ years of experience building production-scale ML and backend systems. Published at ICLR, PETS, AAAI, HyperText, COMPSAC, and ASONAM.

*A PDF version will be linked here once uploaded to `files/CV.pdf`.*

## Education

* **Ph.D. in Computer Science**, University of Texas at El Paso (UTEP) — Aug 2024 – present
  * Combined CGPA 3.92 / 4.00 (including credits transferred from SIUC)
* **M.Sc. in Computer Science**, University of Texas at El Paso (UTEP) — Aug 2024 – May 2025
  * CGPA 3.80 / 4.00
* **Ph.D. coursework in Computer Science**, Southern Illinois University Carbondale (SIUC) — Jan 2023 – Jul 2024
  * CGPA 4.00 / 4.00 (24 credits, transferred to UTEP)
* **B.Sc. in Computer Science and Engineering**, Bangladesh University of Engineering and Technology (BUET) — Mar 2009 – May 2016
  * CGPA 3.35 / 4.00

## Research Experience

**Graduate Research Assistant** — SUPREME Lab, UTEP and SIUC · Jan 2023 – present
* Advised by Dr. [Sajedul Talukder](https://www.cs.utep.edu/stalukder/)
* Research areas: generative AI, LLM safety and alignment, agentic AI safety, social network security, user data privacy
* Built a large-scale LLM safety evaluation pipeline — 1.2M+ samples across 100 languages — for multilingual jailbreak detection across the Llama, Gemma, Qwen, Mistral, GPT, Gemini, and Claude families
* Designed an AEGIS-based harm scoring framework (S1–S23) for cross-lingual safety benchmarking
* Developed benchmark frameworks and defenses for agentic LLM skill / MCP supply-chain security, including detection and mitigation of malicious tool integrations

## Work in Progress

* **Cap-PermLLM: Capability-Aware Access Control for Agentic Large Language Models** — CCS 2026
* **Detecting Privacy Drift as an Early-Warning Signal of Account Compromise and Data Exposure** — CCS 2026
* **Scalable Benchmark for Multilingual (100 Languages) Safety Alignment for Large Language Models** — NeurIPS 2026
* **Unmasking Citation Manipulation: A Feature-Driven and Transformer-Based Approach** — ICWSM 2026
* **Who Said What, When, and Where? Agentic Contextual Interpretation of Social Media Posts with Large Language Models** — ICWSM 2026

## Research Impact

* **Publications:** 20+ peer-reviewed papers across ICLR, PETS, HyperText, AAAI Symposium, COMPSAC, and ASONAM
* **Citations:** 130 · h-index 7 · i10-index 3 ([Google Scholar](https://scholar.google.com/citations?user=v7hMP8kAAAAJ&hl=en), April 2026)
* **Research areas:** LLM safety, AI alignment, social network security
* **Reviewer and PC service:** SMS Workshop (PC), ASONAM 2023–2025, ICWSM 2026 (PC), WWW 2026 (PC), PLOS ONE, SN Computer Science
* **Awards:** National Project Champion, BSCCL 2013 ($1,000); Top-56 team, U.S. DOE CyberForce Competition 2023
* **Travel grants:** $600 for paper registration, HyperText 2025

## Teaching Experience

**Graduate Teaching Assistant** — UTEP and SIUC · Spring 2024, 2025, 2026
* UTEP, Fall 2025 and Spring 2026 — Computer Networks: mentoring and grading graduate and undergraduate students
* UTEP, Spring 2025 — Automata: mentoring and grading graduate and undergraduate students
* SIUC, Spring 2024 — led machine learning / NLP labs and Linux programming; mentored and graded students

## Work Experience

**Senior Software Engineer** — BRAC IT, Anwar Group (AES), REVE Systems · Dhaka, Bangladesh · Mar 2017 – Jan 2023
*(REVE Systems 2017–2020; AES 2022–2023)*
* Built and deployed ML training, LLM fine-tuning, and large-scale evaluation pipelines bridging research and production systems
* Led backend and NLP-focused development across ERP, chatbot, and enterprise analytics systems using scalable, distributed service architectures
* Implemented end-to-end NLP pipelines for text classification, entity recognition, and language detection in Python, scikit-learn, and NLTK
* Integrated and optimized multi-platform applications (Salesforce, Shopify, WordPress) over REST APIs
* Containerized applications with Docker and deployed on Linux servers; CI/CD workflows and basic container orchestration

**Software Engineer** — Nascenia IT, Aegis Foundry · Dhaka, Bangladesh · Aug 2014 – Mar 2017
* Developed and maintained REST APIs, data pipelines, and reporting modules for restaurant, healthcare, and e-commerce clients
* Designed database schemas, user management, and payment gateway integrations for production systems
* Built reporting tools for POS systems over large databases, with a focus on query optimization and backend performance

## Technical Skills

* **LLM / generative AI:** fine-tuning, RAG, agentic LLMs, prompt injection defense, multimodal GenAI, safety and alignment, content moderation, tool-augmented LLMs, LangChain, CrewAI
* **ML/AI stack:** PyTorch, Transformers, scikit-learn, NLTK, pandas
* **Cloud and tools:** AWS, Google Colab, Anaconda, Selenium, Spring MVC, Django, React.js
* **Databases and servers:** MySQL, PostgreSQL, MongoDB, Nginx, Linux/CentOS
* **Languages:** Python, Java, JavaScript

## Publications

See the [full publication list](/publications/) or my [Google Scholar profile](https://scholar.google.com/citations?user=v7hMP8kAAAAJ&hl=en).

<ul>{% assign cv_pubs = site.publications | sort: 'date' | reverse %}{% for post in cv_pubs %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Talks and Service

<ul>{% assign cv_talks = site.talks | sort: 'date' | reverse %}{% for post in cv_talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>
