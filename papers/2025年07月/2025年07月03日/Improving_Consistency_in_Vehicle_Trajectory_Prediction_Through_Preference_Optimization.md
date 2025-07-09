# 通过偏好优化提升车辆轨迹预测的一致性

发布时间：2025年07月03日

`LLM应用` `自动驾驶`

> Improving Consistency in Vehicle Trajectory Prediction Through Preference Optimization

# 摘要

> 轨迹预测是自动驾驶系统中的关键环节。对周围目标运动的不准确或不一致预测，不仅会导致路径规划失误，还可能危及驾驶安全。当前基于深度学习的轨迹预测模型在公开数据集上表现优异，但在复杂交互场景下，往往难以捕捉目标间的相互依赖关系，导致交通场景预测结果不一致。受大型语言模型中融入人类偏好的启发，本研究通过偏好优化方法，在多目标场景下对轨迹预测模型进行微调。通过在微调过程中引入自动计算的未来预测偏好排名，我们在三个独立数据集上的实验表明：与现有模型相比，新方法不仅显著提升了场景一致性，还保持了较高的轨迹预测精度，且在推理阶段无需增加额外计算开销。

> Trajectory prediction is an essential step in the pipeline of an autonomous vehicle. Inaccurate or inconsistent predictions regarding the movement of agents in its surroundings lead to poorly planned maneuvers and potentially dangerous situations for the end-user. Current state-of-the-art deep-learning-based trajectory prediction models can achieve excellent accuracy on public datasets. However, when used in more complex, interactive scenarios, they often fail to capture important interdependencies between agents, leading to inconsistent predictions among agents in the traffic scene. Inspired by the efficacy of incorporating human preference into large language models, this work fine-tunes trajectory prediction models in multi-agent settings using preference optimization. By taking as input automatically calculated preference rankings among predicted futures in the fine-tuning process, our experiments--using state-of-the-art models on three separate datasets--show that we are able to significantly improve scene consistency while minimally sacrificing trajectory prediction accuracy and without adding any excess computational requirements at inference time.

[Arxiv](https://arxiv.org/abs/2507.02406)