# Manual Transformer Encoder – Self-Attention

## 📌 Overview

This project provides a **manual implementation of a Transformer Encoder with Self-Attention in Python**, based on a mathematical example.

The implementation demonstrates how a Transformer converts a noisy raw sentence into **context-aware representations** through the different stages of the Transformer Encoder.

The input sentence used in the example is:

> **"OMG!!! AI students rrr brillianttt 😊"**

It is progressively transformed into:

```text
Raw Text
   ↓
Preprocessing
   ↓
Tokenization
   ↓
Token IDs
   ↓
Embedding
   ↓
Positional Encoding
   ↓
Query, Key, Value
   ↓
Self-Attention
   ↓
Softmax Attention Weights
   ↓
Attention Output
   ↓
Output Projection
   ↓
Residual Connection + LayerNorm
   ↓
Feed-Forward Network
   ↓
Residual Connection + LayerNorm
   ↓
Final Context-Aware Representation
