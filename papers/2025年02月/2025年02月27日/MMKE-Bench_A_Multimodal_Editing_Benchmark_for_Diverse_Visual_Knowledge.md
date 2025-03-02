# MMKE-Bench：多模态编辑基准测试——针对多样化视觉知识的评估

发布时间：2025年02月27日

`LLM应用` `人工智能` `计算机视觉`

> MMKE-Bench: A Multimodal Editing Benchmark for Diverse Visual Knowledge

# 摘要

> 知识编辑技术已成为更新大型语言模型和多模态模型事实知识的必备工具，使它们无需从头重新训练即可纠正过时或不准确的信息。然而，现有的多模态知识编辑基准主要关注于以简单三元组形式表示的实体级别知识，这些基准未能捕捉到现实世界中多模态信息的复杂性。为了解决这一问题，我们引入了 MMKE-Bench，这是一个全面的多模态知识编辑基准，旨在评估 LMMs 在现实场景中编辑多样化视觉知识的能力。

MMKE-Bench 通过纳入三种编辑任务来克服这些限制：视觉实体编辑、视觉语义编辑和用户特定编辑。此外，MMKE-Bench 使用自由形式的自然语言来表示和编辑知识，提供了一种更灵活和有效的格式。该基准包含 33 个广泛类别的 2,940 个知识条目和 8,363 张图像，并通过自动生成并经过人工验证的评估问题进行测试。

我们评估了五种最先进的知识编辑方法在三种突出的 LMMs 上的表现，发现没有一种方法能在所有标准上都表现出色，而视觉和用户特定的编辑尤其具有挑战性。MMKE-Bench 为评估多模态知识编辑技术的鲁棒性设立了新标准，推动了这一快速发展的领域不断进步。

> Knowledge editing techniques have emerged as essential tools for updating the factual knowledge of large language models (LLMs) and multimodal models (LMMs), allowing them to correct outdated or inaccurate information without retraining from scratch. However, existing benchmarks for multimodal knowledge editing primarily focus on entity-level knowledge represented as simple triplets, which fail to capture the complexity of real-world multimodal information. To address this issue, we introduce MMKE-Bench, a comprehensive MultiModal Knowledge Editing Benchmark, designed to evaluate the ability of LMMs to edit diverse visual knowledge in real-world scenarios. MMKE-Bench addresses these limitations by incorporating three types of editing tasks: visual entity editing, visual semantic editing, and user-specific editing. Besides, MMKE-Bench uses free-form natural language to represent and edit knowledge, offering a more flexible and effective format. The benchmark consists of 2,940 pieces of knowledge and 8,363 images across 33 broad categories, with evaluation questions automatically generated and human-verified. We assess five state-of-the-art knowledge editing methods on three prominent LMMs, revealing that no method excels across all criteria, and that visual and user-specific edits are particularly challenging. MMKE-Bench sets a new standard for evaluating the robustness of multimodal knowledge editing techniques, driving progress in this rapidly evolving field.

[Arxiv](https://arxiv.org/abs/2502.19870)