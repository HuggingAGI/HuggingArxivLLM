# 大型语言模型结合人类在环验证，助力系统综述数据提取

发布时间：2025年01月20日

`LLM应用

理由：这篇论文探讨了使用大型语言模型（LLMs）来加速系统综述中的数据提取过程，并开发了一个工具（AIDE）来简化基于LLMs的人类参与数据提取流程。这属于LLM在实际应用中的使用，因此归类为LLM应用。` `文献综述`

> Large Language Models with Human-In-The-Loop Validation for Systematic Review Data Extraction

# 摘要

> 系统综述通常耗时费力，传统上需要人工筛选和提取数据。然而，大型语言模型（LLMs）有望大幅加速这一过程。在一项初步研究中，我们发现LLMs潜力巨大，随后我们探索了使用免费LLMs提取系统综述数据的方法。我们使用三种不同的LLMs，从112项研究中提取了24种数据，包括9个明确变量和15个分类变量。结果显示，Gemini 1.5 Flash、Gemini 1.5 Pro和Mistral Large 2的表现相当不错，提取数据与人工编码的一致性分别为71.17%、72.14%和62.43%。尽管结果令人鼓舞，但也表明在AI辅助数据提取中，人类参与（HIL）不可或缺。为此，我们开发了一个免费开源工具（AIDE），旨在简化基于LLMs的HIL数据提取流程。

> Systematic reviews are time-consuming endeavors. Historically speaking, knowledgeable humans have had to screen and extract data from studies before it can be analyzed. However, large language models (LLMs) hold promise to greatly accelerate this process. After a pilot study which showed great promise, we investigated the use of freely available LLMs for extracting data for systematic reviews. Using three different LLMs, we extracted 24 types of data, 9 explicitly stated variables and 15 derived categorical variables, from 112 studies that were included in a published scoping review. Overall we found that Gemini 1.5 Flash, Gemini 1.5 Pro, and Mistral Large 2 performed reasonably well, with 71.17%, 72.14%, and 62.43% of data extracted being consistent with human coding, respectively. While promising, these results highlight the dire need for a human-in-the-loop (HIL) process for AI-assisted data extraction. As a result, we present a free, open-source program we developed (AIDE) to facilitate user-friendly, HIL data extraction with LLMs.

[Arxiv](https://arxiv.org/abs/2501.11840)