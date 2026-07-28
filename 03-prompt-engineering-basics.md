# 03 - Prompt Engineering Basics

Notes on the fundamentals of writing effective prompts for LLMs. See the `genai-prompt-engineering-basics` repo for hands-on examples.

## What is Prompt Engineering?

Prompt engineering is the practice of designing the input (prompt) given to an LLM to get more accurate, relevant, and useful outputs.

## Core Techniques

- **Zero-shot prompting** — asking the model to perform a task directly, with no examples (e.g., "Summarize this paragraph.").
- **Few-shot prompting** — providing a few examples of the desired input/output pattern before asking the model to continue (helps the model understand the expected format).
- **Chain-of-thought prompting** — asking the model to reason step by step before giving a final answer, which improves accuracy on multi-step problems.
- **Role prompting** — asking the model to respond as if it were a specific persona or expert (e.g., "You are a senior DevOps engineer...") to shape tone and focus.

## Basic Best Practices

1. Be specific about the desired output format (e.g., "Respond in a bulleted list").
2. Provide context the model needs (relevant background, constraints, examples).
3. Break complex tasks into smaller steps.
4. Iterate — refine the prompt based on the output you get.
5. Set clear boundaries (e.g., "If you are not sure, say so") to reduce hallucination.

## Simple Example

```
Prompt: "Explain what a load balancer does, in 2 sentences, for someone new to networking."
```

This is a zero-shot prompt with clear scope (2 sentences) and clear audience (someone new to networking) — both help the model produce a focused answer.

---
> Personal learning notes — simplified for beginner understanding.

