# 关于方法级代码异味检测中参数高效微调的全面评估

发布时间：2024年12月18日

`LLM应用` `代码检测`

> A Comprehensive Evaluation of Parameter-Efficient Fine-Tuning on Method-Level Code Smell Detection

# 摘要

> 代码异味指的是那些对软件系统质量有负面影响的次优编码实践。现有的检测手段，依靠启发式或者机器学习（ML）及深度学习（DL）技术，常常面临诸如性能不佳之类的局限。参数高效微调（PEFT）方法已成为使大型语言模型（LLM）适配特定任务的一种资源高效途径，但其用于方法级代码异味检测的有效性还未被充分探究。就此而言，本研究在小型和大型语言模型（LM）上对最先进的PEFT方法进行了评估，以检测两类方法级代码异味：复杂条件和复杂方法。利用来自GitHub的高质量数据集，我们用PEFT技术对四个小型LM和六个LLM进行了微调，涵盖提示调整、前缀调整、LoRA和（IA）3。结果显示，PEFT方法在消耗更少GPU内存的情况下，达成了与全微调相当甚至更优的性能。值得注意的是，LLM并不比小型LM表现出色，这表明较小的模型更适合这项任务。另外，增大训练数据集的规模显著提升了性能，而增加可训练参数却没有。我们的发现凸显了PEFT方法是有效且可扩展的解决方案，胜过现有的基于启发式和基于DL的检测器。

> Code smells are suboptimal coding practices that negatively impact the quality of software systems. Existing detection methods, relying on heuristics or Machine Learning (ML) and Deep Learning (DL) techniques, often face limitations such as unsatisfactory performance. Parameter-Efficient Fine-Tuning (PEFT) methods have emerged as a resource-efficient approach for adapting LLMs to specific tasks, but their effectiveness for method-level code smell detection remains underexplored. In this regard, this study evaluates state-of-the-art PEFT methods on both small and large Language Models (LMs) for detecting two types of method-level code smells: Complex Conditional and Complex Method. Using high-quality datasets sourced from GitHub, we fine-tuned four small LMs and six LLMs with PEFT techniques, including prompt tuning, prefix tuning, LoRA, and (IA)3. Results show that PEFT methods achieve comparable or better performance than full fine-tuning while consuming less GPU memory. Notably, LLMs did not outperform small LMs, suggesting smaller models' suitability for this task. Additionally, increasing training dataset size significantly boosted performance, while increasing trainable parameters did not. Our findings highlight PEFT methods as effective and scalable solutions, outperforming existing heuristic-based and DL-based detectors.

[Arxiv](https://arxiv.org/abs/2412.13801)