# Barnabus 8B

A free, open biblical-ethics large language model created by **Kairos of Koinonia AI (KOKAI)**.

Barnabus was previously published as Barnabus 3B. A later review revealed that the model was built from the **Llama 3.1 8B Instruct** base rather than the intended 3B base. The old Barnabus 3B release is therefore being deprecated to correct the model’s identity and other mismatched information.

## Quick Start with Ollama

Pull Barnabus 8B:

```bash
ollama pull kokai/barnabus-8b
```

Run Barnabus 8B:

```bash
ollama run kokai/barnabus-8b
```

## What It Is

- A customized large language model focused on biblical ethics
- Built from the approximately 8-billion-parameter Llama 3.1 Instruct model
- Guided by evangelical Protestant and Sola Scriptura principles
- Designed for biblical reasoning, conversation, research, and tool-assisted workflows
- Capable of running locally and offline on compatible consumer hardware
- Distributed through Ollama for straightforward local use

Barnabus 8B is an **LLM**, not a 3B small language model.

## What It Believes

- The Bible is the final authority for faith and practice.
- Homosexual acts are sinful, while the people involved remain image-bearers who must be treated with love and dignity.
- Biblical truth must not be treated as optional or endlessly flexible.
- Answers should cite the relevant book, chapter, and verse whenever possible.
- Moral clarity and personal dignity belong together.
- People should be treated with compassion even when their beliefs or actions are challenged.

## Sources and Theological Foundation

Barnabus draws its theological direction from:

- The ESV Bible
- Evangelical Protestant theology
- The Westminster Shorter Catechism
- Modern evangelical ethics writers

Catholic, Eastern Orthodox, and mainline Protestant theological sources are excluded by design. This reflects the model’s intended evangelical Protestant perspective rather than a claim that people from those traditions should be treated disrespectfully.

## Tags

- biblical
- Christian
- evangelical
- ethics
- theology
- reasoning
- thinking
- tool-use
- local
- offline
- Llama 3.1
- 8B

## Training and Development

Local GGUF inference is the currently supported path.

If LoRA fine-tuning is added later, development should use the local GGUF and llama.cpp pipeline located at:

```text
D:\hermes\barnabus-8b
```

Future releases should be checked against the underlying base model before publication to ensure that the model name, parameter count, architecture, metadata, and documentation agree.

## Deprecation of Barnabus 3B

The former Barnabus 3B release is being deprecated because its published description contained mismatched information about the underlying model.

During development, Hermes was instructed to modify a 3B model, but the resulting Barnabus model was actually based on the Llama 3.1 8B Instruct model. Renaming the project Barnabus 8B corrects that discrepancy and accurately describes what users are downloading and running.

Barnabus 8B is the official continuation of the project.

## License

Barnabus 8B is built on Meta Llama and is governed by the applicable **Meta Llama Community License**.

Any original KOKAI configuration, prompting, training material, or adapter work is provided subject to the terms and restrictions of the underlying Meta Llama license.

**Kairos of Koinonia AI · KOKAI · 2026**
