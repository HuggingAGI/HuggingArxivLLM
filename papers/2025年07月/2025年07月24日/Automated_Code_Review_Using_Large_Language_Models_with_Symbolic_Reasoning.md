# 基于大型语言模型的自动化代码审查，结合符号推理

发布时间：2025年07月24日

`LLM应用` `软件工程` `代码审查`

> Automated Code Review Using Large Language Models with Symbolic Reasoning

# 摘要

> 代码审查是软件开发中维护代码质量的关键环节，但人工审查主观且耗时。鉴于代码审查的规则性特点，自动化是大势所趋。近年来，人工智能技术，尤其是大型语言模型（LLMs），在这一领域取得了显著进展。然而，现有模型在逻辑推理能力方面仍显不足，难以全面理解和评估代码。为此，我们提出了一种结合符号推理技术与LLMs的混合方法，旨在实现代码审查的自动化。通过在CodexGlue数据集上的实验，我们对比了CodeT5、CodeBERT和GraphCodeBERT等模型，验证了符号推理与提示技术结合LLMs的有效性。实验结果表明，该方法显著提升了自动化代码审查的准确性和效率。

> Code review is one of the key processes in the software development lifecycle and is essential to maintain code quality. However, manual code review is subjective and time consuming. Given its rule-based nature, code review is well suited for automation. In recent years, significant efforts have been made to automate this process with the help of artificial intelligence. Recent developments in Large Language Models (LLMs) have also emerged as a promising tool in this area, but these models often lack the logical reasoning capabilities needed to fully understand and evaluate code. To overcome this limitation, this study proposes a hybrid approach that integrates symbolic reasoning techniques with LLMs to automate the code review process. We tested our approach using the CodexGlue dataset, comparing several models, including CodeT5, CodeBERT, and GraphCodeBERT, to assess the effectiveness of combining symbolic reasoning and prompting techniques with LLMs. Our results show that this approach improves the accuracy and efficiency of automated code review.

[Arxiv](https://arxiv.org/abs/2507.18476)