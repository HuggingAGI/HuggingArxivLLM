# 关注数据差距：评估视觉系统在小数据应用中的表现

发布时间：2025年04月08日

`LLM应用

理由：这篇论文探讨了多模态大语言模型（MLLMs）在小数据集上的实际应用表现，比较了其与仅视觉方法的性能差异，并提出了显式的小数据评估建议。这属于LLM的实际应用和性能评估，因此归类为LLM应用。` `计算机视觉` `生态监测`

> Mind the Gap: Evaluating Vision Systems in Small Data Applications

# 摘要

> AI工具在特定计算机视觉任务中的实际应用建立在“小数据集”基础上，即几百到几千个标注样本。这一小数据场景对于生态监测、医学诊断和工业质量控制等需要昂贵专家标注的应用至关重要。然而，我们发现，随着研究领域越来越关注零样本和少量样本学习，小数据集的重要性被忽视了。我们通过自然世界任务（NeWT）基准测试，比较了多模态大语言模型（MLLMs）和仅视觉方法在不同训练集大小下的表现。结果显示，MLLMs的性能在早期达到 plateau，而仅视觉方法在整个小数据集中持续改进，且性能差距在10个训练样本后显著扩大。这是首次在小数据背景下对这些方法进行全面比较。我们建议在AI研究中加入显式的小数据评估，以更好地将理论进展与实际应用相结合。

> The practical application of AI tools for specific computer vision tasks relies on the "small-data regime" of hundreds to thousands of labeled samples. This small-data regime is vital for applications requiring expensive expert annotations, such as ecological monitoring, medical diagnostics or industrial quality control. We find, however, that computer vision research has ignored the small data regime as evaluations increasingly focus on zero- and few-shot learning. We use the Natural World Tasks (NeWT) benchmark to compare multi-modal large language models (MLLMs) and vision-only methods across varying training set sizes. MLLMs exhibit early performance plateaus, while vision-only methods improve throughout the small-data regime, with performance gaps widening beyond 10 training examples. We provide the first comprehensive comparison between these approaches in small-data contexts and advocate for explicit small-data evaluations in AI research to better bridge theoretical advances with practical deployments.

[Arxiv](https://arxiv.org/abs/2504.06486)