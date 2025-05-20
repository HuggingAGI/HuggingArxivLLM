# 模块化建设场景下的混合投票式任务分配方法

发布时间：2025年05月19日

`Agent` `机器人技术`

> Hybrid Voting-Based Task Assignment in Modular Construction Scenarios

# 摘要

> 模块化建筑通过场外预制和现场装配，展现出显著优势，但也给机器人自动化带来了复杂的协调难题。在结构化环境中，有效分配任务对于充分发挥多智能体系统的作用至关重要。本文提出了一种创新的混合投票任务分配（HVBTA）框架，旨在优化异构多智能体建筑团队的协作。受人类任务委派推理启发，HVBTA 独特地结合了多种投票机制与大型语言模型（LLM）的能力，实现智能体能力与任务需求之间适应性的精准评估。该框架通过为智能体分配能力概况，并为建筑任务生成详细的需求清单（即任务描述），构建出定量的适应性矩阵。通过预训练的大型语言模型增强的六种不同投票方法对这个矩阵进行分析，从而稳健地识别每个任务的最佳执行者。同时，框架集成了基于冲突的搜索（CBS）进行分散式、无碰撞路径规划，确保机器人团队在装配操作期间高效、安全地进行时空协调。HVBTA 实现了高效、无冲突的任务分配与协调，从而有望实现更快、更精确的模块化装配。目前，我们正在评估 HVBTA 在涉及不同机器人平台和任务复杂性的各种模拟建筑场景中的性能表现。虽然 HVBTA 被设计为适用于任何任务和能力明确可定义的领域，但由于其基于预先规划的建筑流程，它特别适用于解决模块化建筑中多智能体协作机器人面临的严格协调需求。

> Modular construction, involving off-site prefabrication and on-site assembly, offers significant advantages but presents complex coordination challenges for robotic automation. Effective task allocation is critical for leveraging multi-agent systems (MAS) in these structured environments. This paper introduces the Hybrid Voting-Based Task Assignment (HVBTA) framework, a novel approach to optimizing collaboration between heterogeneous multi-agent construction teams. Inspired by human reasoning in task delegation, HVBTA uniquely integrates multiple voting mechanisms with the capabilities of a Large Language Model (LLM) for nuanced suitability assessment between agent capabilities and task requirements. The framework operates by assigning Capability Profiles to agents and detailed requirement lists called Task Descriptions to construction tasks, subsequently generating a quantitative Suitability Matrix. Six distinct voting methods, augmented by a pre-trained LLM, analyze this matrix to robustly identify the optimal agent for each task. Conflict-Based Search (CBS) is integrated for decentralized, collision-free path planning, ensuring efficient and safe spatio-temporal coordination of the robotic team during assembly operations. HVBTA enables efficient, conflict-free assignment and coordination, facilitating potentially faster and more accurate modular assembly. Current work is evaluating HVBTA's performance across various simulated construction scenarios involving diverse robotic platforms and task complexities. While designed as a generalizable framework for any domain with clearly definable tasks and capabilities, HVBTA will be particularly effective for addressing the demanding coordination requirements of multi-agent collaborative robotics in modular construction due to the predetermined construction planning involved.

[Arxiv](https://arxiv.org/abs/2505.13278)