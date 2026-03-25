# The Reverse Turing Test

**Can you still tell human writing from machine output?**

A cognitive benchmark that measures your ability to distinguish authentic human text from AI-generated responses. Each round presents a real question with a real answer — your job is to decide whether it was written by a human or by ChatGPT.

**[Take the test →](https://chiefautism.github.io/reverse-turing-test/)**

## How it works

1. You're shown a question and one answer
2. You decide: **Human** or **ChatGPT**?
3. Every answer is real — sourced from the [HC3 Dataset](https://huggingface.co/datasets/Hello-SimpleAI/HC3) (Human ChatGPT Comparison Corpus)
4. After each round, you get an explanation of the telltale signs
5. At the end — your Reverse Turing Score, a bell curve, and a shareable result card

## Features

- **Live data** — pulls random samples from 17,000+ paired responses via HuggingFace Datasets API
- **No two tests are the same** — random offset + random human/GPT selection each session
- **Multiple domains** — ELI5, Open QA, Finance, Medicine, Wiki/CS, or all
- **Configurable rounds** — 20 (standard), 35 (extended), 50 (research)
- **Auto-detection explanations** — analyzes GPT-isms (delve, tapestry, moreover...) and human markers (hedging, slang, anecdotes)
- **Shareable result card** — 3:4 canvas image with bell curve, copy to clipboard or download
- **Local history** — scores persist in localStorage across sessions
- **Privacy-friendly analytics** — GoatCounter, no cookies

## Design

Styled after [Nature](https://nature.com) — serif headings (Harding/Palatino), system sans-serif body, academic paper layout, `#006699` accents on white.

## Tech

Single HTML file. No build step. No dependencies. No backend.

- Vanilla JS
- HuggingFace Datasets REST API
- Canvas API for share card generation
- localStorage for persistence
- GoatCounter for anonymous telemetry

## Dataset

[Hello-SimpleAI/HC3](https://huggingface.co/datasets/Hello-SimpleAI/HC3) — Guo, Z. et al. (2023). *How Close is ChatGPT to Human Experts? Comparison Corpus, Evaluation, and Detection.*

## Author

[@chiefofautism](https://x.com/chiefofautism)
