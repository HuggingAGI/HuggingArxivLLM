# 大型语言模型对科学研究总结的泛化偏差研究

发布时间：2025年03月28日

`LLM应用` `人工智能` `科学传播`

> Generalization Bias in Large Language Model Summarization of Scientific Research

# 摘要

> 大型语言模型（LLMs）驱动的AI聊天机器人能够快速将复杂科学信息转化为通俗易懂的内容，从而有望提升公众科学素养并支持科研工作。然而，LLMs在总结科学文本时，容易忽略限制研究结论范围的细节，导致研究结果的概括范围超出原始研究的支持范围。我们对包括ChatGPT-4o、ChatGPT-4.5、DeepSeek、LLaMA 3.3 70B和Claude 3.7 Sonnet在内的10个知名LLM进行了测试，对比分析了4900个LLM生成的摘要与原文。即使在明确要求准确性的提示下，大多数LLM生成的科学结果概括范围仍比原文更广，其中DeepSeek、ChatGPT-4o和LLaMA 3.3 70B在26%到73%的情况下存在过度概括。在直接比较LLM生成和人工编写的科学摘要时，LLM摘要包含广泛概括的可能性几乎是人工摘要的五倍（OR = 4.85，95% CI [3.06, 7.70]）。值得注意的是，较新的模型在概括准确性方面往往表现不如早期模型。我们的研究结果表明，许多广泛使用的LLM在科学结论上存在过度概括的强烈倾向，这可能导致对研究发现的大规模误读。我们提出了潜在的缓解策略，包括降低LLM的温度设置以及对LLM进行概括准确性的基准测试。

> Artificial intelligence chatbots driven by large language models (LLMs) have the potential to increase public science literacy and support scientific research, as they can quickly summarize complex scientific information in accessible terms. However, when summarizing scientific texts, LLMs may omit details that limit the scope of research conclusions, leading to generalizations of results broader than warranted by the original study. We tested 10 prominent LLMs, including ChatGPT-4o, ChatGPT-4.5, DeepSeek, LLaMA 3.3 70B, and Claude 3.7 Sonnet, comparing 4900 LLM-generated summaries to their original scientific texts. Even when explicitly prompted for accuracy, most LLMs produced broader generalizations of scientific results than those in the original texts, with DeepSeek, ChatGPT-4o, and LLaMA 3.3 70B overgeneralizing in 26 to 73% of cases. In a direct comparison of LLM-generated and human-authored science summaries, LLM summaries were nearly five times more likely to contain broad generalizations (OR = 4.85, 95% CI [3.06, 7.70]). Notably, newer models tended to perform worse in generalization accuracy than earlier ones. Our results indicate a strong bias in many widely used LLMs towards overgeneralizing scientific conclusions, posing a significant risk of large-scale misinterpretations of research findings. We highlight potential mitigation strategies, including lowering LLM temperature settings and benchmarking LLMs for generalization accuracy.

[Arxiv](https://arxiv.org/abs/2504.00025)