# SOLAR：可扩展优化大规模推理架构

发布时间：2025年03月06日

`LLM理论` `人工智能`

> SOLAR: Scalable Optimization of Large-scale Architecture for Reasoning

# 摘要

> 大型语言模型（LLMs）在推理领域表现卓越，但在复杂任务中仍受制于链式思维（CoT）方法，尤其在需要细致拓扑推理的场景下表现不足。为此，我们推出SOLAR（可扩展大规模架构推理优化框架），通过动态优化多种推理拓扑，显著提升了准确性和效率。我们的拓扑注释生成（TAG）系统实现了拓扑数据集的自动化创建与分割，进一步优化了模型的训练与评估流程。同时，我们提出了拓扑扩展框架，通过奖励机制使训练与推理的扩展保持一致，赋予LLMs自适应的任务感知推理能力。在MATH和GSM8K数据集上，SOLAR表现优异：拓扑调优使准确率提升+5%，拓扑奖励提升+9%，而混合扩展更是带来+10.02%的提升。此外，该框架使复杂问题的响应长度减少超过5%，有效降低了推理延迟。为优化奖励系统，我们开发了多任务拓扑奖励模型（M-TRM），它能在单次推理中自主选择最佳拓扑和答案，无需训练多个单任务TRMs（S-TRMs），从而显著降低了训练成本和推理延迟。在性能方面，M-TRM全面超越所有S-TRMs，准确率提升+10%，等级相关性提升+9%。SOLAR不仅为可扩展的高精度LLM推理树立了新标杆，还引入了自动化注释流程和动态推理拓扑竞争机制，推动了LLM推理能力的进一步突破。

> Large Language Models (LLMs) excel in reasoning but remain constrained by their Chain-of-Thought (CoT) approach, which struggles with complex tasks requiring more nuanced topological reasoning. We introduce SOLAR, Scalable Optimization of Large-scale Architecture for Reasoning, a framework that dynamically optimizes various reasoning topologies to enhance accuracy and efficiency.
  Our Topological Annotation Generation (TAG) system automates topological dataset creation and segmentation, improving post-training and evaluation. Additionally, we propose Topological-Scaling, a reward-driven framework that aligns training and inference scaling, equipping LLMs with adaptive, task-aware reasoning.
  SOLAR achieves substantial gains on MATH and GSM8K: +5% accuracy with Topological Tuning, +9% with Topological Reward, and +10.02% with Hybrid Scaling. It also reduces response length by over 5% for complex problems, lowering inference latency.
  To foster the reward system, we train a multi-task Topological Reward Model (M-TRM), which autonomously selects the best reasoning topology and answer in a single pass, eliminating the need for training and inference on multiple single-task TRMs (S-TRMs), thus reducing both training cost and inference latency. In addition, in terms of performance, M-TRM surpasses all S-TRMs, improving accuracy by +10% and rank correlation by +9%.
  To the best of our knowledge, SOLAR sets a new benchmark for scalable, high-precision LLM reasoning while introducing an automated annotation process and a dynamic reasoning topology competition mechanism.

[Arxiv](https://arxiv.org/abs/2503.04530)