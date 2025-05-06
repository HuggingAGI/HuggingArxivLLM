# # PIPA: 诊断交互式规划代理的统一评估协议

发布时间：2025年05月02日

`Agent

摘要讨论了智能代理在任务规划中的应用，特别是评估方法，属于智能代理的研究领域。` `智能代理` `人工智能`

> PIPA: A Unified Evaluation Protocol for Diagnosing Interactive Planning Agents

# 摘要

> 随着大型语言模型（LLMs）在指令理解和上下文处理能力的不断提升，我们迎来了一个由各类智能代理驱动的应用新时代。其中，任务规划代理在需要处理复杂内部流程的现实场景中表现尤为突出，这些场景包括上下文理解、工具管理以及响应生成。然而，现有的评估基准主要通过任务完成度来衡量代理的整体效果。我们提出，仅关注任务完成度可能无法完全满足用户需求，因为用户与代理的整个交互过程相关，而不仅仅是最终结果。为了解决这一问题，我们推出了PIPA，一个基于部分可观察马尔可夫决策过程（POMDP）范式的统一评估协议。通过一系列细致的评估标准，PIPA能够全面评估代理性能，帮助研究者和实践者深入分析代理决策过程中的优势与不足。我们的研究表明，不同代理在行为的不同阶段各有所长，而用户满意度则由最终结果和中间行为共同决定。此外，我们还探讨了未来的发展方向，包括多智能体协作系统以及任务规划中用户模拟器的局限性。

> The growing capabilities of large language models (LLMs) in instruction-following and context-understanding lead to the era of agents with numerous applications. Among these, task planning agents have become especially prominent in realistic scenarios involving complex internal pipelines, such as context understanding, tool management, and response generation. However, existing benchmarks predominantly evaluate agent performance based on task completion as a proxy for overall effectiveness. We hypothesize that merely improving task completion is misaligned with maximizing user satisfaction, as users interact with the entire agentic process and not only the end result. To address this gap, we propose PIPA, a unified evaluation protocol that conceptualizes the behavioral process of interactive task planning agents within a partially observable Markov Decision Process (POMDP) paradigm. The proposed protocol offers a comprehensive assessment of agent performance through a set of atomic evaluation criteria, allowing researchers and practitioners to diagnose specific strengths and weaknesses within the agent's decision-making pipeline. Our analyses show that agents excel in different behavioral stages, with user satisfaction shaped by both outcomes and intermediate behaviors. We also highlight future directions, including systems that leverage multiple agents and the limitations of user simulators in task planning.

[Arxiv](https://arxiv.org/abs/2505.01592)