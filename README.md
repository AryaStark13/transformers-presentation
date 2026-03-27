# How LLMs Actually Learn

A browser-based lecture presentation built with [Reveal.js](https://revealjs.com/) covering how large language models are architected, trained, and kept up to date. Designed for CS students with a background in neural networks and basic transformer architecture.

## Web Presentation URL - Follow Along!

**[AryaStark13.github.io/transformers-presentation](https://AryaStark13.github.io/transformers-presentation)**

---

## Topics Covered

**1. Architecture**
- Why attention beats RNNs for long context
- The tokenization problem (why LLMs can't count r's in "Strawberry")
- LayerNorm, skip connections, and loss surface visualization

**2. Data & Compute**
- Memory requirements: 300B parameter model (training vs. inference)
- Sources of training data: web crawls, curated corpora, synthetic data
- Why Scale AI ($28B) and Mercor exist

**3. Training Phases** *(main focus)*
- Pre-training via Causal Language Modeling
- Supervised Fine-Tuning (SFT)
- Post-training: RLHF, RLAIF, RLVR — differences, use cases, and real controversies
- Why RL is hard: reward hacking, distribution shift, sparse rewards, reward model collapse

**4. Keeping Knowledge Current**
- The knowledge cutoff problem
- Continuous Pre-training (CPT) and its weight arithmetic
- RAG, long context windows, and tool use as alternatives

---

## Editing Locally: Feel Free to Fork & Modify

1. Clone the repository or download the ZIP.
```bash
git clone https://github.com/AryaStark13/transformers-presentation.git
cd transformers-presentation
```

Just open `index.html` in any browser — no server or build step needed.

Make sure the `assets/` folder is in the same directory as the HTML file.

## Navigation

| Key | Action |
|-----|--------|
| `→` / `Space` | Next slide |
| `←` | Previous slide |
| `F` | Fullscreen |
| `O` | Slide overview |
| `Esc` | Exit fullscreen / overview |

---

## Authors

- **Arihant Sheth** (CMU '25, DJSCE '24)
- **Claude Sonnet 4.6** (Anthropic)