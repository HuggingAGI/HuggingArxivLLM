# 从短到长的泛化：长上下文指令调优的关键数据合成方法

发布时间：2025年02月21日

`LLM理论` `文档处理`

> Generalizing From Short to Long: Effective Data Synthesis for Long-Context Instruction Tuning

# 摘要

> 长上下文建模是大型语言模型 (LLMs) 近期研究的重点领域，因为许多实际应用场景需要处理较长的输入，例如文档处理。然而，当前研究主要集中在如何建模位置信息，而对指令微调等其他重要方面关注较少。长上下文训练样本的创建和使用既具挑战性又成本高昂。本文研究了如何为长上下文预训练模型的后训练阶段设计指令数据：需要多少以及何种类型的上下文才能实现最优且高效的后训练。我们发现，基于短上下文进行指令微调的模型能够有效推广至长上下文，同时指令难度和上下文构成等关键因素也起到了重要作用。基于这些发现，我们提出了一种名为上下文合成的新数据合成框架，该框架利用现成的大型语言模型生成高质量指令-答案对的扩展背景上下文。在文档级别基准测试（LongBench）上的实验结果表明，我们提出的方法优于以往的指令合成方法，并且接近于人工标注的长上下文指令数据的性能。项目将在以下链接中提供：https://github.com/NJUNLP/context-synthesis。


> Long-context modelling for large language models (LLMs) has been a key area of recent research because many real world use cases require reasoning over longer inputs such as documents. The focus of research into modelling long context has been on how to model position and there has been little investigation into other important aspects of language modelling such as instruction tuning. Long context training examples are challenging and expensive to create and use. In this paper, we investigate how to design instruction data for the post-training phase of a long context pre-trained model: how much and what type of context is needed for optimal and efficient post-training. Our controlled study reveals that models instruction-tuned on short contexts can effectively generalize to longer ones, while also identifying other critical factors such as instruction difficulty and context composition. Based on these findings, we propose context synthesis, a novel data synthesis framework that leverages off-the-shelf LLMs to generate extended background contexts for high-quality instruction-answer pairs. Experiment results on the document-level benchmark (LongBench) demonstrate that our proposed approach outperforms previous instruction synthesis approaches and comes close to the performance of human-annotated long-context instruction data. The project will be available at: https://github.com/NJUNLP/context-synthesis.

[Arxiv](https://arxiv.org/abs/2502.15592)