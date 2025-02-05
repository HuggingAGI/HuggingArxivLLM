# ReSpark: 借助历史数据报告，利用LLMs生成全新报告

发布时间：2025年02月04日

`LLM应用

解释：这篇论文讨论了如何利用大型语言模型（LLMs）来生成数据报告，并提出了ReSpark方法，该方法利用现有数据报告作为参考来生成新报告。这涉及到LLMs在数据处理和文本生成方面的应用，因此属于“LLM应用”类别。` `数据分析` `报告生成`

> ReSpark: Leveraging Previous Data Reports as References to Generate New Reports with LLMs

# 摘要

> 创建数据报告耗时费力，需要对数据进行反复探索和理解，再提炼出见解。尽管大型语言模型（LLMs）在数据处理和文本生成方面表现出色，但它们往往难以生成完全满足用户需求的完整数据报告。主要挑战在于如何将完整的分析逻辑有效传达给LLMs，而用户也常常为确定全面的分析逻辑感到头疼。为此，我们提出了ReSpark，一种基于LLM的方法，利用现有数据报告作为参考来生成新报告。给定数据表后，ReSpark会搜索类似主题的报告，将其解析为与分析目标相关的相互依赖的片段，并用新数据执行这些片段。它能识别不一致之处，并定制目标、数据转换和文本描述。用户还可以实时查看输出，插入新目标，并修改报告内容。通过对比和用户研究，我们验证了ReSpark的有效性。

> Creating data reports is time-consuming, as it requires iterative exploration and understanding of data, followed by summarizing the insights. While large language models (LLMs) are powerful tools for data processing and text generation, they often struggle to produce complete data reports that fully meet user expectations. One significant challenge is effectively communicating the entire analysis logic to LLMs. Moreover, determining a comprehensive analysis logic can be mentally taxing for users. To address these challenges, we propose ReSpark, an LLM-based method that leverages existing data reports as references for creating new ones. Given a data table, ReSpark searches for similar-topic reports, parses them into interdependent segments corresponding to analytical objectives, and executes them with new data. It identifies inconsistencies and customizes the objectives, data transformations, and textual descriptions. ReSpark allows users to review real-time outputs, insert new objectives, and modify report content. Its effectiveness was evaluated through comparative and user studies.

[Arxiv](https://arxiv.org/abs/2502.02329)