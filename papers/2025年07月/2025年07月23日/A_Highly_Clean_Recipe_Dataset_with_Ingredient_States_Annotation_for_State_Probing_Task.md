# 高质量食谱数据集，附带食材状态标注，适用于状态探测任务

发布时间：2025年07月23日

`LLM应用

LLM应用

论文摘要：大型语言模型（LLMs）经过大量程序性文本的训练，但无法直接观察真实世界的现象。以烹饪食谱为例，由于食材的中间状态经常被省略，模型难以跟踪食材状态并准确理解食谱。本文中，我们将“状态探测”（一种评估语言模型对世界理解的方法）应用于烹饪领域，提出了一项新的任务和数据集，用于评估LLMs在烹饪过程中识别食材中间状态的能力。我们构建了一个新的日语食谱数据集，其中包含清晰准确的食材状态变化标注，数据集来源于结构良好且经过控制的食谱文本。利用这个数据集，我们设计了三项新颖的任务，以评估LLMs是否能够跟踪食材状态的转变，并识别烹饪过程中各步骤的食材。实验结果表明，学习食材状态知识能够提升模型对烹饪流程的理解，其性能可与商用LLMs相媲美。
LLM应用`

> A Highly Clean Recipe Dataset with Ingredient States Annotation for State Probing Task

# 摘要

> 大型语言模型（LLMs）经过大量程序性文本的训练，但无法直接观察真实世界的现象。以烹饪食谱为例，由于食材的中间状态经常被省略，模型难以跟踪食材状态并准确理解食谱。本文中，我们将“状态探测”（一种评估语言模型对世界理解的方法）应用于烹饪领域，提出了一项新的任务和数据集，用于评估LLMs在烹饪过程中识别食材中间状态的能力。我们构建了一个新的日语食谱数据集，其中包含清晰准确的食材状态变化标注，数据集来源于结构良好且经过控制的食谱文本。利用这个数据集，我们设计了三项新颖的任务，以评估LLMs是否能够跟踪食材状态的转变，并识别烹饪过程中各步骤的食材。实验结果表明，学习食材状态知识能够提升模型对烹饪流程的理解，其性能可与商用LLMs相媲美。

> Large Language Models (LLMs) are trained on a vast amount of procedural texts, but they do not directly observe real-world phenomena. In the context of cooking recipes, this poses a challenge, as intermediate states of ingredients are often omitted, making it difficult for models to track ingredient states and understand recipes accurately. In this paper, we apply state probing, a method for evaluating a language model's understanding of the world, to the domain of cooking. We propose a new task and dataset for evaluating how well LLMs can recognize intermediate ingredient states during cooking procedures. We first construct a new Japanese recipe dataset with clear and accurate annotations of ingredient state changes, collected from well-structured and controlled recipe texts. Using this dataset, we design three novel tasks to evaluate whether LLMs can track ingredient state transitions and identify ingredients present at intermediate steps. Our experiments with widely used LLMs, such as Llama3.1-70B and Qwen2.5-72B, show that learning ingredient state knowledge improves their understanding of cooking processes, achieving performance comparable to commercial LLMs.

[Arxiv](https://arxiv.org/abs/2507.17232)