# 大型语言模型能否胜任AI科学家角色？——评估黑箱系统逆向工程研究

发布时间：2025年05月23日

`LLM理论

摘要讨论了大型语言模型（LLM）在逆向工程黑箱系统中的表现，特别是通过主动干预提升性能。研究分析了模型的局限性及其改进机制，属于对LLM内在机制的理论探讨。` `科学发现` `逆向工程`

> Are Large Language Models Reliable AI Scientists? Assessing Reverse-Engineering of Black-Box Systems

# 摘要

> 利用 AI 创建自主研究人员有望加速科学发现，但实现这一愿景的前提是：AI 模型能否通过行为准确识别黑箱系统的潜在结构？本文探讨了大型语言模型（LLM）在被动观察和主动收集数据两种方式下，识别黑箱函数的能力。我们选取了三种代表不同研究领域的黑箱系统进行测试：程序、形式语言和数学方程，以评估 LLM 的逆向工程能力。

实验结果表明，LLM 无法有效提取观察信息，其性能远低于贝叶斯推理的理想水平。然而，通过引导 LLM 主动干预——即通过特定输入主动查询黑箱以观察输出结果——可以显著提升其性能。这种主动干预使 LLM 能够测试边界情况并完善其推理。将一种 LLM 的干预数据应用于另一种 LLM，我们发现这一改进部分源于参与生成有效干预的过程，与人类学习研究结果相呼应。

进一步分析显示，主动干预有助于 LLM 克服两大常见问题：过度复杂化，即错误假设对黑箱的先验知识；以及忽视，即未能充分纳入观察结果。这些发现为提升 LLM 逆向工程黑箱系统的效能提供了实用指导，为其在科学发现中的应用奠定了基础。

> Using AI to create autonomous researchers has the potential to accelerate scientific discovery. A prerequisite for this vision is understanding how well an AI model can identify the underlying structure of a black-box system from its behavior. In this paper, we explore how well a large language model (LLM) learns to identify a black-box function from passively observed versus actively collected data. We investigate the reverse-engineering capabilities of LLMs across three distinct types of black-box systems, each chosen to represent different problem domains where future autonomous AI researchers may have considerable impact: Program, Formal Language, and Math Equation. Through extensive experiments, we show that LLMs fail to extract information from observations, reaching a performance plateau that falls short of the ideal of Bayesian inference. However, we demonstrate that prompting LLMs to not only observe but also intervene -- actively querying the black-box with specific inputs to observe the resulting output -- improves performance by allowing LLMs to test edge cases and refine their beliefs. By providing the intervention data from one LLM to another, we show that this improvement is partly a result of engaging in the process of generating effective interventions, paralleling results in the literature on human learning. Further analysis reveals that engaging in intervention can help LLMs escape from two common failure modes: overcomplication, where the LLM falsely assumes prior knowledge about the black-box, and overlooking, where the LLM fails to incorporate observations. These insights provide practical guidance for helping LLMs more effectively reverse-engineer black-box systems, supporting their use in making new discoveries.

[Arxiv](https://arxiv.org/abs/2505.17968)