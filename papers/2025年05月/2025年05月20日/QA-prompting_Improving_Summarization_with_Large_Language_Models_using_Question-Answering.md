# QA提示：利用问答提升大型语言模型的总结能力

发布时间：2025年05月20日

`LLM应用` `文本生成` `摘要生成`

> QA-prompting: Improving Summarization with Large Language Models using Question-Answering

# 摘要

> 语言模型（LMs）彻底改变了自然语言处理领域，通过提示和上下文学习实现了高质量文本生成。然而，模型在处理长上下文摘要时常常遇到位置偏见问题，导致关键信息提取效果不佳。目前，虽然可以通过微调、流水线处理或复杂技术来改善这一问题，但这些方法各有挑战。

为了解决这些问题，我们提出了一种名为QA-prompting的简单提示方法，用于摘要生成。该方法在生成摘要之前，利用问答作为中间步骤，提取关键信息并丰富文本上下文，从而缓解位置偏见问题。这种方法无需微调或流水线处理，只需每个任务一次LM调用即可提升摘要质量。

在多个跨领域数据集上，使用十种先进的预训练模型进行的实验表明，QA-prompting不仅超越了传统方法，还优于其他先进方法，ROUGE分数提升了29%。这为摘要生成提供了一种有效且可扩展的解决方案，并突显了在特定领域中选择最优问题的重要性。

> Language Models (LMs) have revolutionized natural language processing, enabling high-quality text generation through prompting and in-context learning. However, models often struggle with long-context summarization due to positional biases, leading to suboptimal extraction of critical information. There are techniques to improve this with fine-tuning, pipelining, or using complex techniques, which have their own challenges. To solve these challenges, we propose QA-prompting - a simple prompting method for summarization that utilizes question-answering as an intermediate step prior to summary generation. Our method extracts key information and enriches the context of text to mitigate positional biases and improve summarization in a single LM call per task without requiring fine-tuning or pipelining. Experiments on multiple datasets belonging to different domains using ten state-of-the-art pre-trained models demonstrate that QA-prompting outperforms baseline and other state-of-the-art methods, achieving up to 29% improvement in ROUGE scores. This provides an effective and scalable solution for summarization and highlights the importance of domain-specific question selection for optimal performance.

[Arxiv](https://arxiv.org/abs/2505.14347)