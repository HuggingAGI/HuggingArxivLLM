# 答案之外：你的推理轨迹揭示的远超你的想象

发布时间：2025年04月29日

`LLM理论` `准确性`

> Beyond the Last Answer: Your Reasoning Trace Uncovers More than You Think

# 摘要

> 大型语言模型（LLMs）通过逐步推理解决复杂问题。传统的评估方法是生成完整的推理轨迹，并在结论部分评估最终答案的正确性。本文挑战这一依赖最终答案的做法，提出以下两个问题：最终答案是否能可靠地代表模型的最佳结论？是否存在其他推理路径导致不同结果？为回答这些问题，我们深入分析推理过程中的中间步骤，即子思维，并基于研究结果提出一种新方法。我们的方法基于语言线索，将推理轨迹分割为连续的子思维。首先，我们提示模型从每个中间子思维的终点生成后续内容。然后，我们从不同子思维出发的每条完整续写中提取潜在答案。我们发现，通过聚合这些答案并选择出现频率最高的一个（众数），通常能比仅依赖原始完整轨迹得出的答案获得显著更高的准确率。分析不同子思维得出答案的一致性，可以揭示与模型信心和正确性相关联的特征，这为识别可靠性较低的答案提供了可能性。我们在多种LLMs和具有挑战性的数学推理数据集（AIME2024和AIME2025）上的实验显示了持续的准确率提升，准确率提升分别高达13%和10%。代码实现已开源：https://github.com/hammoudhasan/SubthoughtReasoner.

> Large Language Models (LLMs) leverage step-by-step reasoning to solve complex problems. Standard evaluation practice involves generating a complete reasoning trace and assessing the correctness of the final answer presented at its conclusion. In this paper, we challenge the reliance on the final answer by posing the following two questions: Does the final answer reliably represent the model's optimal conclusion? Can alternative reasoning paths yield different results? To answer these questions, we analyze intermediate reasoning steps, termed subthoughts, and propose a method based on our findings. Our approach involves segmenting a reasoning trace into sequential subthoughts based on linguistic cues. We start by prompting the model to generate continuations from the end-point of each intermediate subthought. We extract a potential answer from every completed continuation originating from different subthoughts. We find that aggregating these answers by selecting the most frequent one (the mode) often yields significantly higher accuracy compared to relying solely on the answer derived from the original complete trace. Analyzing the consistency among the answers derived from different subthoughts reveals characteristics that correlate with the model's confidence and correctness, suggesting potential for identifying less reliable answers. Our experiments across various LLMs and challenging mathematical reasoning datasets (AIME2024 and AIME2025) show consistent accuracy improvements, with gains reaching up to 13\% and 10\% respectively. Implementation is available at: https://github.com/hammoudhasan/SubthoughtReasoner.

[Arxiv](https://arxiv.org/abs/2504.20708)