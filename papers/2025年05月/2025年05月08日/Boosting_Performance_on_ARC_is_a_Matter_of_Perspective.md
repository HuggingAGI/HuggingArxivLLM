# 在ARC上提升性能，关键在于视角的选择。

发布时间：2025年05月08日

`LLM应用` `人工智能`

> Boosting Performance on ARC is a Matter of Perspective

# 摘要

> 抽象与推理语料库 (ARC-AGI) 为大型语言模型 (LLMs) 设置了一个难题，凸显了它们在抽象推理能力上的不足。在本研究中，我们创新性地在训练、生成和评分三个环节引入任务特定的数据增强技术，并结合深度优先搜索算法，生成多样化且高概率的候选解决方案。更进一步，我们突破性地将LLM不仅作为生成器，更作为智能评分器，通过其输出概率精准筛选最优解决方案。经过实践检验，我们的方法在公开的ARC-AGI评估集上取得了71.6%的优异成绩（286.5/400个任务解决），树立了公开方法中的新标杆。尽管同期的闭源工作报告了更高分数，但我们的方法凭借其透明的技术架构、可重复的实验流程，以及令人惊叹的超低推理成本（每项任务仅约2美分，基于Nvidia 4090 GPU时租价格36美分/小时的计算），在众多方案中独树一帜。

> The Abstraction and Reasoning Corpus (ARC-AGI) poses a significant challenge for large language models (LLMs), exposing limitations in their abstract reasoning abilities. In this work, we leverage task-specific data augmentations throughout the training, generation, and scoring phases, and employ a depth-first search algorithm to generate diverse, high-probability candidate solutions. Furthermore, we utilize the LLM not only as a generator but also as a scorer, using its output probabilities to select the most promising solutions. Our method achieves a score of 71.6% (286.5/400 solved tasks) on the public ARC-AGI evaluation set, demonstrating state-of-the-art performance among publicly available approaches. While concurrent closed-source work has reported higher scores, our method distinguishes itself through its transparency, reproducibility, and remarkably low inference cost, averaging only around 2ct per task on readily available hardware (we assume a price of 36ct/hour for a Nvidia 4090 GPU).

[Arxiv](https://arxiv.org/abs/2505.07859)