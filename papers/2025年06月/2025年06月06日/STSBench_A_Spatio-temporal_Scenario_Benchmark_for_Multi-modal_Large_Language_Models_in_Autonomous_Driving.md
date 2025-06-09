# STSBench：自动驾驶领域多模态大型语言模型的时空场景基准测试。

发布时间：2025年06月06日

`LLM应用` `自动驾驶` `视觉语言模型`

> STSBench: A Spatio-temporal Scenario Benchmark for Multi-modal Large Language Models in Autonomous Driving

# 摘要

> 我们推出STSBench——一个基于场景的框架，用于评估视觉语言模型（VLMs）在自动驾驶中的全面理解能力。该框架通过真实标注从任意数据集中自动提取预定义的交通场景，提供直观的用户界面以高效完成人工验证，并生成多选题用于模型评估。在NuScenes数据集上的应用，我们推出了STSnu，这是首个基于全面3D感知评估VLMs时空推理能力的基准。

现有基准通常针对现成或微调的VLMs，处理单一视角的图像或视频，侧重于物体识别、密集描述、风险评估或场景理解等语义任务。而STSnu专注于评估用于端到端驾驶的驾驶专家VLMs，处理多视角摄像头或LiDAR的视频。它特别评估VLMs在推理自身车辆动作及交通参与者间复杂交互的能力，这对自动驾驶汽车至关重要。

该基准涵盖43种多视角多帧的多样化场景，生成了971道经人工验证的多选题。全面评估揭示了现有模型在复杂环境下推理基本交通动态能力上的重大缺陷。这些发现凸显了急需在架构上取得进展，以明确建模时空推理。通过填补时空评估的核心空白，STSBench推动了更强大、更可解释的VLMs在自动驾驶领域的开发。

> We introduce STSBench, a scenario-based framework to benchmark the holistic understanding of vision-language models (VLMs) for autonomous driving. The framework automatically mines pre-defined traffic scenarios from any dataset using ground-truth annotations, provides an intuitive user interface for efficient human verification, and generates multiple-choice questions for model evaluation. Applied to the NuScenes dataset, we present STSnu, the first benchmark that evaluates the spatio-temporal reasoning capabilities of VLMs based on comprehensive 3D perception. Existing benchmarks typically target off-the-shelf or fine-tuned VLMs for images or videos from a single viewpoint and focus on semantic tasks such as object recognition, dense captioning, risk assessment, or scene understanding. In contrast, STSnu evaluates driving expert VLMs for end-to-end driving, operating on videos from multi-view cameras or LiDAR. It specifically assesses their ability to reason about both ego-vehicle actions and complex interactions among traffic participants, a crucial capability for autonomous vehicles. The benchmark features 43 diverse scenarios spanning multiple views and frames, resulting in 971 human-verified multiple-choice questions. A thorough evaluation uncovers critical shortcomings in existing models' ability to reason about fundamental traffic dynamics in complex environments. These findings highlight the urgent need for architectural advances that explicitly model spatio-temporal reasoning. By addressing a core gap in spatio-temporal evaluation, STSBench enables the development of more robust and explainable VLMs for autonomous driving.

[Arxiv](https://arxiv.org/abs/2506.06218)