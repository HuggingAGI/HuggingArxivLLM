# 借助GRPO方法，无监督后训练助力多模态大语言模型推理能力的提升

发布时间：2025年05月28日

`LLM理论` `人工智能` `机器学习`

> Unsupervised Post-Training for Multi-Modal LLM Reasoning via GRPO

# 摘要

> 提升多模态大型语言模型（MLLMs）通常采用监督微调（SFT）或强化学习（RL），但这些方法依赖昂贵的多模态标注数据，难以持续。近期无监督后训练虽有进展，但方法复杂。我们首次提出使用GRPO算法，结合自奖励机制，打造MM-UPT框架，实现MLLM的无监督持续改进。实验显示，MM-UPT显著提升了Qwen2.5-VL-7B的推理能力，且无需真实标签。MM-UPT超越无监督基线，接近监督效果。此外，MLLM自动生成的合成问题进一步提升了性能，为可扩展自我改进提供了新思路。MM-UPT为MLLM的持续自主增强开辟了新范式。代码已开源。

> Improving Multi-modal Large Language Models (MLLMs) in the post-training stage typically relies on supervised fine-tuning (SFT) or reinforcement learning (RL). However, these supervised methods require expensive and manually annotated multi-modal data--an ultimately unsustainable resource. While recent efforts have explored unsupervised post-training, their methods are complex and difficult to iterate. In this work, we are the first to investigate the use of GRPO, a stable and scalable online RL algorithm, for enabling continual self-improvement without any external supervision. We propose MM-UPT, a simple yet effective framework for unsupervised post-training of MLLMs. MM-UPT builds upon GRPO, replacing traditional reward signals with a self-rewarding mechanism based on majority voting over multiple sampled responses. Our experiments demonstrate that MM-UPT significantly improves the reasoning ability of Qwen2.5-VL-7B (e.g., 66.3 %$\rightarrow$72.9 % on MathVista, 62.9 %$\rightarrow$68.7 % on We-Math), using standard dataset without ground truth labels. MM-UPT also outperforms prior unsupervised baselines and even approaches the results of supervised GRPO. Furthermore, we show that incorporating synthetic questions, generated solely by MLLM itself, can boost performance as well, highlighting a promising approach for scalable self-improvement. Overall, MM-UPT offers a new paradigm for continual, autonomous enhancement of MLLMs in the absence of external supervision. Our code is available at https://github.com/waltonfuture/MM-UPT.

[Arxiv](https://arxiv.org/abs/2505.22453)