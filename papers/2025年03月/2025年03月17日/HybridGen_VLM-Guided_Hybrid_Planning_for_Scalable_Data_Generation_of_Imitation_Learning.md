# HybridGen：VLM引导的混合规划，为模仿学习提供可扩展的数据生成方案

发布时间：2025年03月17日

`Agent` `机器人` `自动化`

> HybridGen: VLM-Guided Hybrid Planning for Scalable Data Generation of Imitation Learning

# 摘要

> 大规模多样化演示数据的获取对于提升机器人模仿学习的泛化能力至关重要。然而，在现实场景中生成适用于复杂操作的此类数据极具挑战性。我们提出了一种名为HybridGen的自动化框架，该框架整合了视觉-语言模型（VLM）与混合规划技术。HybridGen采用两阶段流水线：首先，通过VLM解析专家演示，将任务分解为依赖专家的（基于物体中心的位姿变换以实现精准控制）和可规划的（通过路径规划生成多样化轨迹）两个部分；其次，位姿变换显著扩展了第一阶段的数据量。至关重要的是，HybridGen无需特定数据格式即可生成大量训练数据，使其能够广泛应用于多种模仿学习算法。我们通过多个算法的实证研究验证了这一特性。在七项任务及其变体的评估中，采用HybridGen训练的代理实现了显著的性能和泛化能力提升，平均比现有最优方法高出5%。值得注意的是，在最具挑战性的任务变体中，HybridGen表现尤为突出，平均成功率高达59.7%，远超Mimicgen的49.5%。这些结果充分证明了其有效性与实用性。

> The acquisition of large-scale and diverse demonstration data are essential for improving robotic imitation learning generalization. However, generating such data for complex manipulations is challenging in real-world settings. We introduce HybridGen, an automated framework that integrates Vision-Language Model (VLM) and hybrid planning. HybridGen uses a two-stage pipeline: first, VLM to parse expert demonstrations, decomposing tasks into expert-dependent (object-centric pose transformations for precise control) and plannable segments (synthesizing diverse trajectories via path planning); second, pose transformations substantially expand the first-stage data. Crucially, HybridGen generates a large volume of training data without requiring specific data formats, making it broadly applicable to a wide range of imitation learning algorithms, a characteristic which we also demonstrate empirically across multiple algorithms. Evaluations across seven tasks and their variants demonstrate that agents trained with HybridGen achieve substantial performance and generalization gains, averaging a 5% improvement over state-of-the-art methods. Notably, in the most challenging task variants, HybridGen achieves significant improvement, reaching a 59.7% average success rate, significantly outperforming Mimicgen's 49.5%. These results demonstrating its effectiveness and practicality.

[Arxiv](https://arxiv.org/abs/2503.13171)