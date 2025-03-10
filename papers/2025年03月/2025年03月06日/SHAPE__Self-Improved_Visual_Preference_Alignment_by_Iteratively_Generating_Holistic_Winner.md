# 形状：一种通过迭代生成整体获胜者实现自我改进的视觉偏好对齐方法

发布时间：2025年03月06日

`LLM应用` `计算机视觉`

> SHAPE : Self-Improved Visual Preference Alignment by Iteratively Generating Holistic Winner

# 摘要

> 大型视觉语言模型 (LVLMs) 依赖偏好对齐来确保可靠性，通过在 ``图像 - 赢得文本 - 失败文本'' 三元组结构的偏好数据上进行微调来引导模型行为。然而，现有方法受限于人类标注数据的多样性和成本，阻碍了 LVLMs 的对齐能力。我们提出 \projectname，一个自监督框架，能够将现有文本-图像对转换为整体偏好三元组，实现更高效、低成本的 LVLM 对齐，无需人工标注。我们的方法使 LVLMs 能够通过迭代改进逐步提升对齐能力。核心设计是构建偏好三元组，其中赢得文本在整体性和质量上优于失败响应，通过微调推动模型达到对齐性能的 ``极致''。对于每个文本-图像对，SHAPE 生成多种视觉增强，并与摘要文本配对作为赢得响应，原始文本作为失败响应。在包括 LLaVA 和 DeepSeek-VL 在内的 12 个基准测试中，SHAPE 在 7B 模型上实现了显著提升：MMVet 提升 +11.3%，MMBench 提升 +1.4%，POPE 提升 +8.0%。定性分析证实了对视觉细节的关注提升以及与整体描述的人类偏好更好地对齐。

> Large Visual Language Models (LVLMs) increasingly rely on preference alignment to ensure reliability, which steers the model behavior via preference fine-tuning on preference data structured as ``image - winner text - loser text'' triplets. However, existing approaches often suffer from limited diversity and high costs associated with human-annotated preference data, hindering LVLMs from fully achieving their intended alignment capabilities. We present \projectname, a self-supervised framework capable of transforming the already abundant supervised text-image pairs into holistic preference triplets for more effective and cheaper LVLM alignment, eliminating the need for human preference annotations. Our approach facilitates LVLMs in progressively enhancing alignment capabilities through iterative self-improvement. The key design rationale is to devise preference triplets where the winner text consistently improves in holisticness and outperforms the loser response in quality, thereby pushing the model to ``strive to the utmost'' of alignment performance through preference fine-tuning. For each given text-image pair, SHAPE introduces multiple visual augmentations and pairs them with a summarized text to serve as the winner response, while designating the original text as the loser response. Experiments across \textbf{12} benchmarks on various model architectures and sizes, including LLaVA and DeepSeek-VL, show that SHAPE achieves significant gains, for example, achieving +11.3\% on MMVet (comprehensive evaluation), +1.4\% on MMBench (general VQA), and +8.0\% on POPE (hallucination robustness) over baselines in 7B models. Notably, qualitative analyses confirm enhanced attention to visual details and better alignment with human preferences for holistic descriptions.

[Arxiv](https://arxiv.org/abs/2503.04858)