---
layout: home
permalink: /
title: "About Jahangir"
tagline: "CS PhD student at UT El Paso &middot; LLM Safety, Agentic AI, and Multilingual NLP"
cv: /cv/
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hi, I'm Jahangir. Welcome to my personal website! I'm a Ph.D. student in Computer Science at the **University of Texas at El Paso (UTEP)**, in the [SUPREME Lab](https://www.cs.utep.edu/stalukder/supremelab/index.html), advised by Dr. [Sajedul Talukder](https://www.cs.utep.edu/stalukder/). My research is on **LLM safety and agentic AI security** — what breaks once a language model is given tools, memory, and other agents to talk to — alongside multilingual safety evaluation and privacy in online social networks.

Recent work includes a multilingual safety benchmark of **1.2M+ unsafe prompt–response pairs across 100 languages**, and a line of attack-and-defense papers on agentic systems: implicit privilege escalation in tool use, fine-tuning collapse in guard models, compositional attacks on multi-agent pipelines, and supply-chain security for LLM skills and MCP integrations.

Before my Ph.D. I spent eight years as a software engineer in Dhaka, building ERP systems, NLP pipelines, and production ML services. I hold a B.Sc. in CSE from **BUET**.

## Highlights

<ul class="highlights">
  <li><span class="hl__date">Jun 2026</span><span>Four papers at the <strong>AAAI 2026 Summer Symposium</strong>, including <a href="/publication/hallperm"><strong>HALLPERM</strong></a> on implicit privilege escalation in LLM tool use.</span></li>
  <li><span class="hl__date">Apr 2026</span><span><a href="/publication/ai-loop"><strong>AI-in-the-Loop</strong></a> — privacy-preserving scam detection and conversational scam-baiting — published at <strong>PETS 2026</strong>.</span></li>
  <li><span class="hl__date">Jan 2026</span><span><a href="/publication/lamda"><strong>LAMDA</strong></a>, a longitudinal Android malware benchmark for concept drift, accepted to <strong>ICLR 2026</strong>.</span></li>
  <li><span class="hl__date">Sep 2025</span><span>Presented <a href="/publication/comprehensive-privacy-risk-assessment-social-networks"><strong>Comprehensive Privacy Risk Assessment in Social Networks</strong></a> at <strong>HyperText 2025</strong> and chaired Session 7 (TWEB &amp; Blue Sky).</span></li>
  <li><span class="hl__date">Jul 2025</span><span>Five papers accepted at <strong>ASONAM 2025</strong>; joined the program committees of <strong>ICWSM 2026</strong>, <strong>WWW 2026</strong>, and the <strong>SMS workshop</strong>.</span></li>
  <li><span class="hl__date">Jun 2025</span><span>Six papers accepted at <strong>NPIC&amp;HMIT 2025</strong> on securing advanced nuclear reactors with quantum-inspired and federated models.</span></li>
  <li><span class="hl__date">May 2025</span><span>Completed my <strong>M.Sc. in Computer Science</strong> at UTEP (CGPA 3.8/4.0), continuing in the Ph.D. program.</span></li>
  <li><span class="hl__date">Nov 2023</span><span>Finalist in the <strong>U.S. Department of Energy CyberForce Competition</strong> — our team placed 56th of 120+ nationally.</span></li>
  <li><span class="hl__date">2013</span><span>Won the <span class="hl__award">National Project Champion Award</span> ($1,000) at the BSCCL National Project Contest, Dhaka.</span></li>
</ul>

## Experience

**Graduate Research Assistant**, UTEP and SIUC — SUPREME Lab (Jan 2023 – present). LLM safety and alignment, agentic AI security, social network security, and user data privacy. Built the lab's multilingual jailbreak-evaluation pipeline (1.2M+ samples, 100 languages, across the Llama, Gemma, Qwen, Mistral, GPT, Gemini, and Claude families) and an AEGIS-based harm-scoring framework (S1–S23) for cross-lingual safety benchmarking.

**Graduate Teaching Assistant**, UTEP and SIUC (Spring 2024, 2025, 2026). Computer Networks and Automata at UTEP; machine learning / NLP and Linux programming labs at SIUC.

**Senior Software Engineer**, BRAC IT, Anwar Group (AES), REVE Systems — Dhaka (Mar 2017 – Jan 2023; REVE Systems 2017–2020, AES 2022–2023). Backend and NLP development across ERP, chatbot, and enterprise analytics systems; ML training and evaluation pipelines; multi-platform API integration.

**Software Engineer**, Nascenia IT and Aegis Foundry — Dhaka (Aug 2014 – Mar 2017). REST APIs, data pipelines, and reporting modules for restaurant, healthcare, and e-commerce clients.

## Research

### LLM Safety and Agentic AI Security

My current work asks where agent safety breaks once a model is given tools, memory, and other agents to talk to. [**HALLPERM**](/publication/hallperm) (AAAI 2026) shows how under-specified tool schemas let an agent escalate privileges while every guardrail still reports success. [**When Safety Geometry Collapses**](/publication/when-safety-geometry-collapses) shows a guard model losing its alignment through ordinary domain fine-tuning on entirely benign data — no adversary required. [**Semantic Intent Fragmentation**](/publication/semantic-intent-fragmentation) is a single-shot compositional attack on multi-agent orchestration, and [**Agent-Fence**](/publication/agent-fence) maps the vulnerability surface of deep research agents. I also build benchmarks and defenses for the agent skill / MCP supply chain, including detection of malicious tool integrations.

### Multilingual Safety Evaluation

I built a safety benchmark of **1.2M+ unsafe prompt–response pairs spanning 100 languages**, assembled from CatQA, MultiJail, Aegis, HateSpeech, and Toxic through translation and alignment. On top of it sits an evaluation framework using the AEGIS taxonomy with S1–S23 harm scoring, used to measure jailbreak robustness and cross-lingual safety gaps across GPT-4o, Gemini, and open-weight model families.

### Privacy and Security in Social Networks

[**Comprehensive Privacy Risk Assessment**](/publication/comprehensive-privacy-risk-assessment-social-networks) (HyperText 2025) scores user-level privacy exposure by combining profile attributes, social-graph structure, and text analysis; [**Privacy Control in Social Networks**](/publication/privacy-control-social-networks) (ASONAM 2025) turns behavioral patterns and content sensitivity into audience recommendations. Earlier work covers [identity-attack defenses](/publication/combating-identity-attacks-online-social-networks) using zero-knowledge proofs and permissioned blockchains (ASONAM 2023), [content-diversity recommendation](/publication/combating-echo-chambers-online-social-network) against echo chambers (ASONAM 2024), and [**SocialGuard**](/publication/socialguard) (COMPSAC 2024).

### Low-Resource and Multilingual NLP

Datasets and models for settings standard systems handle badly: a [Bangla emotion dataset with an extended taxonomy](/publication/bangla-emotion-detection-dataset-extended-taxonomy), [context-based hate speech detection](/publication/4whcontext), [hate speech in code-mixed social media](/publication/llms-against-digital-deviance), and [encoder–decoder and LLM architectures for low-resource emotion detection](/publication/beyond-transformers). Outside social platforms, [**LAMDA**](/publication/lamda) (ICLR 2026) is a longitudinal Android malware benchmark for studying concept drift.

### In Progress

Under submission: capability-aware access control for agentic LLMs and privacy-drift detection as an early-warning signal for account compromise (CCS 2026); a scalable multilingual safety-alignment benchmark (NeurIPS 2026); citation-manipulation detection and agentic contextual interpretation of social media posts (ICWSM 2026).

<p class="dim">I have also contributed to federated learning systems (SCALE, SAFARI, SocFedGPT, FLASH), cyber-physical security for advanced nuclear reactors at NPIC&amp;HMIT 2025, and a Springer volume on medical imaging informatics.</p>

**At a glance:** 20+ peer-reviewed papers · 130 citations · h-index 7 · i10-index 3 <span class="dim">(Google Scholar, April 2026)</span>. Full details are in my [CV](/cv/); research directions are in my [statements](/statements/).

## Selected Publications

{% include base_path %}

<div class="pub-list">
{% assign pubs = site.publications | where: "selected", true | sort: "selected_rank" %}
{% for pub in pubs %}
  <div class="pub">
    <a class="pub__title" href="{% if pub.paperurl and pub.paperurl != '' %}{{ pub.paperurl }}{% else %}{{ base_path }}{{ pub.url }}{% endif %}">{{ pub.title }}</a>
    <p class="pub__excerpt">{{ pub.excerpt | markdownify | strip_html | strip_newlines }}</p>
    <p class="pub__meta">{% if pub.venue and pub.venue != '' %}<span class="pub__venue">{{ pub.venue }}</span> &middot; {% endif %}{{ pub.date | date: "%Y" }}</p>
  </div>
{% endfor %}
</div>

<p class="pub-list__more"><a href="{{ base_path }}/publications/">Full publication list &rarr;</a></p>

## Contact

The best way to reach me is email: `{{ site.author.email }}` — happy to talk about research collaborations, agent and LLM safety evaluation, internships, or open-source work.
