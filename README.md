# Gabriele Vadalà

**AI Solution Architect & DevOps Engineer** — Ladispoli / Roma, Italia
[CRI.GA.MO. 3 SRLS](https://www.crigamo3.com)

Ventisei anni di infrastruttura enterprise (Linux, virtualizzazione, reti, cloud, CI/CD),
oggi spesi su un problema diverso: rendere operativi gli agenti AI su sistemi reali,
non su slide.

Quello che mi interessa davvero è il punto in cui un modello linguistico smette di
essere una demo e diventa un pezzo di infrastruttura: quando deve autenticarsi, leggere
uno stato che cambia, sbagliare in modo recuperabile e lasciare una traccia che qualcuno
può verificare dopo.

---

## Su cosa sto lavorando

**Orchestrazione agentica su HPC.** Un layer agentico sopra
[FirecREST](https://github.com/eth-cscs/firecrest), il gateway REST del
[CSCS](https://www.cscs.ch) (Swiss National Supercomputing Centre) verso i suoi
supercomputer: un wrapper MCP sull'API, una board dove l'agente riceve il lavoro come
un membro del team — con log di esecuzione e revisione umana prima del merge — e un
layer RAG locale sulla documentazione, così l'agente cerca i parametri invece di
inventarli.

L'obiettivo è che un ricercatore che non è un esperto di HPC possa sottomettere,
monitorare e diagnosticare job in linguaggio naturale. Tutto lo stack gira offline su
un portatile, per poter essere provato senza chiedere risorse a nessuno.

Sarò alla **FirecREST Hackathon — *Automating Your Workflow with FirecREST***,
ETH Zürich, 3 novembre 2026.

---

## Progetti pubblici

| | |
|---|---|
| **[rodecaster-ndi-hx](https://github.com/VadaLinux/rodecaster-ndi-hx)** | Trasforma una webcam USB su Raspberry Pi 4 in una sorgente NDI\|HX reale, usando l'encoder H.264 hardware. Reverse-engineering sull'NDI Advanced SDK con un RØDECaster Video come receiver. |
| **[framework360-mcp-server](https://github.com/VadaLinux/framework360-mcp-server)** | Server MCP + CLI sui 141 endpoint REST di Framework360: clienti, ordini, chat, marketing, report — da Claude Code o da terminale. |
| **[framework360-skill](https://github.com/VadaLinux/framework360-skill)** | La skill che insegna a un agente a usare quella CLI senza indovinare comandi e parametri. |

---

## Come lavoro

- **Un'affermazione senza fonte non è un'affermazione.** Nei miei progetti un fatto
  non verificato si scrive `[unverified]`, con nota di dove ho cercato. Vale anche —
  soprattutto — per quello che dice un LLM.
- **Un errore riportato vale più di un successo descritto.** Se un container non parte
  o una chiamata fallisce, il valore sta nel comando esatto e nell'output verbatim,
  non in una spiegazione di come sarebbe dovuta andare.
- **Il lavoro finisce in review, non in `main`.** Anche quando l'ha fatto un agente.
  Soprattutto quando l'ha fatto un agente.

---

**Stack:** Linux (openSUSE, RHEL, Debian) · Kubernetes · Terraform · Docker ·
CI/CD · MCP · RAG (LlamaIndex, Qdrant) · Python · agenti multi-runtime

📍 Ladispoli / Roma · 🔗 [crigamo3.com](https://www.crigamo3.com)
