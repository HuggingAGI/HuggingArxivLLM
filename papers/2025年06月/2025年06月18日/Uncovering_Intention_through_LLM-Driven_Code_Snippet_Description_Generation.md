# 揭示意图：基于 LLM 的代码片段描述生成

发布时间：2025年06月18日

`LLM应用` `软件开发` `文档生成`

> Uncovering Intention through LLM-Driven Code Snippet Description Generation

# 摘要

> 记录代码片段是至关重要的，它能够帮助开发者和用户准确地关注到关键区域。例如，使用示例和其他应用程序编程接口（API）的文档，对于第三方库来说尤其重要。随着大型语言模型（LLMs）的兴起，我们的研究目标是探索开发者常用的描述类型，并评估LLM（在此情况下为Llama）在支持描述生成方面的表现。我们采用了NPM代码片段数据集，该数据集包含185,412个包和1,024,579个代码片段。从中，我们选取了400个代码片段及其描述作为样本。首先，我们的手动分类发现，大多数原始描述（55.5%）的重点在于基于示例的用法。这一发现突显了清晰文档的重要性，因为某些描述缺乏足够的细节来传达意图。其次，LLM正确识别了大多数原始描述为“示例”（79.75%），这与我们手动分类的结果一致，表明了其具有良好的泛化能力。第三，与原始描述相比，生成的描述平均相似度得分为0.7173，这表明有一定的相关性，但仍有提升空间。得分低于0.9意味着存在一些不相关性。我们的研究结果表明，根据代码片段的任务不同，文档的意图可能有所不同，它可能不仅仅是使用说明或安装指南，还可能作为任何库用户的描述性学习示例。

> Documenting code snippets is essential to pinpoint key areas where both developers and users should pay attention. Examples include usage examples and other Application Programming Interfaces (APIs), which are especially important for third-party libraries. With the rise of Large Language Models (LLMs), the key goal is to investigate the kinds of description developers commonly use and evaluate how well an LLM, in this case Llama, can support description generation. We use NPM Code Snippets, consisting of 185,412 packages with 1,024,579 code snippets. From there, we use 400 code snippets (and their descriptions) as samples. First, our manual classification found that the majority of original descriptions (55.5%) highlight example-based usage. This finding emphasizes the importance of clear documentation, as some descriptions lacked sufficient detail to convey intent. Second, the LLM correctly identified the majority of original descriptions as "Example" (79.75%), which is identical to our manual finding, showing a propensity for generalization. Third, compared to the originals, the produced description had an average similarity score of 0.7173, suggesting relevance but room for improvement. Scores below 0.9 indicate some irrelevance. Our results show that depending on the task of the code snippet, the intention of the document may differ from being instructions for usage, installations, or descriptive learning examples for any user of a library.

[Arxiv](https://arxiv.org/abs/2506.15453)