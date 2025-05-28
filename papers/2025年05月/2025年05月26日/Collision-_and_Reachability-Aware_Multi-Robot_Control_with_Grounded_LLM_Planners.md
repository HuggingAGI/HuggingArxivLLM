# Collision- and Reachability-Aware Multi-Robot Control with Grounded LLM Planners
具备碰撞与可达性感知能力的多机器人控制系统，采用基于大型语言模型的规划器。

发布时间：2025年05月26日

`LLM应用` `机器人控制`

> Collision- and Reachability-Aware Multi-Robot Control with Grounded LLM Planners

# 摘要

> 大型语言模型（LLMs）在各类机器人控制任务中展现出卓越性能。然而，其在实际应用中的部署仍面临诸多挑战。即便是GPT-o4mini这样的先进LLMs，也经常生成违反物理约束的无效动作计划，例如指示机器人前往无法到达的位置或导致机器人之间发生碰撞。这一问题主要源于LLMs在推理过程中缺乏对物理约束的认识。为了解决这一问题，我们提出了一种创新性框架，将强化学习与可验证奖励（RLVR）相结合，旨在激励LLMs掌握物理约束知识，从而在规划生成过程中实现约束感知推理。在此方法中，只有成功完成控制任务的有效动作计划才会获得正向奖励。我们将此方法应用于两个小型LLMs：不具备推理能力的Qwen2.5-3B-Instruct和具备推理能力的Qwen3-4B。实验结果表明，具备约束感知能力的小型LLMs在BoxNet任务以及基于MuJoCo构建的新开发BoxNet3D环境中，显著优于不具备约束的大规模模型。这项研究凸显了即使对于小型LLMs，通过融入物理约束进行“接地”也能实现高效、可扩展的多机器人控制，在复杂且物理受限的环境中表现尤为突出。


> Large language models (LLMs) have demonstrated strong performance in various robot control tasks. However, their deployment in real-world applications remains constrained. Even state-ofthe-art LLMs, such as GPT-o4mini, frequently produce invalid action plans that violate physical constraints, such as directing a robot to an unreachable location or causing collisions between robots. This issue primarily arises from a lack of awareness of these physical constraints during the reasoning process. To address this issue, we propose a novel framework that integrates reinforcement learning with verifiable rewards (RLVR) to incentivize knowledge of physical constraints into LLMs to induce constraints-aware reasoning during plan generation. In this approach, only valid action plans that successfully complete a control task receive positive rewards. We applied our method to two small-scale LLMs: a non-reasoning Qwen2.5-3B-Instruct and a reasoning Qwen3-4B. The experiment results demonstrate that constraint-aware small LLMs largely outperform large-scale models without constraints, grounded on both the BoxNet task and a newly developed BoxNet3D environment built using MuJoCo. This work highlights the effectiveness of grounding even small LLMs with physical constraints to enable scalable and efficient multi-robot control in complex, physically constrained environments.

[Arxiv](https://arxiv.org/abs/2505.20573)