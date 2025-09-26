# SoM-1K：材料力学一千题基准数据集

发布时间：2025年09月25日

`LLM应用` `工业与制造`

> SoM-1K: A Thousand-Problem Benchmark Dataset for Strength of Materials

# 摘要

> 基础模型虽在各领域展现卓越能力，但在复杂多模态工程问题上的表现仍有待深入探索。为此，我们推出SoM-1K——首个大规模多模态基准数据集，专门用于评估基础模型在材料力学（SoM）问题上的性能。该数据集涵盖1065个带标注的SoM问题，同时包含文本问题描述与示意图，真实还原了工程场景中的任务需求。鉴于现有基础模型对复杂视觉信息的理解能力有限，我们提出一种名为“图像描述（DoI）”的新型提示策略——通过专家生成严谨的图文描述作为上下文。我们对8个代表性基础模型进行了评估，涵盖大型语言模型（LLMs）与视觉语言模型（VLMs）。结果显示，现有基础模型在这类工程问题上表现不佳：最优模型准确率仅达56.6%。值得注意的是，当LLMs配备DoI时，其性能常优于直接输入视觉图的VLMs。深入的错误分析揭示，DoI在减少视觉误判方面起到关键作用，这意味着对现有基础模型而言，准确的文本描述可能比直接图像输入更有效。本研究为工程AI构建了严格的评估基准，并凸显了提升基础模型多模态推理能力的迫切性——尤其是在科学与工程场景中。

> Foundation models have shown remarkable capabilities in various domains, but their performance on complex, multimodal engineering problems remains largely unexplored. We introduce SoM-1K, the first large-scale multimodal benchmark dataset dedicated to evaluating foundation models on problems in the strength of materials (SoM). The dataset, which contains 1,065 annotated SoM problems, mirrors real-world engineering tasks by including both textual problem statements and schematic diagrams. Due to the limited capabilities of current foundation models in understanding complicated visual information, we propose a novel prompting strategy called Descriptions of Images (DoI), which provides rigorous expert-generated text descriptions of the visual diagrams as the context. We evaluate eight representative foundation models, including both large language models (LLMs) and vision language models (VLMs). Our results show that current foundation models struggle significantly with these engineering problems, with the best-performing model achieving only 56.6% accuracy. Interestingly, we found that LLMs, when provided with DoI, often outperform VLMs provided with visual diagrams. A detailed error analysis reveals that DoI plays a crucial role in mitigating visual misinterpretation errors, suggesting that accurate text-based descriptions can be more effective than direct image input for current foundation models. This work establishes a rigorous benchmark for engineering AI and highlights a critical need for developing more robust multimodal reasoning capabilities in foundation models, particularly in scientific and engineering contexts.

[Arxiv](https://arxiv.org/abs/2509.21079)