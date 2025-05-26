# LiloDriver：面向长尾自动驾驶场景的闭环运动规划终身学习框架

发布时间：2025年05月22日

`LLM应用` `自动驾驶` `机器人`

> LiloDriver: A Lifelong Learning Framework for Closed-loop Motion Planning in Long-tail Autonomous Driving Scenarios

# 摘要

> 近期自动驾驶研究在鲁棒、安全且自适应的运动规划器方面取得进展。然而，现有规划器在长尾场景适应性不足，知识驱动方法虽推理能力强，但在表示、控制和现实评估上存在挑战。为此，我们提出LiloDriver，专为长尾自动驾驶设计的闭环运动规划终身学习框架。通过结合大语言模型（LLMs）与记忆增强规划器生成系统，LiloDriver无需重新训练即可适应新场景。其架构包括感知、场景编码、基于记忆的策略优化和LLM引导推理四个阶段。在nuPlan基准测试中，LiloDriver在常见和罕见驾驶场景中均表现优异，超越静态规则和学习规划器。研究结果表明，结合结构化记忆与LLM推理，可实现现实世界中可扩展、类人式的自动驾驶运动规划。代码可在https://github.com/Hyan-Yao/LiloDriver获取。

> Recent advances in autonomous driving research towards motion planners that are robust, safe, and adaptive. However, existing rule-based and data-driven planners lack adaptability to long-tail scenarios, while knowledge-driven methods offer strong reasoning but face challenges in representation, control, and real-world evaluation. To address these challenges, we present LiloDriver, a lifelong learning framework for closed-loop motion planning in long-tail autonomous driving scenarios. By integrating large language models (LLMs) with a memory-augmented planner generation system, LiloDriver continuously adapts to new scenarios without retraining. It features a four-stage architecture including perception, scene encoding, memory-based strategy refinement, and LLM-guided reasoning. Evaluated on the nuPlan benchmark, LiloDriver achieves superior performance in both common and rare driving scenarios, outperforming static rule-based and learning-based planners. Our results highlight the effectiveness of combining structured memory and LLM reasoning to enable scalable, human-like motion planning in real-world autonomous driving. Our code is available at https://github.com/Hyan-Yao/LiloDriver.

[Arxiv](https://arxiv.org/abs/2505.17209)