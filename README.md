# Bryan Londres

**AI + Cybersecurity Engineer** | CompTIA Security+ | Bachelor's, Computer Science (FIU) | Associate's, Computer Engineering (MDC)

I build systems that sit at the intersection of AI and cybersecurity. My current focus is automated vulnerability verification, using LLMs, static analysis, and hardened container execution to determine whether security findings are exploitable or theoretical. I care about engineering discipline as much as output: clean module boundaries, deterministic pipelines, and sandboxing that doesn't cut corners.

I also work across the full abstraction stack, from GPU-level C++20 and OpenGL shader programming to enterprise CI/CD and cloud infrastructure.

---

### Flagship Projects

**[ShieldClaw](https://github.com/blondres04/shieldclaw)** | Evidence-Backed SQL Injection Validation

A Python CLI MVP that validates Semgrep `CWE-89` SQL injection findings against owned Docker Compose apps. It scores findings with an LLM, requires human approval before detonation, generates one approved proof-of-concept, runs it inside a hardened ephemeral Docker attacker container (read-only filesystem, blocked egress, seccomp, strict memory/PID limits), and only reports `TRUE_POSITIVE` when exit-code evidence is corroborated by Tier-2 observer evidence. Non-SQLi findings remain visible but are deferred by default. Supports OpenAI/Ollama providers, SQLite-backed scan resumability, and JSON/Markdown reports, with SARIF available as a secondary export.

**[In Silico Neural Dynamics Simulator](https://github.com/blondon1/Procedural-Neuron-OpenGL)** | GPU-Accelerated Computational Neuroscience Engine

A 1,000-node neural network simulation built from scratch in C++20 and OpenGL. Implements Leaky Integrate-and-Fire physics decoupled from the render loop via a fixed-step accumulator, procedural graph topology using rejection sampling for organic soma placement, O(N²) Euclidean synaptic wiring, and custom GLSL fragment shaders with SDF blending for membrane rendering. Designed as an interactive prototyping sandbox for observing emergent network dynamics.

---

### Technical Range

**Systems and Low-Level:** C++20, C, OpenGL/GLSL, GPU pipeline engineering, manual memory management, CMake

**AI and Security:** Python, LLM integration (Claude, OpenAI, Ollama), Docker container hardening, seccomp, Semgrep, CompTIA Security+

**Cloud and Infrastructure:** AWS, Azure DevOps, Kubernetes, Terraform, CI/CD, GitHub Actions, Jenkins, Linux, Docker

**Data and Enterprise:** SQL (Oracle, PostgreSQL, MS SQL), RESTful APIs, C#/.NET, Power Apps, RPA, ETL concepts

**Languages:** Python, Java, C++, C#, TypeScript, SQL, Bash

---

### Currently

- Tightening ShieldClaw's SQLi-only MVP validation path before broadening vulnerability coverage
- Implementing inhibitory (GABAergic) neuron types in the neural simulator to stabilize network dynamics against hyper-synchronous firing
- Completing a Mobile Applications Development College Credit Certificate at Miami Dade College (Fall 2026)

---

<sub>bryanlondres5@gmail.com · <a href="https://linkedin.com/in/bryanlondres">LinkedIn</a> · Miami, FL</sub>
