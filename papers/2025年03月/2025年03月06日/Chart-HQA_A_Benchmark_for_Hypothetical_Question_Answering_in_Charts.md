# Chart-HQA：图表假设问答基准测试

发布时间：2025年03月06日

`LLM应用` `多模态` `图表理解`

> Chart-HQA: A Benchmark for Hypothetical Question Answering in Charts

# 摘要

> 多模态大型语言模型（MLLMs）凭借其卓越的视觉语义理解能力吸引了广泛关注。现有图表基准测试主要评估MLLMs从图表中提取信息回答问题的能力，但忽视了模型固有的输出偏差问题——即模型依赖参数记忆而非真正理解图表内容来回答问题。为解决这一问题，我们提出了创新的图表假设问答（HQA）任务，通过附加假设条件，迫使模型基于图表内容进行反事实推理。同时，我们开发了HAI——一种人机协作的数据合成方法，结合LLMs强大的文本编辑能力和人类专业知识，以低成本生成多样且高质量的HQA数据。利用HAI，我们构建了Chart-HQA，这是一个基于公开数据源打造的高难度基准测试。在涵盖不同规模的18个MLLMs上的评估结果显示，当前模型在HQA任务中面临显著的泛化挑战，推理性能表现不均衡。

> Multimodal Large Language Models (MLLMs) have garnered significant attention for their strong visual-semantic understanding. Most existing chart benchmarks evaluate MLLMs' ability to parse information from charts to answer questions.However, they overlook the inherent output biases of MLLMs, where models rely on their parametric memory to answer questions rather than genuinely understanding the chart content. To address this limitation, we introduce a novel Chart Hypothetical Question Answering (HQA) task, which imposes assumptions on the same question to compel models to engage in counterfactual reasoning based on the chart content. Furthermore, we introduce HAI, a human-AI interactive data synthesis approach that leverages the efficient text-editing capabilities of LLMs alongside human expert knowledge to generate diverse and high-quality HQA data at a low cost. Using HAI, we construct Chart-HQA, a challenging benchmark synthesized from publicly available data sources. Evaluation results on 18 MLLMs of varying model sizes reveal that current models face significant generalization challenges and exhibit imbalanced reasoning performance on the HQA task.

[Arxiv](https://arxiv.org/abs/2503.04095)