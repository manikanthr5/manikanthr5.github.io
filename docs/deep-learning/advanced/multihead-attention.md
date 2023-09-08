---
comments: true
---

# Multihead Attention

In this blog article, we will go through and understand the different concepts of Attention, then learn about Multihead Attention and see how it is a building block of the Transformers models like BERT, GPT & Variants and T5 models. We will try to understand the concept first and then go into implementing the Attention and Multihead Attention layers in PyTorch.

## Contents

- [Motivation](#motivation)
- [Attenion Basics](#attention-basics)
- [Self Attention](#)
- [Multihead Attention](#)
- [Multihead Attention in Transformers](#)

## Motivation

### Translation before Attention

### Translation after Attention

### Attention examples

## Attention Basics

### Bahdanav Attention

### Different types of Attention

## Self Attention

### Key Value Pairs

### Self Attention Implementation

## Multihead Attenion

### Multihead Attention Implementation

```python
import torch
import torch.nn as nn



class Attention(nn.Module):
    def __init__(self):
        pass

    def forward(self):
        pass


class MultiheadAttention(nn.Module):
    def __init__(self, embed_dim, num_heads, dropout=0.0, bias=True, add_bias_kv=False, add_zero_attn=False, kdim=None, batch_first=False, device=None, dtype=None):
        pass

    def forward(self, X, return_attenion: bool = False):
        pass

```

## Multihead Attention in Transformers
