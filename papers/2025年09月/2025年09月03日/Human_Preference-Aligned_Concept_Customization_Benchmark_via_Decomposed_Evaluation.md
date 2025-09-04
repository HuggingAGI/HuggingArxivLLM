# 基于分解评估的人类偏好对齐概念定制基准

发布时间：2025年09月03日

`LLM应用` `媒体与娱乐`

> Human Preference-Aligned Concept Customization Benchmark via Decomposed Evaluation

# 摘要

> 评估概念定制颇具挑战，因其需全面衡量生成提示与概念图像的保真度。此外，多概念评估比单概念评估难度大得多，不仅要对每个概念进行细致评估，还需考察概念间的相互作用。尽管人类能直观评判生成图像，现有指标却常给出过窄或过泛的评价，与人类偏好脱节。为此，我们提出分解GPT分数（D-GPTScore）——一种新颖的人类对齐评估方法，它将评估标准拆解为更精细的维度，并借助多模态大型语言模型（MLLM）进行多维度评估整合。此外，我们发布了人类偏好对齐的概念定制基准（CC-AlignBench），该数据集涵盖单概念与多概念任务，支持跨难度范围的阶段性评估——从个体动作到多人交互场景。我们的方法在该基准上显著优于现有方法，与人类偏好的相关性更高。本研究为概念定制评估树立了新标准，并指明了未来研究的核心挑战。相关基准及材料可访问https://github.com/ReinaIshikawa/D-GPTScore获取。

> Evaluating concept customization is challenging, as it requires a comprehensive assessment of fidelity to generative prompts and concept images. Moreover, evaluating multiple concepts is considerably more difficult than evaluating a single concept, as it demands detailed assessment not only for each individual concept but also for the interactions among concepts. While humans can intuitively assess generated images, existing metrics often provide either overly narrow or overly generalized evaluations, resulting in misalignment with human preference. To address this, we propose Decomposed GPT Score (D-GPTScore), a novel human-aligned evaluation method that decomposes evaluation criteria into finer aspects and incorporates aspect-wise assessments using Multimodal Large Language Model (MLLM). Additionally, we release Human Preference-Aligned Concept Customization Benchmark (CC-AlignBench), a benchmark dataset containing both single- and multi-concept tasks, enabling stage-wise evaluation across a wide difficulty range -- from individual actions to multi-person interactions. Our method significantly outperforms existing approaches on this benchmark, exhibiting higher correlation with human preferences. This work establishes a new standard for evaluating concept customization and highlights key challenges for future research. The benchmark and associated materials are available at https://github.com/ReinaIshikawa/D-GPTScore.

[Arxiv](https://arxiv.org/abs/2509.03385)