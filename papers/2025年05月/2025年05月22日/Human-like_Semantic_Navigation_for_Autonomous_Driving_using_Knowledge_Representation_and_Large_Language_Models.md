# 基于知识表示和大型语言模型的类人语义导航自动驾驶

发布时间：2025年05月22日

`LLM应用` `自动驾驶` `自动驾驶`

> Human-like Semantic Navigation for Autonomous Driving using Knowledge Representation and Large Language Models

# 摘要

> 自动驾驶车辆的全自动化仍是未解难题，尤其在需要实时应变的城市环境中。现有系统受限于对预定义地图信息的过度依赖，难以应对道路布局突变、临时绕行或地图数据缺失等复杂情况。本研究提出了一种创新方案：利用大型语言模型将非正式导航指令转化为结构化的逻辑推理，进而生成Answer Set Programming（ASP）规则。ASP的非单调推理特性使自动驾驶车辆无需依赖预设地图即可灵活应对场景变化。我们通过实验验证了LLMs生成的ASP约束能够将现实城市驾驶逻辑转化为形式化知识表示。通过自动化非正式导航指令到逻辑规则的转换，我们的方法显著提升了自动驾驶导航的适应性和可解释性。实验结果证实，基于LLM的ASP规则生成支持语义决策，为动态导航规划提供了一个与人类沟通导航意图方式相契合的可解释框架。


> Achieving full automation in self-driving vehicles remains a challenge, especially in dynamic urban environments where navigation requires real-time adaptability. Existing systems struggle to handle navigation plans when faced with unpredictable changes in road layouts, spontaneous detours, or missing map data, due to their heavy reliance on predefined cartographic information. In this work, we explore the use of Large Language Models to generate Answer Set Programming rules by translating informal navigation instructions into structured, logic-based reasoning. ASP provides non-monotonic reasoning, allowing autonomous vehicles to adapt to evolving scenarios without relying on predefined maps. We present an experimental evaluation in which LLMs generate ASP constraints that encode real-world urban driving logic into a formal knowledge representation. By automating the translation of informal navigation instructions into logical rules, our method improves adaptability and explainability in autonomous navigation. Results show that LLM-driven ASP rule generation supports semantic-based decision-making, offering an explainable framework for dynamic navigation planning that aligns closely with how humans communicate navigational intent.

[Arxiv](https://arxiv.org/abs/2505.16498)