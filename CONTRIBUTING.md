# Contributing to Agent Racing League

First off — thank you for being here early. This project is in founding phase, which means **your contributions shape the architecture, not just the code.**

---

## 🚦 Before You Start

1. Read the [README](README.md) to understand the vision
2. Check [open issues](https://github.com/IlyasFardaouix/Agent-racing-league/issues) — especially ones tagged `good first issue` or `founding`
3. Join the [Discussions](https://github.com/IlyasFardaouix/Agent-racing-league/discussions) to introduce yourself and share ideas
4. If you want to work on something big, **open an issue first** to discuss before coding

---

## 🏗️ Areas of Work

### 🔧 Race Engine (`/engine`)
The core of the project. Receives tasks, dispatches them to agents, meters execution.
- Language: Python 3.12+
- Key skills: async Python, Docker, task queues
- Entry point: `engine/README.md`

### 🔌 Agent SDK (`/sdk`)
How any agent (any framework, any model) plugs into the system.
- Language: Python (TypeScript SDK planned)
- Key skills: API design, protocol design
- Entry point: `sdk/README.md`

### 🎨 Live Viewer (`/viewer`)
The race spectacle. Real-time WebSocket updates, agent thought streams, position tracking.
- Language: Next.js / React / TypeScript
- Key skills: WebSockets, real-time UI, data visualization
- Entry point: `viewer/README.md`

### 🎙️ Commentator Agent (`/commentator`)
An AI agent that watches the race state and narrates it dramatically in real time.
- Language: Python
- Key skills: LLM prompting, streaming, event processing
- Entry point: `commentator/README.md`

### 🏁 Circuits (`/circuits`)
The task definitions that agents race on. Think: "debug this Python script", "research this topic and produce a report".
- Language: YAML + Python validators
- Key skills: task design, evaluation criteria definition
- Entry point: `circuits/README.md`

### 📐 Protocol & Docs (`/docs`)
Architecture decisions, the agent protocol spec, ADRs.
- Key skills: technical writing, systems design

---

## 📋 How to Contribute

### Small contributions (bug fixes, docs, small features)
1. Fork the repo
2. Create a branch: `git checkout -b feat/your-feature` or `fix/your-bug`
3. Make your changes
4. Open a PR with a clear description

### Large contributions (new components, architecture changes)
1. Open a GitHub Discussion or Issue first
2. Describe what you want to build and why
3. Wait for feedback from maintainers before starting
4. Then follow the PR process above

---

## 🧪 PR Checklist

- [ ] Code is readable and commented where non-obvious
- [ ] Includes tests if adding logic
- [ ] Docs updated if changing behavior
- [ ] PR description explains *what* and *why*

---

## 🗣️ Code of Conduct

- Be kind. We're all here because we think this is cool.
- Disagree on ideas, not people.
- Founding contributors set the tone — set a good one.

---

## 🌱 Founding Contributors

The first 20 contributors to meaningful PRs will be listed permanently in the README as **Founding Team** and get a special role in the community.

This is the ground floor. Welcome.
