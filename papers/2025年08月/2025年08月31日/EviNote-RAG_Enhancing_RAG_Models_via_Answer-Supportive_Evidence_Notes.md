# <翻译失败>

发布时间：2025年08月31日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> EviNote-RAG: Enhancing RAG Models via Answer-Supportive Evidence Notes

# 摘要

> <翻译失败>

> Large Language Models (LLMs) empowered with retrieval mechanisms have achieved strong progress in open-domain question answering (QA). Yet, the conventional retrieve--then--answer paradigm often suffers from two key limitations: (1) low signal-to-noise ratio in retrieved evidence, where useful information is buried under irrelevant content, and (2) error accumulation in multi-hop reasoning when incomplete or noisy passages are involved. To address these challenges, we present EviNote-RAG, an agentic RAG framework that introduces a structured retrieve--note--answer pipeline. Instead of directly reasoning over raw retrievals, the model is trained to compose Supportive-Evidence Notes (SENs), concise, human-like notes that preserve only answer-relevant information, highlight uncertainty, and explicitly state when no useful evidence exists. This distillation process is further reinforced by the Evidence Quality Reward (EQR), an entailment-based signal that evaluates whether SENs logically support the final answer. Together, SENs and EQR guide the model toward faithful and robust reasoning, while reducing the impact of noise. Experiments on in-domain and out-of-domain QA benchmarks show that EviNote-RAG consistently outperforms strong baselines in accuracy, generalization, and training stability. In particular, it achieves state-of-the-art results while enhancing robustness and efficiency, yielding relative F1 gains of 20\% on HotpotQA (+0.093), 40\% on Bamboogle (+0.151), and 91\% on 2Wiki (+0.256) via denser rewards and reduced verbosity.

[Arxiv](https://arxiv.org/abs/2509.00877)