# 多维度一致性优化语言模型的推理能力

发布时间：2025年03月04日

`LLM理论

摘要讨论了大型语言模型在推理任务中对输入变化的敏感性，并提出了一种理论框架来系统性地测试和提升模型在不同输入变化下的答案一致性。这属于对LLM内在机制和性能的理论分析与改进，因此归类为LLM理论。` `数学推理` `大型语言模型`

> Multidimensional Consistency Improves Reasoning in Language Models

# 摘要

> 尽管大型语言模型（LLMs）能够处理一些复杂的推理任务，但它们对输入变化极其敏感，这可能导致不同的解题路径和最终答案。因此，输入变化下的一致性回答则能体现更强的信心。基于这一观察，我们提出了一种名为{\em 多维推理一致性}的框架，专注于数学问题，系统性地推动模型多样化解题路径以达到最终答案，从而测试它们在多种输入变化下的答案一致性。我们引入了三种变化维度：(i) 提示中示例的顺序，(ii) 问题表述方式，以及 (iii) 使用的语言。在广泛实验中，我们对各种规模的开源先进LLMs进行了测试，结果表明推理一致性因变化维度而异，通过跨维度聚合一致性，我们的框架在单语数据集GSM8K和多语数据集MGSM上均显著提升了数学推理性能，尤其是对较小规模的模型效果更为显著。

> While Large language models (LLMs) have proved able to address some complex reasoning tasks, we also know that they are highly sensitive to input variation, which can lead to different solution paths and final answers. Answer consistency across input variations can thus be taken as a sign of stronger confidence. Leveraging this insight, we introduce a framework, {\em Multidimensional Reasoning Consistency} where, focusing on math problems, models are systematically pushed to diversify solution paths towards a final answer, thereby testing them for answer consistency across multiple input variations. We induce variations in (i) order of shots in prompt, (ii) problem phrasing, and (iii) languages used. Extensive experiments on a large range of open-source state-of-the-art LLMs of various sizes show that reasoning consistency differs by variation dimension, and that by aggregating consistency across dimensions, our framework consistently enhances mathematical reasoning performance on both monolingual dataset GSM8K and multilingual dataset MGSM, especially for smaller models.

[Arxiv](https://arxiv.org/abs/2503.02670)