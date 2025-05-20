# ViPlan：基于符号谓词和视觉-语言模型的视觉规划基准测试

发布时间：2025年05月19日

`LLM应用` `视觉规划` `机器人`

> ViPlan: A Benchmark for Visual Planning with Symbolic Predicates and Vision-Language Models

# 摘要

> 将大型语言模型与符号规划器结合，是实现可验证且有依据规划的有前途方向，相较于在自然语言中进行规划。近期研究通过视觉语言模型（VLMs）将这一思路扩展到了视觉领域。然而，由于缺乏统一的环境、评估协议和模型覆盖范围，VLM支持的符号方法与直接使用VLM进行规划的方法之间的严格比较受到了限制。我们推出了ViPlan，这是首个结合符号谓词和VLMs的视觉规划开源基准。ViPlan在两个领域中设计了一系列难度递增的任务：一是经典积木世界规划问题的视觉变体，二是模拟的家庭机器人环境。我们对九种开源VLM家族进行了多规模基准测试，并选用了部分闭源模型，评估了VLM支持的符号规划以及直接使用模型提出行动的方法。实验结果显示，在积木世界中，符号规划优于直接的VLM规划，因为精准的图像接地至关重要；而在家庭机器人任务中，直接VLM规划表现更优，这得益于常识知识和从错误中恢复的能力。最后，我们发现，对于大多数模型和方法而言，Chain-of-Thought提示并未带来显著优势，表明当前VLM在视觉推理方面仍具挑战。

> Integrating Large Language Models with symbolic planners is a promising direction for obtaining verifiable and grounded plans compared to planning in natural language, with recent works extending this idea to visual domains using Vision-Language Models (VLMs). However, rigorous comparison between VLM-grounded symbolic approaches and methods that plan directly with a VLM has been hindered by a lack of common environments, evaluation protocols and model coverage. We introduce ViPlan, the first open-source benchmark for Visual Planning with symbolic predicates and VLMs. ViPlan features a series of increasingly challenging tasks in two domains: a visual variant of the classic Blocksworld planning problem and a simulated household robotics environment. We benchmark nine open-source VLM families across multiple sizes, along with selected closed models, evaluating both VLM-grounded symbolic planning and using the models directly to propose actions. We find symbolic planning to outperform direct VLM planning in Blocksworld, where accurate image grounding is crucial, whereas the opposite is true in the household robotics tasks, where commonsense knowledge and the ability to recover from errors are beneficial. Finally, we show that across most models and methods, there is no significant benefit to using Chain-of-Thought prompting, suggesting that current VLMs still struggle with visual reasoning.

[Arxiv](https://arxiv.org/abs/2505.13180)