# o1类大语言模型的过度思考：为什么2+3=？也需要三思而后行？

发布时间：2025年02月01日

`LLM应用` `人工智能`

> Do NOT Think That Much for 2+3=? On the Overthinking of o1-Like LLMs

# 摘要

> OpenAI o1 等模型的出色表现源于其推理过程中模拟人类长时间思考的能力。这些模型通过延长链式思考（CoT）过程，深入探讨多种策略以提升问题解决能力。然而，一个关键问题仍待解决：如何在测试中智能且高效地扩展计算资源。本文首次全面研究了这些模型中普遍存在的过度思考问题，即在简单问题上过度分配计算资源却收益甚微。我们从结果和过程两个角度引入了新型效率指标，用于评估 o1 类模型对计算资源的合理利用。通过自训练范式，我们提出了解决过度思考的策略，优化推理过程的同时不牺牲准确性。实验结果表明，我们的方法成功降低了计算开销，同时在 GSM8K、MATH500、GPQA 和 AIME 等不同难度级别的测试集上保持了模型性能。

> The remarkable performance of models like the OpenAI o1 can be attributed to their ability to emulate human-like long-time thinking during inference. These models employ extended chain-of-thought (CoT) processes, exploring multiple strategies to enhance problem-solving capabilities. However, a critical question remains: How to intelligently and efficiently scale computational resources during testing. This paper presents the first comprehensive study on the prevalent issue of overthinking in these models, where excessive computational resources are allocated for simple problems with minimal benefit. We introduce novel efficiency metrics from both outcome and process perspectives to evaluate the rational use of computational resources by o1-like models. Using a self-training paradigm, we propose strategies to mitigate overthinking, streamlining reasoning processes without compromising accuracy. Experimental results show that our approach successfully reduces computational overhead while preserving model performance across a range of testsets with varying difficulty levels, such as GSM8K, MATH500, GPQA, and AIME.

[Arxiv](https://arxiv.org/abs/2412.21187)