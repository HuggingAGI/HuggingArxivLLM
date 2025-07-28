# # 研究标题
视觉之眼：基于视觉的下一个GPS位置预测模型——通过强化学习从视觉地图反馈中学习

发布时间：2025年07月23日

`LLM应用

理由：这篇论文探讨了如何将视觉语言模型（VLMs）应用于位置预测任务，特别是在轨迹推理和下一个位置预测方面。论文提出了一种基于视觉引导的方法，并通过监督微调和强化学习来提升模型性能。这些方法属于将大型语言模型应用于具体任务的范畴，因此归类为LLM应用。` `城市治理`

> Eyes Will Shut: A Vision-Based Next GPS Location Prediction Model by Reinforcement Learning from Visual Map Feed Back

# 摘要

> 位置预测是人类移动性研究中的基础任务，在交通规划、城市治理和疫情预测等领域有着广泛应用。当人类预测轨迹中的下一个位置时，通常会将轨迹绘制在地图上，并根据道路连通性和移动趋势进行推理。然而，现有绝大多数的下一个位置预测模型并未像人类那样基于地图进行推理。幸运的是，近期发展的视觉语言模型（VLMs）在视觉感知甚至视觉推理方面展现出了强大的能力，这为我们打开了一扇新的大门：通过将道路网络和轨迹渲染到图像上，并借助VLMs的推理能力，可以让模型以类似人类的方式进行轨迹推理。

为了探索这一想法，我们首先提出了一种名为视觉引导的位置搜索（VGLS）的方法，评估了一般用途的VLM在不修改其任何内部参数的情况下是否能够进行基于轨迹的推理。基于VGLS结果的启发，我们进一步提出了主要方法：VLMLocPredictor，它由两个阶段组成。第一阶段，我们设计了两个监督微调（SFT）任务，帮助VLM理解道路网络和轨迹结构，并掌握对这类视觉输入的基本推理能力。第二阶段，我们引入了基于视觉地图反馈的强化学习，使模型能够通过与环境的交互来自我提升其下一个位置的预测能力。

在来自四个不同城市的实验数据集上，我们的方法实现了最先进（SOTA）的性能，并在与其他基于LLM的方法相比时表现出更优秀的跨城市泛化能力。

> Next Location Prediction is a fundamental task in the study of human mobility, with wide-ranging applications in transportation planning, urban governance, and epidemic forecasting. In practice, when humans attempt to predict the next location in a trajectory, they often visualize the trajectory on a map and reason based on road connectivity and movement trends. However, the vast majority of existing next-location prediction models do not reason over maps \textbf{in the way that humans do}. Fortunately, the recent development of Vision-Language Models (VLMs) has demonstrated strong capabilities in visual perception and even visual reasoning. This opens up a new possibility: by rendering both the road network and trajectory onto an image and leveraging the reasoning abilities of VLMs, we can enable models to perform trajectory inference in a human-like manner. To explore this idea, we first propose a method called Vision-Guided Location Search (VGLS), which evaluates whether a general-purpose VLM is capable of trajectory-based reasoning without modifying any of its internal parameters. Based on insights from the VGLS results, we further propose our main approach: VLMLocPredictor, which is composed of two stages: In the first stage, we design two Supervised Fine-Tuning (SFT) tasks that help the VLM understand road network and trajectory structures and acquire basic reasoning ability on such visual inputs. In the second stage, we introduce Reinforcement Learning from Visual Map Feedback, enabling the model to self-improve its next-location prediction ability through interaction with the environment. Experiments conducted on datasets from four different cities show that our method achieves state-of-the-art (SOTA) performance and exhibits superior cross-city generalization compared to other LLM-based approaches.

[Arxiv](https://arxiv.org/abs/2507.18661)