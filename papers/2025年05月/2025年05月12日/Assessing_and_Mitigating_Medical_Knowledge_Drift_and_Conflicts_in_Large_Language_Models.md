# 评估与缓解大型语言模型中的医学知识漂移与冲突

发布时间：2025年05月12日

`LLM应用

理由：论文探讨了大型语言模型在医疗领域中的应用，特别是如何应对医学知识的快速变化和模型的可靠性问题。虽然提到了RAG作为缓解策略之一，但论文的核心是研究LLMs在医疗场景中的表现和改进方法，属于应用层面的研究。` `临床实践`

> Assessing and Mitigating Medical Knowledge Drift and Conflicts in Large Language Models

# 摘要

> 大型语言模型（LLMs）在医疗领域展现出了巨大潜力，但它们在应对快速发展的医学知识时面临诸多挑战，可能导致治疗建议过时或相互矛盾。本研究聚焦于LLMs对临床指南演变的响应，深入探讨了概念漂移和内部不一致的问题。为此，我们开发了DriftMedQA基准测试，模拟指南的演变过程，并评估了多种LLMs的时序可靠性。通过对7个最先进模型在4,290个场景中的全面评估，我们发现模型在拒绝过时建议和避免支持相互矛盾的指导方面存在明显困难。此外，我们还探索了两种缓解策略：基于检索增强生成（Retrieval-Augmented Generation）和通过直接偏好优化（Direct Preference Optimization）进行的偏好微调。虽然每种方法都显著提升了模型性能，但将两者结合使用却能带来最一致和可靠的结果。这些研究发现凸显了提升LLMs对时序变化的鲁棒性的重要性，以确保其在临床实践中的更可靠应用。

> Large Language Models (LLMs) have great potential in the field of health care, yet they face great challenges in adapting to rapidly evolving medical knowledge. This can lead to outdated or contradictory treatment suggestions. This study investigated how LLMs respond to evolving clinical guidelines, focusing on concept drift and internal inconsistencies. We developed the DriftMedQA benchmark to simulate guideline evolution and assessed the temporal reliability of various LLMs. Our evaluation of seven state-of-the-art models across 4,290 scenarios demonstrated difficulties in rejecting outdated recommendations and frequently endorsing conflicting guidance. Additionally, we explored two mitigation strategies: Retrieval-Augmented Generation and preference fine-tuning via Direct Preference Optimization. While each method improved model performance, their combination led to the most consistent and reliable results. These findings underscore the need to improve LLM robustness to temporal shifts to ensure more dependable applications in clinical practice.

[Arxiv](https://arxiv.org/abs/2505.07968)