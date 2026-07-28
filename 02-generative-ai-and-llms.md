# 02 - Generative AI and Large Language Models (LLMs)

Notes on generative AI concepts and how large language models work, at a beginner level.

## What is Generative AI?

Generative AI refers to models that create new content — text, images, code, audio — rather than just classifying or predicting a label. Examples include text generators (ChatGPT), image generators (DALL-E, Midjourney), and code assistants (GitHub Copilot).

## What is a Large Language Model (LLM)?

An LLM is a neural network trained on large amounts of text to predict the next word (token) in a sequence. Through this simple objective, trained at massive scale, LLMs learn grammar, facts, reasoning patterns, and coding ability.

## Key Concepts

- **Token** — a chunk of text (word or part of a word) that a model processes as a unit.
- **Context window** — the amount of text (in tokens) a model can consider at once when generating a response.
- **Pre-training** — training a model on a broad, general dataset before fine-tuning it for specific tasks.
- **Fine-tuning** — further training a pre-trained model on a smaller, task-specific dataset.
- **Embeddings** — numerical representations of text that capture meaning, used for search and similarity comparisons.
- **Hallucination** — when a model generates plausible-sounding but incorrect or fabricated information.

## Common Ways to Use LLMs

1. Chat interfaces (e.g., ChatGPT, Claude) for Q&A, writing, and brainstorming.
2. API integration — calling a model programmatically to build an application (see the `llm-chatbot-starter` repo for a basic example).
3. Coding assistants (e.g., GitHub Copilot) that suggest code inline in an editor.

## Basic Limitations to Keep in Mind

- LLMs can hallucinate — always verify important facts.
- Outputs can reflect biases present in training data.
- Context windows are limited — very long documents may need to be summarized or chunked.

---
> Personal learning notes — simplified for beginner understanding.

