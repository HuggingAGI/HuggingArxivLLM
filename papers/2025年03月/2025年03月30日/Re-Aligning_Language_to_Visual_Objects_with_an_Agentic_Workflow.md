# # 智能体工作流：重新定义语言与视觉对象的对齐方式

发布时间：2025年03月30日

`LLM应用` `计算机视觉`

> Re-Aligning Language to Visual Objects with an Agentic Workflow

# 摘要

> 基于语言的对象检测（LOD）旨在将视觉对象与语言表达对齐。为提升LOD模型的泛化能力，我们利用大量成对数据进行训练。近期研究通过视觉语言模型（VLMs）自动生成类似人类的表达，从而扩展训练数据。然而，我们发现VLM幻觉会导致不准确的对象描述（如名称、颜色和形状），进而降低视觉语言对齐质量。为解决这一问题，我们提出了一种由大型语言模型（LLM）控制的智能工作流Real-LOD，通过自适应调整图像和文本提示重新对齐语言与视觉对象。Real-LOD包括规划、工具使用和反思三个步骤。给定一张包含检测对象和VLM原始语言表达的图像，Real-LOD会自动推理其状态，并根据神经符号设计安排行动（即规划）。行动将自适应调整图像和文本提示，并将其发送到VLMs进行对象重新描述（即工具使用）。然后，我们使用另一个LLM分析这些优化后的表达以提供反馈（即反思）。这些步骤以循环形式进行，逐步改进语言描述以重新对齐视觉对象。我们构建了一个包含0.18M图像和重新对齐语言表达的数据集，并训练了一个流行的LOD模型，在标准基准上超越现有LOD方法约50%。我们的Real-LOD工作流通过自动视觉语言优化，在扩展数据量的同时保持数据质量，从而进一步从数据对齐的角度提升了LOD性能。

> Language-based object detection (LOD) aims to align visual objects with language expressions. A large amount of paired data is utilized to improve LOD model generalizations. During the training process, recent studies leverage vision-language models (VLMs) to automatically generate human-like expressions for visual objects, facilitating training data scaling up. In this process, we observe that VLM hallucinations bring inaccurate object descriptions (e.g., object name, color, and shape) to deteriorate VL alignment quality. To reduce VLM hallucinations, we propose an agentic workflow controlled by an LLM to re-align language to visual objects via adaptively adjusting image and text prompts. We name this workflow Real-LOD, which includes planning, tool use, and reflection steps. Given an image with detected objects and VLM raw language expressions, Real-LOD reasons its state automatically and arranges action based on our neural symbolic designs (i.e., planning). The action will adaptively adjust the image and text prompts and send them to VLMs for object re-description (i.e., tool use). Then, we use another LLM to analyze these refined expressions for feedback (i.e., reflection). These steps are conducted in a cyclic form to gradually improve language descriptions for re-aligning to visual objects. We construct a dataset that contains a tiny amount of 0.18M images with re-aligned language expression and train a prevalent LOD model to surpass existing LOD methods by around 50% on the standard benchmarks. Our Real-LOD workflow, with automatic VL refinement, reveals a potential to preserve data quality along with scaling up data quantity, which further improves LOD performance from a data-alignment perspective.

[Arxiv](https://arxiv.org/abs/2503.23508)