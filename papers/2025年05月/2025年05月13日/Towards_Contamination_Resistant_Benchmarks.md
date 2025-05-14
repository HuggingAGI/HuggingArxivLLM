# 迈向抗污染基准测试

发布时间：2025年05月13日

`LLM理论

理由：这篇论文探讨了大型语言模型评估中的污染问题，并提出了一种抗污染能力的基准测试方法。它涉及模型的评估和理论探讨，属于LLM理论类别。`

> Towards Contamination Resistant Benchmarks

# 摘要

> 大型语言模型（LLMs）的飞速发展彻底改变了自然语言处理的格局。正确评估 LLMs 对于理解其潜力和解决安全等问题至关重要。然而，LLM 评估面临诸多挑战，其中污染问题尤为突出，它严重削弱了评估结果的可靠性。在这项研究中，我们提出了抗污染能力的概念，以应对这一挑战。我们基于凯撒密码（例如，当偏移量为1时，“ab”变为“bc”）提出了一种基准测试，尽管其简单，但它是一个抗污染基准的优秀示例。我们在多种设置下，使用这一基准测试了广泛使用的 LLMs，发现当污染得到控制时，这些模型在该基准上表现挣扎。我们的发现揭示了当前 LLMs 的问题，并提出了关于其真实能力的重要问题。我们的工作为抗污染基准的发展做出了贡献，使 LLM 评估更加严格，并为理解 LLMs 的真实能力和局限性提供了见解。

> The rapid development of large language models (LLMs) has transformed the landscape of natural language processing. Evaluating LLMs properly is crucial for understanding their potential and addressing concerns such as safety. However, LLM evaluation is confronted by various factors, among which contamination stands out as a key issue that undermines the reliability of evaluations. In this work, we introduce the concept of contamination resistance to address this challenge. We propose a benchmark based on Caesar ciphers (e.g., "ab" to "bc" when the shift is 1), which, despite its simplicity, is an excellent example of a contamination resistant benchmark. We test this benchmark on widely used LLMs under various settings, and we find that these models struggle with this benchmark when contamination is controlled. Our findings reveal issues in current LLMs and raise important questions regarding their true capabilities. Our work contributes to the development of contamination resistant benchmarks, enabling more rigorous LLM evaluation and offering insights into the true capabilities and limitations of LLMs.

[Arxiv](https://arxiv.org/abs/2505.08389)