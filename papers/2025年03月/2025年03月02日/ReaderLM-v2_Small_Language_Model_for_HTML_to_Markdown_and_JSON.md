# ReaderLM-v2: 小型语言模型，用于将HTML转换为Markdown和JSON

发布时间：2025年03月02日

`LLM应用` `信息抽取`

> ReaderLM-v2: Small Language Model for HTML to Markdown and JSON

# 摘要

> 我们很高兴推出ReaderLM-v2——一款专为高效提取网页内容而设计的紧凑型15亿参数语言模型。该模型能够处理长达512K tokens的文档，并以极高的准确率将杂乱的HTML转化为整洁的Markdown或JSON格式，堪称大型语言模型实现 grounding 的理想之选。模型的卓越性能得益于两大创新：(1) 一个三阶段数据合成流水线，通过迭代式地起草、优化和改进网络内容提取过程，生成高质量且多样化的训练数据；(2) 一个融合持续预训练与多目标优化的统一训练框架。在精心挑选的基准测试中，ReaderLM-v2的表现超越了GPT-4o-2024-08-06等更大规模的模型，胜出15-20%，尤其在处理超过100K tokens的长文档时表现尤为出色，同时保持了更低的计算需求。

> We present ReaderLM-v2, a compact 1.5 billion parameter language model designed for efficient web content extraction. Our model processes documents up to 512K tokens, transforming messy HTML into clean Markdown or JSON formats with high accuracy -- making it an ideal tool for grounding large language models. The model's effectiveness results from two key innovations: (1) a three-stage data synthesis pipeline that generates high quality, diverse training data by iteratively drafting, refining, and critiquing web content extraction; and (2) a unified training framework combining continuous pre-training with multi-objective optimization. Intensive evaluation demonstrates that ReaderLM-v2 outperforms GPT-4o-2024-08-06 and other larger models by 15-20\% on carefully curated benchmarks, particularly excelling at documents exceeding 100K tokens, while maintaining significantly lower computational requirements.

[Arxiv](https://arxiv.org/abs/2503.01151)