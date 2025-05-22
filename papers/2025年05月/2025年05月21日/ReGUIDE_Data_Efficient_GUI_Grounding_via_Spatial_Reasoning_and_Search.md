# ReGUIDE：基于空间推理与搜索的高效 GUI 锚定方法

发布时间：2025年05月21日

`LLM应用` `人工智能` `计算机图形学`

> ReGUIDE: Data Efficient GUI Grounding via Spatial Reasoning and Search

# 摘要

> 近期，多模态大型语言模型（MLLMs）的突破性进展让自主智能体能够通过图形用户界面（GUI）与计算机进行交互。在这一过程中，准确定位界面元素（如按钮）的坐标通常是实现精细操作的关键。然而，这一任务仍然具有很大挑战性，导致先前的研究依赖大规模网络数据集来提升定位精度。在此项研究中，我们提出了一种名为基于推理的高效数据GUI定位框架（ReGUIDE），这是一种新颖且有效的网络定位框架，使MLLMs能够通过自动生成的推理和空间感知的批评机制高效学习数据。具体而言，ReGUIDE通过在线强化学习自动生成用于定位的语言推理过程，并利用空间先验知识对预测结果进行批评，确保在输入变换下的等变性。推理时，ReGUIDE进一步通过结合空间搜索与坐标聚合的测试时间缩放策略提升性能。实验结果表明，ReGUIDE显著提升了多基准测试中的网络定位性能，相较于最优开源基线，仅需极少量的训练数据（例如，仅需0.2%的样本量）。

> Recent advances in Multimodal Large Language Models (MLLMs) have enabled autonomous agents to interact with computers via Graphical User Interfaces (GUIs), where accurately localizing the coordinates of interface elements (e.g., buttons) is often required for fine-grained actions. However, this remains significantly challenging, leading prior works to rely on large-scale web datasets to improve the grounding accuracy. In this work, we propose Reasoning Graphical User Interface Grounding for Data Efficiency (ReGUIDE), a novel and effective framework for web grounding that enables MLLMs to learn data efficiently through self-generated reasoning and spatial-aware criticism. More specifically, ReGUIDE learns to (i) self-generate a language reasoning process for the localization via online reinforcement learning, and (ii) criticize the prediction using spatial priors that enforce equivariance under input transformations. At inference time, ReGUIDE further boosts performance through a test-time scaling strategy, which combines spatial search with coordinate aggregation. Our experiments demonstrate that ReGUIDE significantly advances web grounding performance across multiple benchmarks, outperforming baselines with substantially fewer training data points (e.g., only 0.2% samples compared to the best open-sourced baselines).

[Arxiv](https://arxiv.org/abs/2505.15259)