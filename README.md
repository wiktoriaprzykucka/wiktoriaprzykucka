<h1 align="center">Hi, I'm Wiktoria 👋</h1>
<h3 align="center">AI Engineering Student · Computer Vision, RAG & Edge AI</h3>

<p align="center">
  Creative Technologies & AI @ Howest University of Applied Sciences · Kortrijk, Belgium 🇧🇪 · from Koszalin, Poland 🇵🇱
</p>

---

### About

I build AI systems that have to work outside a notebook — on a Raspberry Pi, behind an API, against messy client data. Most of my work sits at three points: **computer vision and pose estimation**, **retrieval over real business data (RAG / GraphRAG)**, and the engineering that holds them together — data pipelines, services, databases, containers, deployment.

- 🎓 B.Sc. Creative Technologies & Artificial Intelligence, Howest (2024 → 2027)
- 💼 Built a RAG/GraphRAG assistant over industrial Excel data for a client — led to a student job offer
- 🏆 Two projects selected for Howest's **Tech Connect** public exhibition
- 🔬 Looking for a **research internship, 15 Feb – 4 Jun 2027** — computer vision, ML, applied AI
- 🌱 Rebuilding my linear algebra, calculus and probability; reading into quantum computing
- 💬 Ask me about pose estimation, retrieval pipelines, or running ML on constrained hardware

---

### Selected work

**🤸 trAIner — AI Gymnastics Evaluation**
End-to-end platform that scores gymnastics performances from video. MediaPipe extracts 33 body landmarks per frame, normalised against hip centre and torso size so predictions hold across athlete size and camera distance. Bidirectional LSTMs segment movements into phases and grade them — 91% segmentation, 86% grading. Three Dockerized services, Gradio interface for coaches, automated PDF reports.
`Python` `PyTorch` `MediaPipe` `FastAPI` `Gradio` `Docker Compose`

**🖐️ Real-Time ASL Alphabet Recognition**
Recognises ASL letters from a live webcam feed, split across two machines: a Raspberry Pi captures frames, a laptop runs inference over TCP, keeping compute off the embedded device. Classification over 21 hand landmarks (42 features), with a custom labelled-data collection pipeline, safe-zone hand placement guidance, GPIO status LEDs, systemd deployment, and a Flask practice app that gives learners instant feedback.
`Python` `MediaPipe` `OpenCV` `scikit-learn` `Flask` `Raspberry Pi`

**🐎 AI Show Jumping Simulator**
A Unity ML-Agents environment where an AI-controlled horse learns FEI-inspired show-jumping courses. Custom reward shaping over direction alignment, approach quality and movement efficiency; curriculum learning that promotes the agent through harder courses on performance thresholds; JSON-driven course generation. Includes an in-engine parkour editor with Bézier path visualisation and runtime switching between human and AI control.
`Unity` `C#` `ML-Agents` `Reinforcement Learning`

**🚦 Smart Traffic Management from Aerial Video**
Six-module pipeline over aerial footage: YOLOv8 vehicle detection → XGBoost flow forecasting → a graph neural network modelling the intersection network → a genetic algorithm optimising signal timing.
`YOLOv8` `XGBoost` `PyTorch Geometric`

**🔎 Industrial RAG / GraphRAG Assistant** — *client project, code private under NDA*
Question answering over semi-structured Excel production data. Hybrid retrieval combining vector search with a Neo4j graph representation, PostgreSQL storage, Azure AI endpoints and output guardrails, with the source spreadsheets kept authoritative.

---

### Tech stack

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C#](https://img.shields.io/badge/-C%23-239120?style=flat&logo=csharp&logoColor=white)

**AI / ML**
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
MediaPipe · RAG / GraphRAG · Reinforcement Learning

**Data & infrastructure**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Neo4j](https://img.shields.io/badge/-Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0089D6?style=flat&logo=microsoftazure&logoColor=white)
FastAPI · Flask · Kubernetes · CI/CD

**Hardware**
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)
GPIO · I²C · sensors & actuators · BLE UART

---

### Outside the obvious

I like putting AI where people don't usually put it — most of my project ideas come from equestrian sport, which is how a reinforcement-learning horse ended up in my portfolio. Movement analysis, posture and lameness detection are where I want to take that next.

---

### Reach me

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wiktoria-przykucka/)

<p align="center"><i>Building, breaking, and trying to understand what's underneath the abstraction.</i></p>
