# DRAMA-X：驾驶场景下的精细意图预测与风险推理基准

发布时间：2025年06月21日

`LLM应用` `自动驾驶` `智能交通系统`

> DRAMA-X: A Fine-grained Intent Prediction and Risk Reasoning Benchmark For Driving

# 摘要

> 理解行人和骑行者等弱势道路使用者（VRUs）的短期运动对于安全的自动驾驶至关重要，尤其是在城市环境中存在模糊或高风险行为的情况下。尽管视觉-语言模型（VLMs）实现了开放词汇表的感知能力，但它们在细粒度意图推理方面的实用性尚未得到充分探索。值得注意的是，目前还没有现有的基准针对安全关键情况下的多类意图预测进行评估。为了解决这一空白，我们引入了DRAMA-X，这是一个通过自动化标注管道从DRAMA数据集中构建的细粒度基准。DRAMA-X包含5,686个易发生事故的帧，标注了目标边界框、九类方向意图分类、二进制风险评分、专家生成的 ego 车辆动作建议以及描述性运动摘要。这些标注使我们能够对与自主决策相关的四个相互关联的任务进行结构化评估：目标检测、意图预测、风险评估和动作建议。作为参考基线，我们提出了SGG-Intent，这是一个轻量级、无需训练的框架，模仿了 ego 车辆的推理管道。它依次从视觉输入生成场景图，使用基于VLM的检测器，推理意图，评估风险，并利用大型语言模型驱动的组合推理阶段推荐动作。我们评估了多种近期的VLMs，并在DRAMA-X的四个任务上比较了它们的性能。我们的实验表明，基于场景图的推理增强了意图预测和风险评估，尤其是在显式建模上下文线索时表现尤为显著。


> Understanding the short-term motion of vulnerable road users (VRUs) like pedestrians and cyclists is critical for safe autonomous driving, especially in urban scenarios with ambiguous or high-risk behaviors. While vision-language models (VLMs) have enabled open-vocabulary perception, their utility for fine-grained intent reasoning remains underexplored. Notably, no existing benchmark evaluates multi-class intent prediction in safety-critical situations, To address this gap, we introduce DRAMA-X, a fine-grained benchmark constructed from the DRAMA dataset via an automated annotation pipeline. DRAMA-X contains 5,686 accident-prone frames labeled with object bounding boxes, a nine-class directional intent taxonomy, binary risk scores, expert-generated action suggestions for the ego vehicle, and descriptive motion summaries. These annotations enable a structured evaluation of four interrelated tasks central to autonomous decision-making: object detection, intent prediction, risk assessment, and action suggestion. As a reference baseline, we propose SGG-Intent, a lightweight, training-free framework that mirrors the ego vehicle's reasoning pipeline. It sequentially generates a scene graph from visual input using VLM-backed detectors, infers intent, assesses risk, and recommends an action using a compositional reasoning stage powered by a large language model. We evaluate a range of recent VLMs, comparing performance across all four DRAMA-X tasks. Our experiments demonstrate that scene-graph-based reasoning enhances intent prediction and risk assessment, especially when contextual cues are explicitly modeled.

[Arxiv](https://arxiv.org/abs/2506.17590)