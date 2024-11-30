# 在合作与互动智能体的引导下掌握工具使用技能

发布时间：2024年03月05日

`Agent`

> Learning to Use Tools via Cooperative and Interactive Agents

# 摘要

> 工具学习赋予了LLMs以运用外部工具扩展自身能力的能力，现有的解决方案是让一个基于LLM的单一代理循环选取并执行工具，然后将执行结果反馈至后续的动作预测中。不过，在面对复杂的任务挑战时，由于单个LLM固有的多样化动作执行限制及任务失败后的适应性纠错困难，此类方法可能遭受性能下滑的问题。为此，我们创新性地提出了一种名为ConAgents的合作与交互智能体框架，它将工具学习的过程划分为接地、执行和观察三大智能体模块，并引入了迭代校准机制IterCali，使得智能体能根据工具环境的反馈动态调整自身策略。实验证明，ConAgents在三个数据集上均展现出卓越的表现（比如，相比最新技术基准提高了6个百分点），并且我们还对框架的高效性和一致性进行了深入细致的分析。

> Tool learning empowers large language models (LLMs) as agents to use external tools to extend their capability. Existing methods employ one single LLM-based agent to iteratively select and execute tools, thereafter incorporating the result into the next action prediction. However, they still suffer from potential performance degradation when addressing complex tasks due to: (1) the limitation of the inherent capability of a single LLM to perform diverse actions, and (2) the struggle to adaptively correct mistakes when the task fails. To mitigate these problems, we propose the ConAgents, a Cooperative and interactive Agents framework, which modularizes the workflow of tool learning into Grounding, Execution, and Observing agents. We also introduce an iterative calibration (IterCali) method, enabling the agents to adapt themselves based on the feedback from the tool environment. Experiments conducted on three datasets demonstrate the superiority of our ConAgents (e.g., 6 point improvement over the SOTA baseline). We further provide fine-granularity analysis for the efficiency and consistency of our framework.

[Arxiv](https://arxiv.org/abs/2403.03031)