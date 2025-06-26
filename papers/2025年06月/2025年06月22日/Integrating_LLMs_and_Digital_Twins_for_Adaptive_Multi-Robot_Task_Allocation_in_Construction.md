# # 结合大型语言模型与数字孪生实现建筑领域的自适应多机器人任务分配

发布时间：2025年06月22日

`LLM应用`

> Integrating LLMs and Digital Twins for Adaptive Multi-Robot Task Allocation in Construction

# 摘要

> 多机器人系统正成为工业领域提升生产力、安全性和适应性的有前景的解决方案。然而，在建筑工地等动态且不确定的环境中有效协调多个机器人仍具挑战性，尤其是面对材料延迟、意外场地状况和天气干扰等不可预测因素。为应对这些挑战，本研究提出了一种自适应任务分配框架，该框架充分利用了数字孪生、整数规划（IP）和大型语言模型（LLMs）的协同潜力。多机器人任务分配问题通过一个IP模型正式定义和求解，该模型考虑了任务依赖性、机器人异质性、调度约束和重新规划需求。引入了一种基于叙述驱动的计划适应机制，其中非结构化的自然语言输入由LLM进行解释，优化约束自主更新，从而实现人机协同的灵活性，无需手动编码。开发了一个基于数字孪生的系统，以实现实时物理操作与数字表示的同步。这种闭环反馈框架确保了系统能够动态响应现场的持续变化。案例研究表明，优化算法的计算效率以及多个LLMs的推理性能，其中表现最佳的模型在约束和参数提取方面准确率超过97%。结果证实了所提方法的实用性、适应性和跨领域适用性。

> Multi-robot systems are emerging as a promising solution to the growing demand for productivity, safety, and adaptability across industrial sectors. However, effectively coordinating multiple robots in dynamic and uncertain environments, such as construction sites, remains a challenge, particularly due to unpredictable factors like material delays, unexpected site conditions, and weather-induced disruptions. To address these challenges, this study proposes an adaptive task allocation framework that strategically leverages the synergistic potential of Digital Twins, Integer Programming (IP), and Large Language Models (LLMs). The multi-robot task allocation problem is formally defined and solved using an IP model that accounts for task dependencies, robot heterogeneity, scheduling constraints, and re-planning requirements. A mechanism for narrative-driven schedule adaptation is introduced, in which unstructured natural language inputs are interpreted by an LLM, and optimization constraints are autonomously updated, enabling human-in-the-loop flexibility without manual coding. A digital twin-based system has been developed to enable real-time synchronization between physical operations and their digital representations. This closed-loop feedback framework ensures that the system remains dynamic and responsive to ongoing changes on site. A case study demonstrates both the computational efficiency of the optimization algorithm and the reasoning performance of several LLMs, with top-performing models achieving over 97% accuracy in constraint and parameter extraction. The results confirm the practicality, adaptability, and cross-domain applicability of the proposed methods.

[Arxiv](https://arxiv.org/abs/2506.18178)