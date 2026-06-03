---
type: mixed
density: balanced
style: sketch-notes
palette: default warm learning-note palette
image_count: 4
article: posts/hello-agents-chapter3.html
---

## Illustration 1
**Position**: After article lead
**Purpose**: Give readers the big evolution map from early language models to modern LLMs.
**Visual Content**: Timeline: N-gram -> Word Embedding -> RNN/LSTM -> Transformer -> LLM.
**Filename**: 01-timeline-llm-evolution.png

## Illustration 2
**Position**: After Transformer section
**Purpose**: Explain why self-attention is the key jump from sequential processing to parallel context modeling.
**Visual Content**: A sentence tokens attention map showing each token attending to others, plus a small contrast with RNN serial chain.
**Filename**: 02-framework-transformer-attention.png

## Illustration 3
**Position**: After prompt and tokenization section
**Purpose**: Help readers understand how human prompts enter the model as token sequences and become generated text.
**Visual Content**: User prompt -> tokenizer -> token IDs -> LLM -> generated tokens -> response.
**Filename**: 03-flowchart-prompt-tokenization.png

## Illustration 4
**Position**: After limitations section
**Purpose**: Show both LLM capability sources and reliability risks, plus practical mitigation methods.
**Visual Content**: Balanced framework: scaling laws/emergent abilities on one side; hallucination/stale knowledge/bias on the other; RAG/tools/verification as guardrails.
**Filename**: 04-framework-llm-capabilities-limits.png
