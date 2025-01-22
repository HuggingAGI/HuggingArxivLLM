# BAP v2: 一个用于 Minecraft 对话指令跟随的增强型任务框架

发布时间：2025年01月18日

`Agent

理由：这篇论文主要讨论了在《我的世界》协作建造任务（MCBT）中，建造者动作预测（BAP）子任务的改进和评估。论文的核心是开发一个能够理解和执行物理世界指令的交互式智能体（Agent），并通过改进数据和评估方法来提升其性能。虽然论文中提到了LLM（大型语言模型）的应用，但主要关注的是智能体在特定任务中的表现和优化，因此更适合归类为Agent。` `人工智能`

> BAP v2: An Enhanced Task Framework for Instruction Following in Minecraft Dialogues

# 摘要

> # 摘要
能够理解和执行物理世界指令的交互式智能体，一直是AI研究的核心目标。《我的世界》协作建造任务（MCBT）为实现这一目标提供了一个实验场景（Narayan-Chen等，2019）。在这个双人游戏中，建筑师（A）指导建造者（B）在模拟的积木世界中构建目标结构。我们聚焦于建造者动作预测（BAP）子任务，即在有限训练数据下预测多模态游戏中的正确动作序列（Jayannavar等，2020）。我们深入研究了BAP任务的评估和数据，发现了关键挑战，并提出了BAP v2，这是该任务的升级版本。它包括：（1）一个增强的评估基准，包含更干净的测试集和更公平、更有洞察力的指标；（2）通过模拟MCBT的新型《我的世界》对话和目标结构生成器生成的额外合成训练数据。我们展示了即使使用简单的训练方法，合成数据也能训练出性能更好、更稳健的神经模型。展望未来，这些数据对于训练更复杂、数据需求更大的深度Transformer模型以及微调大型LLM至关重要。尽管建模不是重点，但我们展示了数据和训练方法对基于简单LLM和Transformer模型的影响，验证了方法的稳健性，并为未来更先进的架构和LLM奠定了基础。

> Interactive agents capable of understanding and executing instructions in the physical world have long been a central goal in AI research. The Minecraft Collaborative Building Task (MCBT) provides one such setting to work towards this goal (Narayan-Chen, Jayannavar, and Hockenmaier 2019). It is a two-player game in which an Architect (A) instructs a Builder (B) to construct a target structure in a simulated Blocks World Environment. We focus on the challenging Builder Action Prediction (BAP) subtask of predicting correct action sequences in a given multimodal game context with limited training data (Jayannavar, Narayan-Chen, and Hockenmaier 2020). We take a closer look at evaluation and data for the BAP task, discovering key challenges and making significant improvements on both fronts to propose BAP v2, an upgraded version of the task. This will allow future work to make more efficient and meaningful progress on it. It comprises of: (1) an enhanced evaluation benchmark that includes a cleaner test set and fairer, more insightful metrics, and (2) additional synthetic training data generated from novel Minecraft dialogue and target structure simulators emulating the MCBT. We show that the synthetic data can be used to train more performant and robust neural models even with relatively simple training methods. Looking ahead, such data could also be crucial for training more sophisticated, data-hungry deep transformer models and training/fine-tuning increasingly large LLMs. Although modeling is not the primary focus of this work, we also illustrate the impact of our data and training methodologies on a simple LLM- and transformer-based model, thus validating the robustness of our approach, and setting the stage for more advanced architectures and LLMs going forward.

[Arxiv](https://arxiv.org/abs/2501.10836)