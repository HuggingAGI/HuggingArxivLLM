# TTrace：专为分布式训练设计的轻量级错误检测与诊断工具

发布时间：2025年06月10日

`LLM应用

理由：这篇论文讨论了分布式训练中大型语言模型的静默错误检测和定位问题，并提出了一种名为TTrace的系统来解决这一问题。虽然它涉及大型语言模型的训练，但更侧重于优化和工具层面，因此归类为LLM应用。` `高性能计算` `系统软件`

> TTrace: Lightweight Error Checking and Diagnosis for Distributed Training

# 摘要

> 分布式训练是扩展大型神经网络模型（如大型语言模型LLMs）训练规模的关键，尤其是在数千块GPU上进行。然而，分布式训练程序的复杂性使得它们特别容易出现静默错误，这些错误不会产生明确的错误信号，但却会导致训练结果不正确。在分布式训练中有效检测和定位这些静默错误颇具挑战性。使用训练损失或梯度范数曲线等常见指标进行调试可能效率低下且效果不佳。此外，在静默错误定位过程中获取中间张量值并判断其是否正确也颇具难度，尤其是在低精度训练的背景下。

为了解决这些挑战，我们设计并实现了TTrace，这是首个能够检测和定位分布式训练中静默错误的系统。TTrace以细粒度的方式从分布式训练中收集中间张量，并将它们与来自可信单设备参考实现的张量进行对比。为了正确比较张量中的浮点值，我们提出了新颖的数学分析方法，该方法提供了设置阈值的指导，使TTrace能够区分由静默错误引起的误差和浮点数舍入误差。实验结果表明，TTrace成功检测到广泛使用的Megatron-LM框架中已有的11个静默错误和3个新发现的静默错误，且仅需修改不到10行代码。TTrace在多种训练配置中均表现出有效性，包括涉及BF16和FP8的低精度训练配置。

> Distributed training is essential for scaling the training of large neural network models, such as large language models (LLMs), across thousands of GPUs. However, the complexity of distributed training programs makes them particularly prone to silent bugs, which do not produce explicit error signal but lead to incorrect training outcome. Effectively detecting and localizing such silent bugs in distributed training is challenging. Common debugging practice using metrics like training loss or gradient norm curves can be inefficient and ineffective. Additionally, obtaining intermediate tensor values and determining whether they are correct during silent bug localization is difficult, particularly in the context of low-precision training.
  To address those challenges, we design and implement TTrace, the first system capable of detecting and localizing silent bugs in distributed training. TTrace collects intermediate tensors from distributing training in a fine-grained manner and compares them against those from a trusted single-device reference implementation. To properly compare the floating-point values in the tensors, we propose novel mathematical analysis that provides a guideline for setting thresholds, enabling TTrace to distinguish bug-induced errors from floating-point round-off errors. Experimental results demonstrate that TTrace effectively detects 11 existing bugs and 3 new bugs in the widely used Megatron-LM framework, while requiring fewer than 10 lines of code change. TTrace is effective in various training recipes, including low-precision recipes involving BF16 and FP8.

[Arxiv](https://arxiv.org/abs/2506.09280)