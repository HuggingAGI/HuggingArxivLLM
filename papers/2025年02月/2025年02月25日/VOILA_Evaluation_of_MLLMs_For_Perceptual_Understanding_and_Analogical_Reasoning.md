# VOILA：多模态大语言模型的感知理解与类比推理评估

发布时间：2025年02月25日

`LLM应用` `计算机视觉` `人工智能评估`

> VOILA: Evaluation of MLLMs For Perceptual Understanding and Analogical Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）正在成为连接视觉与文本信息的强力工具。尽管它们在视觉理解方面表现出色，但如何衡量其跨图像抽象推理能力仍是难题。为此，我们推出VOILA——一个大规模、开放式的动态基准测试，专注于评估MLLMs的感知理解与抽象关系推理。VOILA采用视觉类比映射方法，要求模型根据两组图像生成完成类比关系的图像，无需依赖预设选项。实验结果表明，VOILA中的类比推理任务对MLLMs提出了严峻挑战。通过多步骤分析，我们发现现有MLLMs在理解图像间关系方面存在明显短板，且在高级关系推理能力上仍有待提升。值得注意的是，采用从简到繁的提示策略可显著改善模型表现。在开源模型和GPT-4o上的全面评估显示，针对文本答案，最具挑战性场景下的最佳准确率仅为13%（LLaMa 3.2），即使是简单任务也只有29%（GPT-4o），而人类在两种难度下的准确率均显著高于70%。

> Multimodal Large Language Models (MLLMs) have become a powerful tool for integrating visual and textual information. Despite their exceptional performance on visual understanding benchmarks, measuring their ability to reason abstractly across multiple images remains a significant challenge. To address this, we introduce VOILA, a large-scale, open-ended, dynamic benchmark designed to evaluate MLLMs' perceptual understanding and abstract relational reasoning. VOILA employs an analogical mapping approach in the visual domain, requiring models to generate an image that completes an analogy between two given image pairs, reference and application, without relying on predefined choices. Our experiments demonstrate that the analogical reasoning tasks in VOILA present a challenge to MLLMs. Through multi-step analysis, we reveal that current MLLMs struggle to comprehend inter-image relationships and exhibit limited capabilities in high-level relational reasoning. Notably, we observe that performance improves when following a multi-step strategy of least-to-most prompting. Comprehensive evaluations on open-source models and GPT-4o show that on text-based answers, the best accuracy for challenging scenarios is 13% (LLaMa 3.2) and even for simpler tasks is only 29% (GPT-4o), while human performance is significantly higher at 70% across both difficulty levels.

[Arxiv](https://arxiv.org/abs/2503.00043)