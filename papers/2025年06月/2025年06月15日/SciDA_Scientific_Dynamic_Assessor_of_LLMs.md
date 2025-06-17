# SciDA: 大型语言模型的科学动态评估工具 SciDA

发布时间：2025年06月15日

`LLM应用` `跨学科`

> SciDA: Scientific Dynamic Assessor of LLMs

# 摘要

> 大型语言模型（LLMs）推理能力的提升使其能够更高效地解决科学问题。因此，建立一个高质量的综合性评估基准具有重要意义，而现有的基准要么面临数据污染的风险，要么缺乏跨学科的覆盖。具体来说，由于LLMs训练数据与静态基准的数据源重叠，模型可能无意中记住了答案的关键词或数字模式（即数据污染），导致对其推理能力（尤其是数值推理）的系统性高估。为此，我们提出了SciDA，一个多学科基准，仅包含超过1000个奥运级别的数值计算问题，并支持每轮推理的随机数值初始化，以避免依赖固定的数值模式。我们使用闭源和开源的顶尖LLMs进行了一系列实验，发现LLMs在随机数值初始化下的性能显著下降。因此，我们提供了对LLMs数值推理能力的真实、无偏评估。数据集可访问https://huggingface.co/datasets/m-a-p/SciDA

> Advancement in Large Language Models (LLMs) reasoning capabilities enables them to solve scientific problems with enhanced efficacy. Thereby, a high-quality benchmark for comprehensive and appropriate assessment holds significance, while existing ones either confront the risk of data contamination or lack involved disciplines. To be specific, due to the data source overlap of LLMs training and static benchmark, the keys or number pattern of answers inadvertently memorized (i.e. data contamination), leading to systematic overestimation of their reasoning capabilities, especially numerical reasoning. We propose SciDA, a multidisciplinary benchmark that consists exclusively of over 1k Olympic-level numerical computation problems, allowing randomized numerical initializations for each inference round to avoid reliance on fixed numerical patterns. We conduct a series of experiments with both closed-source and open-source top-performing LLMs, and it is observed that the performance of LLMs drop significantly under random numerical initialization. Thus, we provide truthful and unbiased assessments of the numerical reasoning capabilities of LLMs. The data is available at https://huggingface.co/datasets/m-a-p/SciDA

[Arxiv](https://arxiv.org/abs/2506.12909)