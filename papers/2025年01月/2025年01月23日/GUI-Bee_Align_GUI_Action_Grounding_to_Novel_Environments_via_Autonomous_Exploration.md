# GUI-Bee：通过自主探索实现 GUI 动作定位与新颖环境的无缝对接

发布时间：2025年01月23日

`Agent

理由：这篇论文介绍了一个名为GUI-Bee的自主代理，它通过探索收集高质量、环境特定的数据，并持续微调模型。GUI-Bee采用了创新的Q值激励上下文强化学习方法，优化探索效率和数据质量。这些特征表明该研究主要关注于开发一个能够自主执行任务并不断学习和改进的代理系统，因此将其分类为Agent。` `人机交互` `自动化`

> GUI-Bee: Align GUI Action Grounding to Novel Environments via Autonomous Exploration

# 摘要

> # 图形用户界面（GUI）动作定位
GUI动作定位是GUI自动化的核心步骤，它将语言指令映射到屏幕上的可操作元素。近期研究多依赖大型GUI数据集微调多模态大语言模型（MLLMs），但微调数据往往局限于有限环境，导致模型在新环境中表现不佳。我们认为，当推理涉及新环境时，GUI定位模型应进一步与新环境对齐，以释放其全部潜力。为此，我们提出了GUI-Bee，一个基于MLLM的自主代理，通过探索收集高质量、环境特定的数据，并持续微调模型。GUI-Bee采用了一种创新的Q值激励上下文强化学习（Q-ICRL）方法，优化探索效率和数据质量。我们还推出了NovelScreenSpot基准，用于测试数据在模型对齐新环境中的效果，实验证明了GUI-Bee收集数据的有效性。此外，消融研究验证了Q-ICRL方法在提升GUI-Bee效率方面的作用。项目页面：https://gui-bee.github.io

> Graphical User Interface (GUI) action grounding is a critical step in GUI automation that maps language instructions to actionable elements on GUI screens. Most recent works of GUI action grounding leverage large GUI datasets to fine-tune MLLMs. However, the fine-tuning data always covers limited GUI environments, and we find the performance of the resulting model deteriorates in novel environments. We argue that the GUI grounding models should be further aligned to the novel environments to reveal their full potential, when the inference is known to involve novel environments, i.e., environments not used during the previous fine-tuning. To realize this, we first propose GUI-Bee, an MLLM-based autonomous agent, to collect high-quality, environment-specific data through exploration and then continuously fine-tune GUI grounding models with the collected data. Our agent leverages a novel Q-value-Incentive In-Context Reinforcement Learning (Q-ICRL) method to optimize exploration efficiency and data quality. Additionally, we introduce NovelScreenSpot, a benchmark for testing how well the data can help align GUI action grounding models to novel environments and demonstrate the effectiveness of data collected by GUI-Bee in the experiments. Furthermore, we conduct an ablation study to validate the Q-ICRL method in enhancing the efficiency of GUI-Bee. Project page: https://gui-bee.github.io

[Arxiv](https://arxiv.org/abs/2501.13896)