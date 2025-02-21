# # SuperGPQA：将LLM评估扩展至285个学科领域

发布时间：2025年02月20日

`LLM应用` `评估基准` `知识推理`

> SuperGPQA: Scaling LLM Evaluation across 285 Graduate Disciplines

# 摘要

> 大型语言模型（LLMs）在数学、物理和计算机科学等领域表现优异，但人类知识远不止这些主流学科，还包括超过200个专业领域。目前，LLMs在轻工业、农业和服务导向型等众多专业领域的能力尚未得到充分评估。为填补这一空白，我们推出了SuperGPQA，一个涵盖285个学科的研究生水平知识与推理能力评估基准。我们的基准采用了一种创新的人机协同过滤机制，通过迭代优化，结合LLM响应和专家反馈，剔除琐碎或模糊的问题。实验结果显示，现有最先进的LLMs在多个知识领域仍有较大提升空间（例如，专注于推理的DeepSeek-R1模型在SuperGPQA中达到了61.82%的最高准确率），这表明当前模型与人工通用智能之间仍存在显著差距。此外，我们还分享了管理大规模标注过程的经验，涉及80多位专家标注员和一个交互式人机协作系统，为未来类似规模的研究项目提供了宝贵的方法论指导。

> Large language models (LLMs) have demonstrated remarkable proficiency in mainstream academic disciplines such as mathematics, physics, and computer science. However, human knowledge encompasses over 200 specialized disciplines, far exceeding the scope of existing benchmarks. The capabilities of LLMs in many of these specialized fields-particularly in light industry, agriculture, and service-oriented disciplines-remain inadequately evaluated. To address this gap, we present SuperGPQA, a comprehensive benchmark that evaluates graduate-level knowledge and reasoning capabilities across 285 disciplines. Our benchmark employs a novel Human-LLM collaborative filtering mechanism to eliminate trivial or ambiguous questions through iterative refinement based on both LLM responses and expert feedback. Our experimental results reveal significant room for improvement in the performance of current state-of-the-art LLMs across diverse knowledge domains (e.g., the reasoning-focused model DeepSeek-R1 achieved the highest accuracy of 61.82% on SuperGPQA), highlighting the considerable gap between current model capabilities and artificial general intelligence. Additionally, we present comprehensive insights from our management of a large-scale annotation process, involving over 80 expert annotators and an interactive Human-LLM collaborative system, offering valuable methodological guidance for future research initiatives of comparable scope.

[Arxiv](https://arxiv.org/abs/2502.14739)