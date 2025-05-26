# EVADE: 针向电子商务场景的多模态规避内容检测基准

发布时间：2025年05月23日

`LLM应用

摘要中讨论了LLMs在电子商务中的应用，特别是检测规避性内容，属于应用层面的研究。` `电子商务` `内容安全`

> EVADE: Multimodal Benchmark for Evasive Content Detection in E-Commerce Applications

# 摘要

> 电子商务平台日益依赖大型语言模型 (LLMs) 和视觉语言模型 (VLMs) 来识别非法或误导性产品内容。然而，这些模型仍易受规避性内容的挑战：这类输入（文本或图像）表面合规，实则暗藏违规信息。与传统对抗攻击不同，规避性内容借助模糊性和上下文，使其检测难度倍增。现有鲁棒性基准对此难题指导有限。我们推出EVADE，首个专家策划的中文多模态基准测试，专为评估基础模型在电商中检测规避性内容而设计。该数据集包含2,833个标注文本和13,961张图像，涵盖体型塑造、增高及保健品等六大具挑战性品类。通过Single-Violation和All-in-One两大任务，分别考察短提示下的细粒度推理与长上下文推理能力。值得注意的是，All-in-One设置显著缩小了部分匹配与完全匹配的性能差距，表明清晰规则定义可提升人机判断一致性。我们对26个主流LLMs和VLMs进行了基准测试，发现显著性能差异：即使是最先进的模型，也常误判规避性样本。通过发布EVADE基准及强基线，我们为规避性内容检测设定了首个严格标准，揭示了当前多模态推理的局限，并为电商更安全、透明的内容审核系统奠定了基础。该数据集现已公开，访问地址为https://huggingface.co/datasets/koenshen/EVADE-Bench。

> E-commerce platforms increasingly rely on Large Language Models (LLMs) and Vision-Language Models (VLMs) to detect illicit or misleading product content. However, these models remain vulnerable to evasive content: inputs (text or images) that superficially comply with platform policies while covertly conveying prohibited claims. Unlike traditional adversarial attacks that induce overt failures, evasive content exploits ambiguity and context, making it far harder to detect. Existing robustness benchmarks provide little guidance for this demanding, real-world challenge. We introduce EVADE, the first expert-curated, Chinese, multimodal benchmark specifically designed to evaluate foundation models on evasive content detection in e-commerce. The dataset contains 2,833 annotated text samples and 13,961 images spanning six demanding product categories, including body shaping, height growth, and health supplements. Two complementary tasks assess distinct capabilities: Single-Violation, which probes fine-grained reasoning under short prompts, and All-in-One, which tests long-context reasoning by merging overlapping policy rules into unified instructions. Notably, the All-in-One setting significantly narrows the performance gap between partial and full-match accuracy, suggesting that clearer rule definitions improve alignment between human and model judgment. We benchmark 26 mainstream LLMs and VLMs and observe substantial performance gaps: even state-of-the-art models frequently misclassify evasive samples. By releasing EVADE and strong baselines, we provide the first rigorous standard for evaluating evasive-content detection, expose fundamental limitations in current multimodal reasoning, and lay the groundwork for safer and more transparent content moderation systems in e-commerce. The dataset is publicly available at https://huggingface.co/datasets/koenshen/EVADE-Bench.

[Arxiv](https://arxiv.org/abs/2505.17654)