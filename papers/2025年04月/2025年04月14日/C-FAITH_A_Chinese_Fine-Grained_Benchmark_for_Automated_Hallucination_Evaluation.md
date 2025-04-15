# C-FAITH：用于自动幻觉生成评估的中文细粒度基准测试

发布时间：2025年04月14日

`LLM应用

摘要讨论了使用HaluAgent框架来自动构建QA数据集，用于评估大型语言模型的幻觉问题，属于应用层面的研究。` `问答系统`

> C-FAITH: A Chinese Fine-Grained Benchmark for Automated Hallucination Evaluation

# 摘要

> 尽管大型语言模型发展迅速，但幻觉生成问题仍严重制约其广泛应用。幻觉研究需要动态且细致的评估，然而现有中文幻觉基准大多依赖人工标注，自动高效评估难度极大。

为解决这一难题，我们提出HaluAgent，一个能基于知识文档自动构建细致QA数据集的智能框架。实验表明，手动设计规则和优化提示能显著提升数据质量。借助HaluAgent，我们构建了C-FAITH，一个基于1,399份网络爬取知识文档的中文QA幻觉基准，包含60,702条数据。通过C-FAITH，我们对16个主流LLM进行了全面评估，结果和分析详见本文。

> Despite the rapid advancement of large language models, they remain highly susceptible to generating hallucinations, which significantly hinders their widespread application. Hallucination research requires dynamic and fine-grained evaluation. However, most existing hallucination benchmarks (especially in Chinese language) rely on human annotations, making automatical and cost-effective hallucination evaluation challenging. To address this, we introduce HaluAgent, an agentic framework that automatically constructs fine-grained QA dataset based on some knowledge documents. Our experiments demonstrate that the manually designed rules and prompt optimization can improve the quality of generated data. Using HaluAgent, we construct C-FAITH, a Chinese QA hallucination benchmark created from 1,399 knowledge documents obtained from web scraping, totaling 60,702 entries. We comprehensively evaluate 16 mainstream LLMs with our proposed C-FAITH, providing detailed experimental results and analysis.

[Arxiv](https://arxiv.org/abs/2504.10167)