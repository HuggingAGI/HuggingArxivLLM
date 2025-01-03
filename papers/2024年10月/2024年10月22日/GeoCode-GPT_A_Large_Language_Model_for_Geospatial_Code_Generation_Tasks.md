# GeoCode-GPT: 专为地理空间代码生成任务打造的大型语言模型

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文主要讨论了如何通过预训练和微调技术（如QLoRA和LoRA）来提升大型语言模型（LLM）在地理空间代码生成任务中的性能。论文提出了一个专门用于地理空间代码生成的LLM（GeoCode-GPT-7B），并构建了相应的评估框架和数据集。这些工作都属于LLM在实际应用中的优化和扩展，因此分类为“LLM应用”。` `地理信息` `代码生成`

> GeoCode-GPT: A Large Language Model for Geospatial Code Generation Tasks

# 摘要

> # 摘要
随着地球科学对时空数据和建模任务需求的激增，地理空间代码生成技术已成为提升生产力的关键。尽管LLMs在代码生成任务中展现出潜力，但由于缺乏领域知识和代码库，它们在地理空间代码生成中常面临拒绝编码或幻觉问题。为此，本文开源了GeoCode-PT和GeoCode-SFT语料库及GeoCode-Eval评估数据集。通过QLoRA和LoRA的预训练与微调，我们推出了首个专注于地理空间代码生成的LLM——GeoCode-GPT-7B，基于Code Llama-7B微调而成。我们还构建了一个全面的地理空间代码评估框架，结合选项匹配、专家验证和LLMs提示工程评分，并利用GeoCode-Eval数据集对GeoCode-GPT-7B进行了系统评估。实验结果显示，GeoCode-GPT在多项选择准确性、代码摘要能力和代码生成能力上分别领先其他模型9.1%-32.1%、1.7%-25.4%和1.2%-25.1%。本文不仅为提升LLMs在地理空间代码生成中的性能提供了解决方案和实证验证，还拓展了领域特定模型的应用边界，为解锁其在地理空间代码生成中的潜力提供了宝贵见解。

> The increasing demand for spatiotemporal data and modeling tasks in geosciences has made geospatial code generation technology a critical factor in enhancing productivity. Although large language models (LLMs) have demonstrated potential in code generation tasks, they often encounter issues such as refusal to code or hallucination in geospatial code generation due to a lack of domain-specific knowledge and code corpora. To address these challenges, this paper presents and open-sources the GeoCode-PT and GeoCode-SFT corpora, along with the GeoCode-Eval evaluation dataset. Additionally, by leveraging QLoRA and LoRA for pretraining and fine-tuning, we introduce GeoCode-GPT-7B, the first LLM focused on geospatial code generation, fine-tuned from Code Llama-7B. Furthermore, we establish a comprehensive geospatial code evaluation framework, incorporating option matching, expert validation, and prompt engineering scoring for LLMs, and systematically evaluate GeoCode-GPT-7B using the GeoCode-Eval dataset. Experimental results show that GeoCode-GPT outperforms other models in multiple-choice accuracy by 9.1% to 32.1%, in code summarization ability by 1.7% to 25.4%, and in code generation capability by 1.2% to 25.1%. This paper provides a solution and empirical validation for enhancing LLMs' performance in geospatial code generation, extends the boundaries of domain-specific model applications, and offers valuable insights into unlocking their potential in geospatial code generation.

[Arxiv](https://arxiv.org/abs/2410.17031)