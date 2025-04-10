# 通过视觉程序逐步基准测试多模态 CoT 奖励模型

发布时间：2025年04月09日

`LLM应用` `人工智能`

> Benchmarking Multimodal CoT Reward Model Stepwise by Visual Program

# 摘要

> 大型语言模型（LLMs）在奖励信号应用方面取得了显著进展。然而，将其扩展至多模态领域时，我们面临三大核心挑战：繁重的标注任务、对单步奖励的过度依赖以及评估体系的不足。为解决这些问题，我们提出了一种创新方法——SVIP，它能够自动训练一种基于步骤级多维思考链（Chain-of-Thought, CoT）的奖励模型。SVIP通过生成解决视觉任务的代码，并将代码块的分析转化为对CoT步骤的评估，从而生成训练样本。随后，我们采用一种名为TriAtt-CoT的多头注意力机制来训练SVIP奖励模型。在多模态大型语言模型（MLLM）的整个训练流程中，SVIP奖励模型的优势显而易见。我们还为CoT奖励模型的训练和测试引入了一个基准测试集。实验结果表明，SVIP奖励模型在训练和推理时间的扩展性方面均提升了MLLM的性能，不仅在基准测试中取得了更优的结果，还有效减少了幻觉现象，同时增强了模型的推理能力。

> Recent advancements in reward signal usage for Large Language Models (LLMs) are remarkable. However, significant challenges exist when transitioning reward signal to the multimodal domain, including labor-intensive annotations, over-reliance on one-step rewards, and inadequate evaluation. To address these issues, we propose SVIP, a novel approach to train a step-level multi-dimensional Chain-of-Thought~(CoT) reward model automatically. It generates code for solving visual tasks and transforms the analysis of code blocks into the evaluation of CoT step as training samples. Then, we train SVIP-Reward model using a multi-head attention mechanism called TriAtt-CoT. The advantages of SVIP-Reward are evident throughout the entire process of MLLM. We also introduce a benchmark for CoT reward model training and testing. Experimental results demonstrate that SVIP-Reward improves MLLM performance across training and inference-time scaling, yielding better results on benchmarks while reducing hallucinations and enhancing reasoning ability.

[Arxiv](https://arxiv.org/abs/2504.06606)