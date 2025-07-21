# CoTasks：链式思维驱动的视频指令微调任务

发布时间：2025年07月17日

`LLM应用` `计算机视觉`

> CoTasks: Chain-of-Thought based Video Instruction Tuning Tasks

# 摘要

> 尽管视频大语言模型（VideoLLMs）领域取得了 recent progress，但一个关键挑战仍然存在：如何赋予模型基于细粒度对象级别视频理解的链式思维（CoT）推理能力。现有如Qwen和LLaVA系列的指令微调模型，基于高层次的视频-文本对进行训练，往往缺乏支持组合式、逐步推理所需的结构化标注。为此，我们提出CoTasks：基于链式思维的视频指令微调任务，这是一个全新的框架。它将NeXT-QA、STAR等现有数据集中的复杂视频问题，分解为四个实体级别的基础任务：帧定位、实体跟踪、空间关系提取和时间关系提取。通过将这些中间的CoT式推理步骤嵌入输入中，CoTasks使模型能够显式地进行以对象为中心的空间时间推理。在NeXT-QA基准上的实验结果表明，CoTasks显著提升了推理性能：LLaVA-video-7B的平均GPT-4评估分数提高了+3.3分，Qwen2.5-VL-3B提升了+17.4分。其中，因果推理提升了+14.6分，时间推理提升了+10.9分，描述性推理更是提升了+48.1分。这些结果充分证明了CoTasks作为结构化的CoT式监督框架，在提升组合式视频推理能力方面的显著效果。


> Despite recent progress in video large language models (VideoLLMs), a key open challenge remains: how to equip models with chain-of-thought (CoT) reasoning abilities grounded in fine-grained object-level video understanding. Existing instruction-tuned models, such as the Qwen and LLaVA series, are trained on high-level video-text pairs, often lacking structured annotations necessary for compositional, step-by-step reasoning. We propose CoTasks: Chain-of-Thought based Video Instruction Tuning Tasks, a new framework that decomposes complex video questions of existing datasets (e.g., NeXT-QA, STAR) into four entity-level foundational tasks: frame localization, entity tracking, spatial and temporal relation extraction. By embedding these intermediate CoT-style reasoning steps into the input, CoTasks enables models to explicitly perform object-centric spatiotemporal reasoning. Experiments on the NeXT-QA benchmark show that CoTasks significantly enhance inference performance: LLaVA-video-7B improves by +3.3 points in average GPT-4 evaluation score, and Qwen2.5-VL-3B gains +17.4, with large boosts in causal (+14.6), temporal (+10.9), and descriptive (+48.1) subcategories. These results demonstrate the effectiveness of CoTasks as a structured CoT-style supervision framework for improving compositional video reasoning.

[Arxiv](https://arxiv.org/abs/2507.13609)