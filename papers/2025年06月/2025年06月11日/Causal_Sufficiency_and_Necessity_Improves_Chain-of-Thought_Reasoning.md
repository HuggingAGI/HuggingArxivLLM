# 因果充分性和必要性提升链式推理能力

发布时间：2025年06月11日

`LLM应用` `人工智能` `推理系统`

> Causal Sufficiency and Necessity Improves Chain-of-Thought Reasoning

# 摘要

> Chain-of-Thought (CoT) 提示在赋予大型语言模型 (LLMs) 复杂推理能力方面发挥着不可或缺的作用。然而，CoT 当前面临两个根本性挑战：(1) 完备性，即确保生成的中间推理步骤全面涵盖并支持最终结论；(2) 必要性，即识别真正对最终答案正确性不可或缺的推理步骤。我们提出了一种因果框架，通过完备性和必要性这两个视角来刻画 CoT 推理过程。引入因果概率中的完备性和必要性概率，不仅能够确定哪些步骤在逻辑上对预测结果是充分或必要的，还能量化这些步骤在不同干预场景下对最终推理结果的实际影响，从而实现对缺失步骤的自动补充和冗余步骤的自动剪裁。在多个数学和常识推理基准测试中进行的广泛实验结果证实，与现有方法相比，我们的方法在推理效率和减少令牌使用方面均取得了显著提升，同时保持了准确性。我们的研究为提升 LLM 的推理性能和成本效益提供了一个有前景的方向。


> Chain-of-Thought (CoT) prompting plays an indispensable role in endowing large language models (LLMs) with complex reasoning capabilities. However, CoT currently faces two fundamental challenges: (1) Sufficiency, which ensures that the generated intermediate inference steps comprehensively cover and substantiate the final conclusion; and (2) Necessity, which identifies the inference steps that are truly indispensable for the soundness of the resulting answer. We propose a causal framework that characterizes CoT reasoning through the dual lenses of sufficiency and necessity. Incorporating causal Probability of Sufficiency and Necessity allows us not only to determine which steps are logically sufficient or necessary to the prediction outcome, but also to quantify their actual influence on the final reasoning outcome under different intervention scenarios, thereby enabling the automated addition of missing steps and the pruning of redundant ones. Extensive experimental results on various mathematical and commonsense reasoning benchmarks confirm substantial improvements in reasoning efficiency and reduced token usage without sacrificing accuracy. Our work provides a promising direction for improving LLM reasoning performance and cost-effectiveness.

[Arxiv](https://arxiv.org/abs/2506.09853)