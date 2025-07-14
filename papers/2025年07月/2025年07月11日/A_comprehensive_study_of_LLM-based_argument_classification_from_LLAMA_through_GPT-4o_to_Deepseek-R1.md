# 深入研究：基于LLM的论证分类，从LLAMA，经由GPT-4o，直至Deepseek-R1

发布时间：2025年07月11日

`LLM应用` `论证挖掘`

> A comprehensive study of LLM-based argument classification: from LLAMA through GPT-4o to Deepseek-R1

# 摘要

> 论证挖掘（AM）是一个跨学科的研究领域，整合了逻辑、哲学、语言学、修辞学、法律、心理学和计算机科学的见解。它专注于自动识别和提取论证成分，如前提和主张，并分析它们之间的关系，如支持、攻击或中立。最近，随着大型语言模型（LLMs）的出现，该领域取得了显著进展，与传统方法和其他深度学习模型相比，LLMs在分析和提取论证语义方面更加高效。尽管有许多基准用于测试和验证LLM的质量，但在公开可用的论证分类数据库中，关于这些模型运行的研究和结果仍然匮乏。本文介绍了一项对选定LLM的研究，使用了Args.me和UKP等多样化数据集。测试的模型包括GPT、Llama和DeepSeek的不同版本，以及结合Chain-of-Thoughts算法的增强推理变体。结果显示，ChatGPT-4o在论证分类基准中表现最佳。对于集成推理能力的模型，Deepseek-R1表现最为出色。然而，尽管GPT-4o和Deepseek-R1表现优异，它们仍然会犯错误。文章讨论了所有模型中最常见的错误。据我们所知，这项工作是首次使用LLM和提示算法对所述数据集进行更广泛的分析。该工作还展示了已知提示算法在论证分析中的某些弱点，同时指出了改进的方向。这项工作的附加价值在于对现有论证数据集的深入分析，并展示了它们的不足。

> Argument mining (AM) is an interdisciplinary research field that integrates insights from logic, philosophy, linguistics, rhetoric, law, psychology, and computer science. It involves the automatic identification and extraction of argumentative components, such as premises and claims, and the detection of relationships between them, such as support, attack, or neutrality. Recently, the field has advanced significantly, especially with the advent of large language models (LLMs), which have enhanced the efficiency of analyzing and extracting argument semantics compared to traditional methods and other deep learning models. There are many benchmarks for testing and verifying the quality of LLM, but there is still a lack of research and results on the operation of these models in publicly available argument classification databases. This paper presents a study of a selection of LLM's, using diverse datasets such as Args.me and UKP. The models tested include versions of GPT, Llama, and DeepSeek, along with reasoning-enhanced variants incorporating the Chain-of-Thoughts algorithm. The results indicate that ChatGPT-4o outperforms the others in the argument classification benchmarks. In case of models incorporated with reasoning capabilities, the Deepseek-R1 shows its superiority. However, despite their superiority, GPT-4o and Deepseek-R1 still make errors. The most common errors are discussed for all models. To our knowledge, the presented work is the first broader analysis of the mentioned datasets using LLM and prompt algorithms. The work also shows some weaknesses of known prompt algorithms in argument analysis, while indicating directions for their improvement. The added value of the work is the in-depth analysis of the available argument datasets and the demonstration of their shortcomings.

[Arxiv](https://arxiv.org/abs/2507.08621)