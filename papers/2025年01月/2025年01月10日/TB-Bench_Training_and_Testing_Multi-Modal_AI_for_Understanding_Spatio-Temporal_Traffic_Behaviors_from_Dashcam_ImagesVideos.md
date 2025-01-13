# TB-Bench: 多模态AI的训练与测试——从行车记录仪图像/视频中理解时空交通行为

发布时间：2025年01月10日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在自动驾驶（AD）中的应用，包括基准测试、数据集发布和基线模型的改进。这些内容属于将大型语言模型应用于具体领域（自动驾驶）的研究，因此归类为LLM应用。` `自动驾驶`

> TB-Bench: Training and Testing Multi-Modal AI for Understanding Spatio-Temporal Traffic Behaviors from Dashcam Images/Videos

# 摘要

> 多模态大型语言模型（MLLMs）在自动驾驶（AD）中的应用面临两大挑战：交通数据训练不足和缺乏时空理解基准。为此，我们提出了TB-Bench，一个全面评估MLLMs在八种自我中心视角交通行为感知任务中的基准。同时，我们发布了视觉-语言指令调优数据集TB-100k和TB-250k，并提供了简单高效的基线模型。实验表明，现有MLLMs在这些任务中表现欠佳，即便是GPT-4o这样的强模型，平均准确率也不到35%。然而，经过TB-100k或TB-250k微调后，基线模型的平均准确率提升至85%，性能显著增强。此外，通过TB-100k与另一交通数据集联合训练，我们实现了性能迁移，进一步提升了后者的表现。总的来说，本研究通过引入基准、数据集和基线模型，推动了MLLMs在AD感知、预测和规划阶段的逐步集成。

> The application of Multi-modal Large Language Models (MLLMs) in Autonomous Driving (AD) faces significant challenges due to their limited training on traffic-specific data and the absence of dedicated benchmarks for spatiotemporal understanding. This study addresses these issues by proposing TB-Bench, a comprehensive benchmark designed to evaluate MLLMs on understanding traffic behaviors across eight perception tasks from ego-centric views. We also introduce vision-language instruction tuning datasets, TB-100k and TB-250k, along with simple yet effective baselines for the tasks. Through extensive experiments, we show that existing MLLMs underperform in these tasks, with even a powerful model like GPT-4o achieving less than 35% accuracy on average. In contrast, when fine-tuned with TB-100k or TB-250k, our baseline models achieve average accuracy up to 85%, significantly enhancing performance on the tasks. Additionally, we demonstrate performance transfer by co-training TB-100k with another traffic dataset, leading to improved performance on the latter. Overall, this study represents a step forward by introducing a comprehensive benchmark, high-quality datasets, and baselines, thus supporting the gradual integration of MLLMs into the perception, prediction, and planning stages of AD.

[Arxiv](https://arxiv.org/abs/2501.05733)