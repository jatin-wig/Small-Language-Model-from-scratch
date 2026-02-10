# 🚀 Small Language Model From Scratch
### Building a Decoder-Only Transformer Without Training Frameworks 

A production-style implementation of a compact Transformer language model designed to understand the inner mechanics of modern LLM systems — from dataset engineering to autoregressive generation.

---

## Why Small Language Models?

While massive language models dominate headlines, **small language models are rapidly becoming critical** for real-world AI deployment:

- Low-latency inference  
- Privacy-sensitive applications  
- Cost-efficient AI systems  
- On-device / edge deployment  
- Specialized domain modeling

This project explores how capable compact transformers can be when engineered correctly.

---

## Built Without High-Level Frameworks

This project intentionally avoids abstraction-heavy libraries such as training wrappers.

Everything is implemented manually to expose the **true mechanics of transformer training**, including:

Attention computation  
Token embedding flow  
Dataset batching strategy  
Memory optimization  
Training stability techniques  

The goal is deep engineering understanding — not API usage.

---


## Architecture Overview

The model follows a **decoder-only Transformer architecture** designed for autoregressive language modeling.

### Core Components

- Causal Self-Attention  
- Multi-Head Attention  
- Feed-Forward Networks  
- Residual Connections  
- Layer Normalization  
- Weight Tying  
- Flash Attention support (when available)

---

# Built by Jatin Wig
### GitHub: https://github.com/jatin-wig
