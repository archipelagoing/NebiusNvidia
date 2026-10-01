# Nebius x NVIDIA Global AI Hackathon ft archipelagoing

## Overview

Welcome to the **Nebius x NVIDIA Global AI Hackathon**.

Build a working AI system on **open, independent infrastructure**, and own the whole thing.

The NVIDIA x Nebius Global AI Hackathon is for AI builders, ML engineers, founders, and anyone interested in shipping practical, high-performance AI.

Projects will use **NVIDIA open-source models** served on **Nebius** through **Nebius Token Factory**, backed by high-performance GPU infrastructure.

The goal is to:

- Experiment with new ideas
- Push the boundaries of open-source AI
- Build a working AI system
- Deploy something people can actually use
- Compete for prizes and recognition

Participants can also join technical onboarding sessions, workshops, team formation events, focused build sessions, and feedback sessions throughout the hackathon.

---

# Requirements

## The Challenge

Every submission must:

- Run on **Nebius Token Factory** or **Nebius AI Cloud**
- Use at least **one NVIDIA open-source model**

Everything else is up to you.

---

# Tracks

## 1. Coding and Agentic Engineering

Build **coding agents and developer tools**.

Possible directions include:

- Coding agents
- Automated debugging tools
- Code-generation systems
- Testing agents
- Repository agents
- Developer copilots
- Autonomous software engineering workflows

Agents can **write, run, and test code through Token Factory**.

---

## 2. Best Apps and Agents

Build an AI application or agent that someone would actually use.

This could include:

- Productivity tools
- AI copilots
- Autonomous workflows
- Research assistants
- Creative applications
- Specialized agents
- Multi-agent systems

Projects should be powered by **Nemotron models on Nebius through Token Factory**.

### Suggested Model Strategy

Use different Nemotron models depending on the task:

- **Nemotron 3 Ultra** for difficult reasoning
- **Nemotron Nano** or **Super** for faster, everyday requests

This allows applications to remain responsive while using credits efficiently.

### Optional Infrastructure

Projects are encouraged to use:

- **Nebius Serverless Endpoints** for application inference
- **Nebius Serverless Jobs** for background processing and asynchronous workflows

Neither is required.

---

## 3. Personal AI

Build an **always-on, private AI assistant** that works for you while keeping your data under your control.

Possible capabilities include:

- Persistent memory
- Reusable skills
- Personal knowledge
- Tool access
- Workflow automation
- Task execution
- User-controlled data access

Projects must use at least one NVIDIA open-source model.

Suggested technologies include:

- **NVIDIA NemoClaw**
- **OpenShell**
- **Hermes Agent**
- **Nebius Serverless**

The goal is to assemble, secure, and run your own personal AI system.

---

## 4. Physical AI

Build **embodied or edge AI agents** that can sense and act in the real world.

Possible areas include:

- Robotics
- IoT
- Edge AI
- Embodied agents
- Sensor-based systems
- Autonomous devices

Projects can use technologies including:

- **Nemotron**
- **GR00T**
- **Cosmos**
- **Sonic models**
- Agent runtimes

### Nebius Infrastructure

Use **Nebius Serverless Jobs** for tasks such as:

- Running simulations
- Generating synthetic data
- Evaluating robot policies
- Processing sensor data at scale

Use **Nebius Serverless Endpoints** when real-time inference is needed.

### Physical AI Demo Requirement

The demonstration video must contain at least **1 minute** showing:

- The physical hardware or robot actually operating

or, if the project does not contain physical hardware:

- The project's key application modules operating

---

# Submission Requirements

## 1. Working Project

Build a functioning project using:

- NVIDIA Nemotron or another NVIDIA open-source model

and

- Nebius Token Factory or Nebius AI Cloud

The project must satisfy the requirements of the selected track.

---

## 2. Category

Select the track that best represents the project:

- Coding and Agentic Engineering
- Best Apps and Agents
- Personal AI
- Physical AI

---

## 3. Project Description

Explain:

- **What** you created
- **Why** you created it
- **How** it works

The description should make the project's value and technical architecture easy for judges to understand.

---

## 4. Working Demo

Provide a URL to one of the following:

- Hosted application
- Working demo
- Test build

> A hosted demo is not required for Physical AI submissions.

---

## 5. Demo Video

Upload a **public YouTube video of 3 minutes or less**.

The video should demonstrate:

1. The project working
2. How **Nebius Token Factory** is used
3. How **NVIDIA Nemotron** or another NVIDIA open-source model is used
4. The project's primary user experience

### Physical AI

Physical AI submissions should dedicate at least **1 minute** to showing:

- Physical hardware or the robot operating

or

- Key application modules operating if there is no physical hardware

---

## 6. Public Code Repository

Provide a publicly accessible repository on:

- GitHub
- GitLab
- Bitbucket

The repository must contain an **open-source license**, such as:

- Apache 2.0
- MIT
- MPL 2.0

The license should be clearly visible from the repository's main page.

---

## 7. README

The repository must include a README with:

### Setup Instructions

Explain how to install and run the project.

### NVIDIA Integration

Clearly identify:

- Which NVIDIA model(s) are used
- What those models do within the application
- Why they were selected

### Nebius Token Factory

Explain:

- Where Token Factory is used
- How it accelerated or enabled the project
- Which workloads run through it

### Additional Nebius Services

Document any additional tools or services used, such as:

- Nebius AI Cloud
- Nebius Serverless Endpoints
- Nebius Serverless Jobs

---

## 8. Product Feedback

Provide feedback about the technologies used during development.

This may include:

- Nebius Token Factory
- Nebius AI Cloud
- NVIDIA models
- NVIDIA tools
- Other Nebius services

Document:

- What worked well
- What was difficult
- What could be improved
- What features would have helped

---

## 9. Existing Projects

If the project existed **before the Submission Period**, include a written explanation of what was **significantly updated during the Submission Period**.

Clearly separate:

### Before the Hackathon

What already existed.

### Built During the Hackathon

What was added, changed, redesigned, or substantially improved for the competition.

---

## 10. Builders & Brews

If you participated in an **IRL Builders & Brews** event, select the city you attended when submitting.

This makes the project eligible for the **City Winner Award**.

---

# Submission Checklist

- [ ] Working AI project
- [ ] Runs on Nebius Token Factory or Nebius AI Cloud
- [ ] Uses at least one NVIDIA open-source model
- [ ] Track selected
- [ ] Project description completed
- [ ] Working demo URL
- [ ] Public YouTube demo video ≤ 3 minutes
- [ ] Public code repository
- [ ] Open-source license
- [ ] README with setup instructions
- [ ] NVIDIA model usage documented
- [ ] Token Factory usage documented
- [ ] Other Nebius services documented
- [ ] Product/tool feedback included
- [ ] Pre-existing work vs. hackathon work documented, if applicable
- [ ] Builders & Brews city selected, if applicable
- [ ] Official Rules reviewed

---

# Core Technical Constraint

At minimum, the architecture needs to satisfy:

```text
Application / Agent
        │
        ▼
NVIDIA Open-Source Model
        │
        ▼
Nebius Token Factory
        OR
Nebius AI Cloud
```

Everything beyond that is open-ended.

---

# Goal

Build something that demonstrates not simply that an NVIDIA model can be called through Nebius, but that **open models + independent AI infrastructure enable a genuinely useful system**.
