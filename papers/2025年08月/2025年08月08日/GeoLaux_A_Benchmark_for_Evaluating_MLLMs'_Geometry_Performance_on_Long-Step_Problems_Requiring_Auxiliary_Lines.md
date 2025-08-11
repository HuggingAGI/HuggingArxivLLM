# GeoLaux：评估多语言大模型在多步骤几何问题中辅助线应用能力的基准测试

发布时间：2025年08月08日

`LLM应用` `模型评估`

> GeoLaux: A Benchmark for Evaluating MLLMs' Geometry Performance on Long-Step Problems Requiring Auxiliary Lines

# 摘要

> 几何问题解决（GPS）需要模型具备图示理解、逻辑推理、知识应用、数值计算和辅助线构造能力，这对多模态大型语言模型（MLLMs）提出了严峻挑战。现有评估MLLM几何能力的基准测试忽略了辅助线构造，并且缺乏细致的过程评估，无法全面评估MLLMs的长步骤推理能力。为此，我们提出了GeoLaux基准，包含2,186个几何问题，涵盖计算与证明两类题目。值得注意的是，这些问题平均需要6.51个推理步骤，最多可达24步，其中41.8%的问题需要辅助线构造。基于该数据集，我们设计了一种五维评估策略，从答案正确性、过程正确性、过程质量、辅助线影响以及错误原因五个维度进行综合评估。在13个领先MLLM（包括思考型模型和非思考型模型）上的广泛实验得出三大发现：首先，模型在长步骤推理中表现明显下降（9个模型性能下降超50%）；其次，MLLMs在解决证明问题时更倾向于走捷径，而计算问题则表现更好；第三，模型普遍缺乏辅助线意识，但提升这一能力对整体几何推理能力的提升尤为显著。这些发现不仅确立了GeoLaux作为评估MLLMs辅助线长步骤几何推理能力的基准，也为模型能力的提升提供了重要指导。我们的数据集和代码已包含在补充材料中，并将公开发布。

> Geometry problem solving (GPS) requires models to master diagram comprehension, logical reasoning, knowledge application, numerical computation, and auxiliary line construction. This presents a significant challenge for Multimodal Large Language Models (MLLMs). However, existing benchmarks for evaluating MLLM geometry skills overlook auxiliary line construction and lack fine-grained process evaluation, making them insufficient for assessing MLLMs' long-step reasoning abilities. To bridge these gaps, we present the GeoLaux benchmark, comprising 2,186 geometry problems, incorporating both calculation and proving questions. Notably, the problems require an average of 6.51 reasoning steps, with a maximum of 24 steps, and 41.8% of them need auxiliary line construction. Building on the dataset, we design a novel five-dimensional evaluation strategy assessing answer correctness, process correctness, process quality, auxiliary line impact, and error causes. Extensive experiments on 13 leading MLLMs (including thinking models and non-thinking models) yield three pivotal findings: First, models exhibit substantial performance degradation in extended reasoning steps (nine models demonstrate over 50% performance drop). Second, compared to calculation problems, MLLMs tend to take shortcuts when solving proving problems. Third, models lack auxiliary line awareness, and enhancing this capability proves particularly beneficial for overall geometry reasoning improvement. These findings establish GeoLaux as both a benchmark for evaluating MLLMs' long-step geometric reasoning with auxiliary lines and a guide for capability advancement. Our dataset and code are included in supplementary materials and will be released.

[Arxiv](https://arxiv.org/abs/2508.06226)