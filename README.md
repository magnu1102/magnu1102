# Magnus Bjørge Almås

MSc Digitalisation Management | BSc Computer Science  
Software development, AI systems, data workflows, infrastructure, Android, and responsible digitalisation.

I build practical portfolio projects around systems that need to be understandable, testable, and useful in real workflows. My current focus is applied AI and digitalisation in public-sector and knowledge-intensive settings, especially where traceability, human review, governance, and clear data flow matter.

## Featured public projects

### [OT Lab-in-a-Box](https://github.com/magnu1102/OT-Lab-in-a-box)

A fully local Docker-based operational technology lab for learning OT/IT segmentation, monitoring, and safe failure scenarios.

- Simulated PLC/process service, HMI dashboard, historian, PostgreSQL, Prometheus, and Grafana
- Segmented Docker networks for corporate, DMZ, OT, and monitoring zones
- Safe demos for high tank alarm, service loss, historian issues, and alert visibility
- Includes screenshots, architecture docs, traffic matrix, runbook, smoke test, and CI

**Shows:** Docker networking, observability, infrastructure documentation, defensive OT/IT architecture, Python/FastAPI, React/TypeScript, PostgreSQL, Prometheus, Grafana.

### [PublicSectorRAG](https://github.com/magnu1102/PublicSectorRAG)

A source-grounded RAG assistant for open Norwegian public-sector documents.

- Ingests Markdown and text-native PDF documents into PostgreSQL/pgvector
- Retrieves source chunks with similarity scores and visible citations
- Generates grounded answers using retrieved excerpts only
- Refuses when the source material is insufficient instead of inventing answers
- Includes evaluation questions, architecture docs, limitations, and CI

**Shows:** RAG architecture, vector search, FastAPI, PostgreSQL/pgvector, OpenAI embeddings, Anthropic Claude, React/TypeScript, Docker, responsible AI design.

### [LLM Evaluation Lab](https://github.com/magnu1102/LLM_Evaluation_Lab)

A full-stack tool for evaluating LLM outputs across prompts, models, and test cases.

- YAML-defined test cases, prompt templates, and criteria
- Deterministic checks for citations, refusal behavior, required terms, and length bounds
- Optional LLM-as-judge signal, human review, run comparison, and trends
- Dataset import/export, CLI runner, asynchronous run state, and CI
- Mock provider supports local demos without API keys

**Shows:** LLM evaluation workflows, prompt regression testing, human-in-the-loop review, FastAPI, SQLAlchemy, PostgreSQL, React/TypeScript, TanStack Query, Docker.

### [ClearMyLabel](https://github.com/magnu1102/ClearMyLabel-release)

An Android OCR label-reading portfolio project distributed as signed APK releases.

- On-device OCR for product labels
- Watchlist checks and optional Open Food Facts barcode lookup
- Optional bring-your-own-key AI structuring
- Public release binaries, checksum files, privacy docs, data-flow docs, terms, and security policy
- Source code is private; the public repository documents releases and user-facing behavior

**Shows:** Android delivery workflow, OCR/product thinking, privacy-aware design, BYOK AI integration, release documentation, GitHub Releases.

## Technologies I work with

Python, Java, Kotlin, TypeScript, React, SQL, PostgreSQL, FastAPI, Docker, Linux, Git, GitHub Actions, Android, APIs, LLMs, embeddings, RAG, evaluation tooling, and documentation for technical systems.

## Current focus

- Building portfolio projects that connect software engineering with responsible digitalisation
- Improving applied AI workflows through source grounding, evaluation, and human review
- Strengthening visible project evidence through READMEs, diagrams, screenshots, demos, and repeatable setup
- Preparing project narratives for job applications, interviews, and a personal portfolio site
