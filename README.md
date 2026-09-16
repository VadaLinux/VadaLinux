# Gabriele Vadalà

**AI Solution Architect & DevOps Engineer** — Ladispoli / Rome, Italy

Twenty-six years of enterprise infrastructure — Linux, virtualisation, networking,
cloud, CI/CD — now spent on a different problem: making AI agents operational on real
systems rather than on slides.

What actually interests me is the point where a language model stops being a demo and
becomes a piece of infrastructure: when it has to authenticate, read state that changes
under it, fail recoverably, and leave a trail somebody can verify afterwards.

---

## What I'm working on

**Agentic orchestration on HPC.** An agentic layer over
[FirecREST](https://github.com/eth-cscs/firecrest), the REST gateway
[CSCS](https://www.cscs.ch) (Swiss National Supercomputing Centre) exposes to its
supercomputers: an MCP wrapper over the API, a board where the agent is assigned work
like a team member — with an execution log and a human review gate — and a local RAG
layer over the documentation, so the agent looks parameters up instead of inventing
them.

The goal is that a researcher who isn't an HPC expert can submit, monitor and diagnose
jobs in natural language. The whole stack runs offline on a laptop, so it can be tried
without asking anyone for resources.

---

## Upcoming

**FirecREST Hackathon — *Automating Your Workflow with FirecREST***
CSCS / ETH Zürich · 3 November 2026

---

## Public projects

| | |
|---|---|
| **[agentic-server-platform](https://github.com/VadaLinux/agentic-server-platform)** | Production-grade autonomous server platform: OmniRoute LLM gateway, Multica workspace orchestration, and Hermes Agent runtime in Docker & Kubernetes. Featuring token governance, semantic context compression (RTK), and Cloudflare Zero Trust ingress. |
| **[firecrest-agentic-workbench](https://github.com/VadaLinux/firecrest-agentic-workbench)** | Agentic layer over CSCS FirecREST: MCP wrapper + Multica board + DocMind RAG. Built for the FirecREST Hackathon (CSCS / ETH Zürich). |
| **[rodecaster-ndi-hx](https://github.com/VadaLinux/rodecaster-ndi-hx)** | Turns a USB webcam on a Raspberry Pi 4 into a real NDI\|HX source using the hardware H.264 encoder. Reverse-engineered against the NDI Advanced SDK with a RØDECaster Video as the receiver. |
| **[framework360-mcp-server](https://github.com/VadaLinux/framework360-mcp-server)** | MCP server + CLI over Framework360's 141 REST endpoints: clients, orders, chat, marketing, reports — from Claude Code or the terminal. |
| **[framework360-skill](https://github.com/VadaLinux/framework360-skill)** | The skill that teaches an agent to drive that CLI without guessing commands and parameters. |

---

## How I work

- **A claim without a source isn't a claim.** In my projects an unverified fact is
  written `[unverified]`, with a note of where I looked. That applies to what an LLM
  says too — especially to that.
- **A reported failure is worth more than a described success.** When a container won't
  start or a call fails, the value is in the exact command and the verbatim output, not
  in an account of how it should have gone.
- **Work lands in review, not in `main`.** Even when an agent did it. Especially when
  an agent did it.

---

**Stack:** Linux (openSUSE, RHEL, Debian) · Kubernetes · Terraform · Docker ·
CI/CD · MCP · RAG (LlamaIndex, Qdrant) · Python · multi-runtime agents

📍 Ladispoli / Rome · 🔗 [poplme.co](https://crigamo3.poplme.co/crigamo3srls/dash)
