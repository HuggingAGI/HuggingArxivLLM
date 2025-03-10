# DELTA：借助大型语言模型，实现高效分解的机器人长期任务规划

发布时间：2024年04月04日

`LLM应用` `机器人` `任务规划`

> DELTA: Decomposed Efficient Long-Term Robot Task Planning using Large Language Models

# 摘要

> 近期大型语言模型（LLMs）的突破性进展在众多研究领域掀起了革命性波澜。特别是，将LLMs蕴含的常识知识融入机器人任务与动作规划，已成为提升规划可解释性与执行效率的关键，达到了空前的高度。然而，这些庞大模型所包含的知识量管理起来颇具挑战，常导致基于LLM的规划系统因信息错乱或领域缺失而制定出不切实际的计划。为应对这些挑战并进一步提升规划的可行性与计算效率，我们提出了一种创新的LLM驱动任务规划方法——DELTA。DELTA通过场景图这一环境表示形式，将环境拓扑结构有效转化为可执行知识，从而快速精准地生成规划问题描述。为进一步提升规划效能，我们利用LLMs将长期任务分解为一系列子目标的自回归序列，交由自动化任务规划器高效解决。这一创新使我们得以构建一个更为高效、全自动化的任务规划流程，在规划成功率及规划时间上均实现了对现有技术的重大突破。

> Recent advancements in Large Language Models (LLMs) have sparked a revolution across various research fields. In particular, the integration of common-sense knowledge from LLMs into robot task and motion planning has been proven to be a game-changer, elevating performance in terms of explainability and downstream task efficiency to unprecedented heights. However, managing the vast knowledge encapsulated within these large models has posed challenges, often resulting in infeasible plans generated by LLM-based planning systems due to hallucinations or missing domain information. To overcome these challenges and obtain even greater planning feasibility and computational efficiency, we propose a novel LLM-driven task planning approach called DELTA. For achieving better grounding from environmental topology into actionable knowledge, DELTA leverages the power of scene graphs as environment representations within LLMs, enabling the fast generation of precise planning problem descriptions. For obtaining higher planning performance, we use LLMs to decompose the long-term task goals into an autoregressive sequence of sub-goals for an automated task planner to solve. Our contribution enables a more efficient and fully automatic task planning pipeline, achieving higher planning success rates and significantly shorter planning times compared to the state of the art.

[Arxiv](https://arxiv.org/abs/2404.03275)