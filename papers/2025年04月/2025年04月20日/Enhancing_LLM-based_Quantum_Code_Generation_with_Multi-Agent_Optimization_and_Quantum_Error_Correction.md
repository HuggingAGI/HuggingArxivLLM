# 通过多智能体优化与量子错误校正提升基于LLM的量子代码生成能力

发布时间：2025年04月20日

`LLM应用` `量子计算` `软件工程`

> Enhancing LLM-based Quantum Code Generation with Multi-Agent Optimization and Quantum Error Correction

# 摘要

> 基于大型语言模型的多智能体框架在利用测试驱动开发生成通用编程语言方面展现出巨大潜力，帮助开发者编写更精准和可靠的代码。然而，在特定领域编程语言的应用中，这些框架的潜力尚未完全释放，因为特定领域往往具有独特的优化机会，为定制化改进提供了可能。本文首次探索了针对量子程序的多智能体代码生成。通过识别量子设计中的独特优化点，如量子错误校正，我们提出了一种新型多智能体框架，专门用于生成精确且容错的量子代码。框架中的每个智能体专注于不同的优化任务，通过使用多遍推理的语义分析器，以及量子纠错码解码器，迭代地优化代码。我们还研究了推理时技术（如链式思维（Chain-of-Thought, CoT）和检索增强生成（Retrieval-Augmented Generation, RAG））在量子编程中的有效性，发现了与通用编程代码生成不同的观察结果。为了评估我们的方法，我们开发了一套测试用例，以衡量每种优化对生成代码准确性的影响。我们的研究结果表明，结构化链式思维等技术显著提高了量子算法的生成效果，准确率提升了高达50%。然而，我们也发现某些技术，如RAG，改进效果有限，仅提高了4%的准确率。此外，我们展示了AI辅助的量子错误预测与校正实例，证明了我们的多智能体框架在减少生成量子程序中的量子错误方面的有效性。

> Multi-agent frameworks with Large Language Models (LLMs) have become promising tools for generating general-purpose programming languages using test-driven development, allowing developers to create more accurate and robust code. However, their potential has not been fully unleashed for domain-specific programming languages, where specific domain exhibits unique optimization opportunities for customized improvement. In this paper, we take the first step in exploring multi-agent code generation for quantum programs. By identifying the unique optimizations in quantum designs such as quantum error correction, we introduce a novel multi-agent framework tailored to generating accurate, fault-tolerant quantum code. Each agent in the framework focuses on distinct optimizations, iteratively refining the code using a semantic analyzer with multi-pass inference, alongside an error correction code decoder. We also examine the effectiveness of inference-time techniques, like Chain-of-Thought (CoT) and Retrieval-Augmented Generation (RAG) in the context of quantum programming, uncovering observations that are different from general-purpose code generation. To evaluate our approach, we develop a test suite to measure the impact each optimization has on the accuracy of the generated code. Our findings indicate that techniques such as structured CoT significantly improve the generation of quantum algorithms by up to 50%. In contrast, we have also found that certain techniques such as RAG show limited improvement, yielding an accuracy increase of only 4%. Moreover, we showcase examples of AI-assisted quantum error prediction and correction, demonstrating the effectiveness of our multi-agent framework in reducing the quantum errors of generated quantum programs.

[Arxiv](https://arxiv.org/abs/2504.14557)