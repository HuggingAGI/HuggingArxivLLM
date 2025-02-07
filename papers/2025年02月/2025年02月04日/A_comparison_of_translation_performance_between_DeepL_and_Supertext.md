# DeepL 与 Supertext 的翻译性能对比

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论了机器翻译（MT）系统在依赖大型语言模型（LLMs）时，如何通过评估未分段文本的翻译表现来捕捉其利用扩展上下文的能力。研究比较了两个商业MT系统（DeepL和Supertext）的翻译质量，并强调了上下文敏感的评估方法的重要性。这涉及到LLM在实际应用中的表现和评估方法，因此属于LLM应用的范畴。` `机器翻译` `语言模型`

> A comparison of translation performance between DeepL and Supertext

# 摘要

> 随着机器翻译（MT）系统越来越多地依赖大型语言模型（LLMs），可靠的质量评估需要能够捕捉其利用扩展上下文能力的方法。本研究通过评估未分段文本的翻译表现，比较了DeepL和Supertext两个商业MT系统。我们评估了四个语言方向的翻译质量，专业翻译人员在完整的文档级上下文中进行片段评估。虽然片段级评估显示在大多数情况下两者无明显优劣，但文档级分析表明，在四个语言方向中有三个更倾向于Supertext，表明其在长文本中的一致性更佳。我们提倡采用更多上下文敏感的评估方法，以确保MT质量评估反映实际可用性。所有评估数据和脚本已发布在https://github.com/supertext/evaluation_deepl_supertext，供进一步分析和复现。

> As strong machine translation (MT) systems are increasingly based on large language models (LLMs), reliable quality benchmarking requires methods that capture their ability to leverage extended context. This study compares two commercial MT systems -- DeepL and Supertext -- by assessing their performance on unsegmented texts. We evaluate translation quality across four language directions with professional translators assessing segments with full document-level context. While segment-level assessments indicate no strong preference between the systems in most cases, document-level analysis reveals a preference for Supertext in three out of four language directions, suggesting superior consistency across longer texts. We advocate for more context-sensitive evaluation methodologies to ensure that MT quality assessments reflect real-world usability. We release all evaluation data and scripts for further analysis and reproduction at https://github.com/supertext/evaluation_deepl_supertext.

[Arxiv](https://arxiv.org/abs/2502.02577)