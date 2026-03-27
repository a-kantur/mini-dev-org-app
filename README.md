# mini-dev-org-app
# 🧠 Dev Persona AI Agent (WIP)

An experimental AI agent that simulates feedback from three developer personas in a mid-sized tech company.

## 🚧 Status

**Work in Progress (WIP)** — This project is part of my ongoing effort to deepen my skills in:

* AI product development
* Prompt engineering
* Retrieval-Augmented Generation (RAG)
* Developer persona modeling

---

## 🎯 Overview

This agent allows a user to input a topic (e.g., a feature idea, tooling decision, or architecture change) and receive:

1. **Independent feedback** from three developer personas:

   * **Craig** — Director of Engineering
   * **Kyle** — Engineering Manager
   * **Jordan** — Software Engineer

2. A **5-line simulated conversation** between the three personas (no Product Manager present), capturing realistic engineering debate and trade-offs.

---

## 🧑‍💻 Personas

The personas are modeled using:

* Organizational hierarchy (Director → Manager → IC)
* Behavioral traits (inspired by Business Chemistry)
* Developer community signals (GitHub, Reddit, Hacker News, etc.)

### Craig (Director of Engineering)

* Focus: business impact, scalability, org efficiency
* Style: strategic, concise, outcome-driven

### Kyle (Engineering Manager)

* Focus: execution, trade-offs, team delivery
* Style: pragmatic, balanced, risk-aware

### Jordan (Software Engineer)

* Focus: code quality, technical design, developer experience
* Style: direct, detail-oriented, implementation-focused

---

## ⚙️ Tech Stack

* LLM: Groq API (free, llama-3.1-8b-instant model)
* Backend: The backend is a simple Node.js/Express server in server.js
* Frontend: The frontend is a single HTML file (public/index.html)
* Data (planned): developer community content (GitHub, Stack Overflow, etc.)
Currently the agent runs only on localhost (port 3000)

---

## 🔍 Planned Features

* [ ] Retrieval-Augmented Generation (RAG) using real developer content
* [ ] Persona grounding using external sources
* [ ] Improved multi-agent conversation realism
* [ ] Topic memory and comparison
* [ ] UI for interactive exploration

---

## 🧪 Why I Built This

This project is a hands-on way for me to:

* Practice building AI agents with distinct personas
* Explore how developers think across roles
* Simulate real-world product discussions
* Prepare for AI Product Manager interviews

---

## 🚀 Future Direction

I plan to extend this project by:

* Integrating RAG pipelines (vector DB + embeddings)
* Using real-world developer discussions as grounding context
* Evaluating output quality and persona consistency
* Experimenting with multi-agent coordination patterns

---

## 📌 Disclaimer

This is an experimental project. Outputs may be inaccurate, incomplete, or biased depending on prompt design and model limitations.

---

## 🙌 Feedback

If you have suggestions or ideas, feel free to open an issue or reach out!
