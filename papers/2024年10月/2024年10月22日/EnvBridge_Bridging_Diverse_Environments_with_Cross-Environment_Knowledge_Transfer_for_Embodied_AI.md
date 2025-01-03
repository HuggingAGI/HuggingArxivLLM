# EnvBridge: 跨环境知识迁移，连接多样环境，赋能具身AI

发布时间：2024年10月22日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLMs）作为代理在机器人操作领域的应用，特别是如何通过EnvBridge方法提升LLM代理的适应性和性能。论文的核心关注点是LLM代理在机器人操作任务中的灵活性和跨环境适用性，这属于Agent（代理）的研究范畴。` `机器人` `人工智能`

> EnvBridge: Bridging Diverse Environments with Cross-Environment Knowledge Transfer for Embodied AI

# 摘要

> 近年来，大型语言模型（LLMs）展现了强大的推理能力，作为代理在各类决策过程中的应用备受瞩目。其中，LLM代理在机器人操作领域的应用尤为引人注目。研究表明，LLMs能够为机器人生成文本规划或控制代码，赋予其极高的灵活性和交互能力。然而，这些方法在灵活性和跨环境适用性方面仍存在挑战，限制了其自主适应能力。当前方法主要分为两类：一类依赖特定环境的策略训练，限制了其可转移性；另一类基于固定提示生成代码动作，面对新环境时性能下降。这些限制严重制约了机器人操作代理的泛化能力。为此，我们提出了名为EnvBridge的新方法，通过将成功的机器人控制代码从源环境迁移到目标环境，利用多环境洞察力提升代理的适应性和性能。我们的方法有效减轻了环境限制，为机器人操作任务提供了更灵活、可泛化的解决方案。我们在RLBench、MetaWorld和CALVIN等机器人操作基准测试中验证了方法的有效性，实验表明LLM代理能够成功利用多样化知识源解决复杂任务，显著增强了其在跨环境规划中的适应性和鲁棒性。

> In recent years, Large Language Models (LLMs) have demonstrated high reasoning capabilities, drawing attention for their applications as agents in various decision-making processes. One notably promising application of LLM agents is robotic manipulation. Recent research has shown that LLMs can generate text planning or control code for robots, providing substantial flexibility and interaction capabilities. However, these methods still face challenges in terms of flexibility and applicability across different environments, limiting their ability to adapt autonomously. Current approaches typically fall into two categories: those relying on environment-specific policy training, which restricts their transferability, and those generating code actions based on fixed prompts, which leads to diminished performance when confronted with new environments. These limitations significantly constrain the generalizability of agents in robotic manipulation. To address these limitations, we propose a novel method called EnvBridge. This approach involves the retention and transfer of successful robot control codes from source environments to target environments. EnvBridge enhances the agent's adaptability and performance across diverse settings by leveraging insights from multiple environments. Notably, our approach alleviates environmental constraints, offering a more flexible and generalizable solution for robotic manipulation tasks. We validated the effectiveness of our method using robotic manipulation benchmarks: RLBench, MetaWorld, and CALVIN. Our experiments demonstrate that LLM agents can successfully leverage diverse knowledge sources to solve complex tasks. Consequently, our approach significantly enhances the adaptability and robustness of robotic manipulation agents in planning across diverse environments.

[Arxiv](https://arxiv.org/abs/2410.16919)