# 提及任何一人

发布时间：2025年03月11日

`LLM应用` `计算机视觉`

> Referring to Any Person

# 摘要

> 人类无疑是计算机视觉领域最重要的参与者，能够根据自然语言描述检测任何个体的能力，我们将其定义为对任何人的引用，具有重要的实用价值。然而，现有模型通常无法实现现实世界的实用性，而目前的基准测试由于专注于一对一的引用，限制了该领域的发展。在本研究中，我们从任务定义、数据集设计和模型架构三个关键视角重新审视这一任务。我们首先识别了可引用实体的五个方面和该任务的三个独特特征。接下来，我们引入了HumanRef，这是一个旨在解决这些挑战并更好地反映现实世界应用的新数据集。从模型设计的角度，我们整合了多模态大型语言模型与目标检测框架，构建了一个强大的引用模型，命名为RexSeek。实验结果表明，现有的最先进的模型在RefCOCO/+/g等常用基准测试中表现良好，但在HumanRef上却表现挣扎，原因在于它们无法检测多个个体。相比之下，RexSeek不仅在人类引用任务中表现出色，还能够有效地推广到常见的物体引用任务，使其在各类感知任务中具有广泛的应用前景。代码可从https://github.com/IDEA-Research/RexSeek获取

> Humans are undoubtedly the most important participants in computer vision, and the ability to detect any individual given a natural language description, a task we define as referring to any person, holds substantial practical value. However, we find that existing models generally fail to achieve real-world usability, and current benchmarks are limited by their focus on one-to-one referring, that hinder progress in this area. In this work, we revisit this task from three critical perspectives: task definition, dataset design, and model architecture. We first identify five aspects of referable entities and three distinctive characteristics of this task. Next, we introduce HumanRef, a novel dataset designed to tackle these challenges and better reflect real-world applications. From a model design perspective, we integrate a multimodal large language model with an object detection framework, constructing a robust referring model named RexSeek. Experimental results reveal that state-of-the-art models, which perform well on commonly used benchmarks like RefCOCO/+/g, struggle with HumanRef due to their inability to detect multiple individuals. In contrast, RexSeek not only excels in human referring but also generalizes effectively to common object referring, making it broadly applicable across various perception tasks. Code is available at https://github.com/IDEA-Research/RexSeek

[Arxiv](https://arxiv.org/abs/2503.08507)