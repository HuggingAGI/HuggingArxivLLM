# 《Mind the Gap》：探究大型语言模型的自我提升能力

发布时间：2024年12月03日

`LLM理论` `语言模型` `人工智能`

> Mind the Gap: Examining the Self-Improvement Capabilities of Large Language Models

# 摘要

> 自我改进是大型语言模型（LLM）在预训练、后训练以及测试时推理中的一种机制。我们探索了这样一个框架：模型对自身输出进行验证，基于此验证来过滤或重新加权数据，并提炼过滤后的数据。尽管取得了一些经验上的成功，但仍缺乏根本的理解。在本研究中，我们针对 LLM 自我改进展开了全面、模块化且受控的研究。我们为自我改进提供了数学公式，其在很大程度上受我们定义为生成 - 验证差距的量所支配。通过对各类模型家族和任务进行实验，我们发现了自我改进的缩放现象——生成 - 验证差距的一个变体随模型预训练的浮点运算次数单调缩放。我们还探讨了自我改进的可能性、迭代的自我改进程序以及提升其性能的方法。我们的发现不仅增进了对 LLM 自我改进的理解，具有实际意义，还为未来研究其能力和边界开辟了众多方向。

> Self-improvement is a mechanism in Large Language Model (LLM) pre-training, post-training and test-time inference. We explore a framework where the model verifies its own outputs, filters or reweights data based on this verification, and distills the filtered data. Despite several empirical successes, a fundamental understanding is still lacking. In this work, we initiate a comprehensive, modular and controlled study on LLM self-improvement. We provide a mathematical formulation for self-improvement, which is largely governed by a quantity which we formalize as the generation-verification gap. Through experiments with various model families and tasks, we discover a scaling phenomenon of self-improvement -- a variant of the generation-verification gap scales monotonically with the model pre-training flops. We also examine when self-improvement is possible, an iterative self-improvement procedure, and ways to improve its performance. Our findings not only advance understanding of LLM self-improvement with practical implications, but also open numerous avenues for future research into its capabilities and boundaries.

[Arxiv](https://arxiv.org/abs/2412.02674)