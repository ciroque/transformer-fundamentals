# Transformer Fundamentals – Guided Notebook Series

**Format:** Jupyter (.ipynb)  
**Language:** Python 3.12.12  
**Frameworks:** NumPy, PyTorch 2.5+, Hugging Face Transformers, ipywidgets, Matplotlib

---

## Overview

This series of six guided notebooks introduces the *core mechanisms* behind Transformer models through interactive, visual exploration.  
Each notebook stands alone but follows a consistent structure, making it suitable for both self-study and instructional use.

---

## Recommended Order

1. **01_input_tokens_embeddings.ipynb** — Tokenization & Embeddings  
   → Learn how text becomes numerical vectors; visualize embeddings.

2. **02_attention_qkv.ipynb** — Attention Mechanism (Q, K, V)  
   → Build attention from scratch; connect to PyTorch’s MultiheadAttention.

3. **03_scoring_dotproduct_scaling.ipynb** — Scoring & Scaling  
   → Explore how dot-products become attention scores and why scaling matters.

4. **04_softmax_weighting.ipynb** — Softmax Weighting  
   → Experiment with temperature and attention focus; visualize entropy.

5. **05_weighted_sum_multihead.ipynb** — Weighted Sum & Multi-Head  
   → Combine multiple attention heads and interpret their roles.

6. **06_ffn_stacking_generation.ipynb** — Feed-Forward, Stacking & Generation  
   → Assemble a minimal Transformer block and compare with GPT-2 generation.

---

## Structure per Notebook

- **Concept Overview:** short explanation with key equations or diagrams  
- **Setup Cell:** environment check and optional installs  
- **From-Scratch Section:** NumPy-based math for transparency  
- **Framework Section:** PyTorch/HF implementation examples  
- **Interactive Section:** ipywidgets + Matplotlib visualizations  
- **Bonus:** multilingual exercise (BERT-multilingual, XLM-R)  
- **Reflection:** key takeaways and follow-ups  

---

## Requirements

```bash
pip install torch>=2.5 transformers>=4.44 datasets>=3.0.0 ipywidgets>=8.1 matplotlib>=3.8 umap-learn>=0.5.6 scikit-learn
```

GPU is optional but recommended.

---

© 2025 – Educational notebooks generated for Transformer fundamentals learning.
