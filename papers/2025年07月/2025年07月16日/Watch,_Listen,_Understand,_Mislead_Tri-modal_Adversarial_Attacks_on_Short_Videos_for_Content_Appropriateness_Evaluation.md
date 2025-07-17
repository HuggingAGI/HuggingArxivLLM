# 看、听、理解、误导：短视频内容适宜性评估中的三模态对抗攻击

发布时间：2025年07月16日

`LLM应用` `内容审核` `短视频`

> Watch, Listen, Understand, Mislead: Tri-modal Adversarial Attacks on Short Videos for Content Appropriateness Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）在内容审核领域的应用日益广泛，但在短视频场景中的稳定性仍待深入研究。现有的安全评估大多局限于单模态攻击，未能有效应对组合攻击威胁。本文提出了一套全面的MLLMs三模态安全性评估框架。首先，我们推出了Short-Video Multimodal Adversarial (SVMA)数据集，该数据集包含多种短视频，并附带了人工引导的合成对抗攻击。其次，我们提出了ChimeraBreak，这是一种创新的三模态攻击策略，能够同时挑战视觉、听觉和语义推理路径。在最先进的MLLMs上进行的大量实验揭示了显著的安全漏洞，且攻击成功率（ASR）极高。我们的研究发现模型存在不同的失效模式，显示出模型在误分类良性或违规内容时的偏见。我们通过LLM-as-a-judge评估结果，展示了攻击推理的有效性。我们的数据集和研究发现为开发更 robust 和安全的MLLMs 提供了重要见解。

> Multimodal Large Language Models (MLLMs) are increasingly used for content moderation, yet their robustness in short-form video contexts remains underexplored. Current safety evaluations often rely on unimodal attacks, failing to address combined attack vulnerabilities. In this paper, we introduce a comprehensive framework for evaluating the tri-modal safety of MLLMs. First, we present the Short-Video Multimodal Adversarial (SVMA) dataset, comprising diverse short-form videos with human-guided synthetic adversarial attacks. Second, we propose ChimeraBreak, a novel tri-modal attack strategy that simultaneously challenges visual, auditory, and semantic reasoning pathways. Extensive experiments on state-of-the-art MLLMs reveal significant vulnerabilities with high Attack Success Rates (ASR). Our findings uncover distinct failure modes, showing model biases toward misclassifying benign or policy-violating content. We assess results using LLM-as-a-judge, demonstrating attack reasoning efficacy. Our dataset and findings provide crucial insights for developing more robust and safe MLLMs.

[Arxiv](https://arxiv.org/abs/2507.11968)