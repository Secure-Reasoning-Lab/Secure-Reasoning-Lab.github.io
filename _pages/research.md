---
permalink: /research/
title: "Research"
author_profile: true
---

SRL studies how learning systems can take on security-critical work, and how to keep those systems trustworthy when they do. The themes below organize current and recent projects.

## Cyber Reasoning Systems

We build agents and tools that find bugs and produce patches in real software.

- **PatchAgent** — a practical program-repair agent that mimics human expertise. USENIX Security 2025 (Long Talk); CSAW 2025 Technical Impact Runner-up. This line of work also supported Team 42-b3yond-bug in the DARPA AI Cyber Challenge.
- **BandFuzz** — collaborative fuzzing with reinforcement learning. First prize at the SBFT 2024 Fuzzing Competition; later used as a fuzzing component in AIxCC.
- **Locus** — agentic predicate reasoning for directed fuzzing. ICSE 2026.
- **CRC@CSAW** — the inaugural Cyber Reasoning Challenge, organized with CSAW.

Related repositories: [CRC-CSAW](https://github.com/Secure-Reasoning-Lab/CRC-CSAW), [oss-crs](https://github.com/Secure-Reasoning-Lab/oss-crs).

## Secure and Robust LLMs

We evaluate and harden language models against jailbreaks, prompt injection, and brittle alignment.

- **LLM-Fuzzer / GPTFuzzer** — automated jailbreak assessment. USENIX Security 2024; Geekcon 2023 Breakthrough Award. The tool has been adopted by major LLM providers and integrated into Microsoft Azure PyRIT.
- **PromptFuzz** — fuzzing for prompt-injection testing. IEEE TIFS 2026.
- **Mind the Inconspicuous** — hidden weaknesses in aligned LLMs' ethical boundaries. USENIX Security 2025 (Long Talk).
- **Custom GPT prompt injection** — risk assessment of 200+ custom GPTs, covered by WIRED.

## Reasoning and Explainability

We try to make model decisions more effective and more inspectable, especially on long-horizon tasks.

- **GPO** — learning from critical steps to improve LLM reasoning. NeurIPS 2025; covered by MIT Technology Review China.
- **EntroPO** — entropy-enhanced multi-turn preference optimization for coding agents. 1st on SWE-bench Lite and 5th on SWE-bench Verified among open-weight models.
- **RICE** — explanation-guided reinforcement learning. ICML 2024 Spotlight.
- **StateMask** and **AIRS** — step-level explanations for deep RL, including security applications. NeurIPS 2023; USENIX Security 2023.

## Blockchain Security

- **BlockScan** — detecting anomalies in blockchain transactions. NeurIPS 2025.
