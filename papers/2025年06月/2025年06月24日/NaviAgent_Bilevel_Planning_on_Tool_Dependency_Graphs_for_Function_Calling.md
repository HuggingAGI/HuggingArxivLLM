# NaviAgent：基于工具依赖图的双层规划实现函数调用

发布时间：2025年06月24日

`LLM应用` `系统架构` `模型优化`

> NaviAgent: Bilevel Planning on Tool Dependency Graphs for Function Calling

# 摘要

> LLMs对静态知识的依赖和脆弱的工具调用严重阻碍了复杂异构工具链的编排，特别是在大规模场景下。现有方法通常采用 rigid single-path execution，导致较差的错误恢复能力和指数级增长的搜索空间。我们引入NaviAgent，这是一种基于图导航的双层规划架构，用于实现稳健的函数调用，包含Multi-Path Decider和Graph-Encoded Navigator。作为LLM驱动的代理，Multi-Path Decider定义了一个四维决策空间，持续感知环境状态，动态选择最优动作以全面覆盖所有工具调用场景。Graph-Encoded Navigator构建了一个工具依赖异构图（TDHG），其中节点嵌入显式融合API架构结构与历史调用行为。它还集成了一个新型启发式搜索策略，引导Decider走向高效且高度成功的工具链，即使面对未见过的工具组合也能如此。实验表明，NaviAgent在所有基础模型和任务复杂度下均持续展现出最高任务成功率（TSR），分别在Qwen2.5-14B、Qwen2.5-32B和Deepseek-V3上比平均基线（ReAct、ToolLLM、α-UMI）高出13.5%、16.4%和19.0%。其执行步骤通常与最高效基线相差仅一步，确保了质量和效率的强劲平衡。值得注意的是，经过微调的Qwen2.5-14B模型实现了49.5%的TSR，超越了我们架构下规模大得多的32B模型（44.9%）。引入Graph-Encoded Navigator进一步平均提升了2.4个TSR百分点，大型模型（Deepseek-V3和GPT-4o）在复杂任务上提升甚至超过9个百分点，凸显其在工具链编排中的核心作用。

> LLMs' reliance on static knowledge and fragile tool invocation severely hinders the orchestration of complex, heterogeneous toolchains, particularly at large scales. Existing methods typically use rigid single-path execution, resulting in poor error recovery and exponentially growing search spaces. We introduce NaviAgent, a graph-navigated bilevel planning architecture for robust function calling, comprising a Multi-Path Decider and Graph-Encoded Navigator. As an LLM-powered agent, the Multi-Path Decider defines a four-dimensional decision space and continuously perceives environmental states, dynamically selecting the optimal action to fully cover all tool invocation scenarios. The Graph-Encoded Navigator constructs a Tool Dependency Heterogeneous Graph (TDHG), where node embeddings explicitly fuse API schema structure with historical invocation behavior. It also integrates a novel heuristic search strategy that guides the Decider toward efficient and highly successful toolchains, even for unseen tool combinations. Experiments show that NaviAgent consistently achieves the highest task success rate (TSR) across all foundation models and task complexities, outperforming the average baselines (ReAct, ToolLLM, α-UMI) by 13.5%, 16.4%, and 19.0% on Qwen2.5-14B, Qwen2.5-32B, and Deepseek-V3, respectively. Its execution steps are typically within one step of the most efficient baseline, ensuring a strong balance between quality and efficiency. Notably, a fine-tuned Qwen2.5-14B model achieves a TSR of 49.5%, surpassing the much larger 32B model (44.9%) under our architecture. Incorporating the Graph-Encoded Navigator further boosts TSR by an average of 2.4 points, with gains up over 9 points on complex tasks for larger models (Deepseek-V3 and GPT-4o), highlighting its essential role in toolchain orchestration.

[Arxiv](https://arxiv.org/abs/2506.19500)