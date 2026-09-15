# Barnabus 3B: A Conversational Language Model with a Biblically Informed Ethical Framework

## A White Paper on the Creation, Training, and Deployment of Barnabus 3B

**KOKAI — Kairos of Koinonia AI**  
**Date: 2026-07-01**

---

# Executive Summary

Barnabus 3B is a conversational small language model developed by **KOKAI (Kairos of Koinonia AI)**. It is designed to provide a general conversational AI experience while operating under an ethical framework informed by biblical Scripture.

Unlike a traditional Bible chatbot or theological question-answering system, Barnabus 3B is intended to function as a broad conversational assistant. It can participate in everyday discussions, assist with creative work, provide educational support, engage in technical conversations, and help users explore ideas while maintaining an ethical foundation shaped by biblical principles.

The purpose of Barnabus 3B is not to limit artificial intelligence to religious discussion, but to explore how modern language models can be developed with intentional ethical alignment.

Barnabus 3B was trained using a curated dataset of **2,003 instruction-response pairs** focused on ethical reasoning, values alignment, and biblical principles. The model is designed for offline-first deployment on consumer hardware, allowing users to run AI locally without requiring constant cloud connectivity.

This white paper documents the motivation, architecture, dataset creation, training methodology, ethical framework, and deployment strategy behind Barnabus 3B.

---

# 1. Vision and Motivation

## 1.1 The Cultural Moment

Artificial intelligence is transforming how people communicate, learn, create, and make decisions. As AI systems become increasingly capable, questions surrounding ethics, responsibility, and the values guiding these systems become increasingly important.

Most modern language models are trained on large collections of human-generated information and attempt to provide generally neutral responses. While this approach offers broad usefulness, it can leave questions about consistent moral reasoning and ethical foundations.

KOKAI seeks to explore a different approach: building artificial intelligence systems that combine modern conversational abilities with a clearly defined ethical framework rooted in biblical principles.

## 1.2 The KOKAI Mission

KOKAI — **Kairos of Koinonia AI** — is a volunteer-led initiative with the mission:

> "Building a foundation for artificial intelligence rooted firmly in Biblical principles."

Barnabus 3B is the first major expression of this mission.

Barnabus 3B is not intended to replace human wisdom, theological study, or personal discernment. Instead, it is designed as an exploration of how AI can be developed with intentional ethical grounding.

The goals of Barnabus 3B include:

- Encouraging truthful and compassionate interactions.
- Promoting wisdom, humility, and integrity.
- Providing useful assistance while maintaining ethical boundaries.
- Exploring responsible AI development guided by Christian principles.

## 1.3 Why "Barnabus"?

The model is named after **Barnabas**, an early church leader known for encouragement, generosity, and faithfulness.

Barnabas represents the qualities KOKAI hopes to reflect in this AI system:

- Encouragement rather than discouragement.
- Truth combined with compassion.
- Service toward others.
- Faithfulness to foundational principles.

---

# 2. Technical Architecture

## 2.1 Model Specification

| Attribute | Value |
|---|---|
| Model Name | Barnabus 3B |
| Parameter Count | Approximately 3 billion |
| Base Model | Meta Llama / TinyLlama-1.1B-chat-v1.0 + LoRA |
| Purpose | Conversational AI with biblically informed ethical alignment |
| Context Window | Optimized for dialogue |
| Deployment | Offline-first through GGUF + Ollama |
| License | Meta Llama Community License |

---

## 2.2 Design Philosophy

Barnabus 3B is designed as a conversational language model rather than a specialized Bible information system.

Its biblical training is intended to influence:

- How the model approaches ethical questions.
- How it communicates with users.
- How it handles difficult conversations.
- How it balances truth, compassion, and responsibility.

The model focuses on:

### Ethical Grounding

Responses are shaped by principles derived from biblical Scripture, including concepts such as honesty, compassion, humility, wisdom, and respect for others.

### General Usefulness

Barnabus 3B remains a conversational AI capable of assisting with a variety of everyday tasks.

### Responsible Assistance

The model operates within defined ethical boundaries intended to encourage helpful and responsible interactions.

---

## 2.3 Infrastructure

Barnabus 3B was developed with accessibility and local deployment as core goals.

- **Training:** LoRA fine-tuning performed on consumer GPU hardware.
- **Inference:** GGUF quantization enables efficient CPU and GPU operation.
- **Runtime:** Designed for local execution through Ollama.
- **Distribution:** Released under applicable Meta Llama Community License terms.

---

# 3. Dataset Construction

## 3.1 Dataset Scale

The Barnabus 3B training dataset consists of **2,003 instruction-response pairs** designed to teach ethical reasoning patterns and biblical value alignment.

The dataset includes:

- **200 handcrafted foundational examples**
  - Carefully created examples establishing desired conversational behavior and ethical principles.

- **2 boundary-definition examples**
  - Examples defining acceptable and unacceptable response patterns.

- **1,800 synthetically expanded examples**
  - Generated examples providing broader coverage of biblical concepts and ethical scenarios.

The purpose of this dataset is not to transform Barnabus 3B into a Bible encyclopedia, but to provide a foundation for ethical reasoning informed by Scripture.

---

# 4. Training Methodology

Barnabus 3B was developed through supervised fine-tuning using **Low-Rank Adaptation (LoRA)**.

LoRA allows a smaller language model to be adapted toward a specialized purpose without requiring the resources needed to train a foundation model from scratch.

Training focused on:

- Ethical reasoning patterns.
- Compassionate communication.
- Scripture-informed values.
- Consistent behavioral alignment.

---

# 5. Deployment Philosophy

A central goal of Barnabus 3B is accessibility.

By supporting local deployment, Barnabus 3B allows users to operate an AI system without relying entirely on external cloud services.

Benefits include:

- Increased privacy.
- Offline availability.
- Greater user control.
- Accessibility on consumer hardware.

Barnabus 3B demonstrates that smaller language models can be adapted to explore ethical alignment while remaining practical for everyday users.

---

# 6. Future Vision

Barnabus 3B represents the beginning of KOKAI's exploration into faith-informed artificial intelligence.

Future development may include:

- Improved conversational abilities.
- Expanded ethical datasets.
- Additional model sizes.
- Integration with local AI tools and agent systems.
- Continued research into responsible AI development.

The long-term vision is not simply to create another chatbot, but to explore how artificial intelligence can be developed with transparency, intentional values, and a commitment to serving people.

---

# Conclusion

Barnabus 3B represents an experiment in building artificial intelligence with a clearly defined ethical foundation.

By combining modern language model technology with principles derived from Scripture, KOKAI seeks to explore a future where AI can be both capable and guided by meaningful values.

Barnabus 3B is not designed to replace human judgment, faith, or wisdom. Instead, it is designed as a tool: a conversational AI built with the intention of reflecting wisdom, compassion, truthfulness, and integrity.
