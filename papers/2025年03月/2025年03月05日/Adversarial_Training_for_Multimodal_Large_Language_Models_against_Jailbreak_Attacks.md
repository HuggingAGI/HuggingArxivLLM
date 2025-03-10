# # 防御越狱攻击的多模态大型语言模型对抗训练方法

发布时间：2025年03月05日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在防御越狱攻击方面的应用，提出了ProEAT框架，属于将LLM应用于实际安全问题的解决方案，因此归类为LLM应用。` `多模态`

> Adversarial Training for Multimodal Large Language Models against Jailbreak Attacks

# 摘要

> 多模态大型语言模型 (MLLMs) 在跨模态任务中取得了显著进展，但它们仍易受越狱攻击影响。本文首次提出了一种针对 MLLM 训练阶段的对抗训练 (AT) 方法，旨在防御越狱攻击。我们提出了 ProEAT 框架，通过轻量级投影层和动态权重调整机制，有效解决了大规模参数调优和多模态鲁棒性两大挑战。实验表明，ProEAT 在三个主流 MLLM 上显著提升了防御性能，平均超越现有方法 +34%，同时保持了高准确率。这一框架为开发更安全的多模态系统提供了新思路。

> Multimodal large language models (MLLMs) have made remarkable strides in cross-modal comprehension and generation tasks. However, they remain vulnerable to jailbreak attacks, where crafted perturbations bypass security guardrails and elicit harmful outputs. In this paper, we present the first adversarial training (AT) paradigm tailored to defend against jailbreak attacks during the MLLM training phase. Extending traditional AT to this domain poses two critical challenges: efficiently tuning massive parameters and ensuring robustness against attacks across multiple modalities. To address these challenges, we introduce Projection Layer Against Adversarial Training (ProEAT), an end-to-end AT framework. ProEAT incorporates a projector-based adversarial training architecture that efficiently handles large-scale parameters while maintaining computational feasibility by focusing adversarial training on a lightweight projector layer instead of the entire model; additionally, we design a dynamic weight adjustment mechanism that optimizes the loss function's weight allocation based on task demands, streamlining the tuning process. To enhance defense performance, we propose a joint optimization strategy across visual and textual modalities, ensuring robust resistance to jailbreak attacks originating from either modality. Extensive experiments conducted on five major jailbreak attack methods across three mainstream MLLMs demonstrate the effectiveness of our approach. ProEAT achieves state-of-the-art defense performance, outperforming existing baselines by an average margin of +34% across text and image modalities, while incurring only a 1% reduction in clean accuracy. Furthermore, evaluations on real-world embodied intelligent systems highlight the practical applicability of our framework, paving the way for the development of more secure and reliable multimodal systems.

[Arxiv](https://arxiv.org/abs/2503.04833)