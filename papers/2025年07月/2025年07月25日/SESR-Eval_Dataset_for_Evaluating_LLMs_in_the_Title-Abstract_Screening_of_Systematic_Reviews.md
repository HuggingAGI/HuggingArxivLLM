# # SESR-Eval：专为评估系统综述中标题-摘要筛选任务而设计的大型语言模型数据集

发布时间：2025年07月25日

`LLM应用` `软件工程`

> SESR-Eval: Dataset for Evaluating LLMs in the Title-Abstract Screening of Systematic Reviews

# 摘要

> 背景：大型语言模型（LLMs）在系统综述（SRs）的标题-摘要筛选中展现出潜力，但性能评估尚不完善。目标：构建基准数据集评估LLMs在标题-摘要筛选中的表现，并为软件工程中使用LLMs提供可行性依据。方法：从169个系统综述研究中筛选出24个构建数据集，测试了9个LLMs的筛选能力。结果：SESR-Eval数据集包含34,528个标签化原始研究，来自24个软件工程期刊的次级研究。大多数LLMs表现相近，次级研究间的差异大于LLMs间的差异，且使用LLM的成本低廉，每项次级研究不足40美元。结论：本基准测试可监控AI在软件工程系统综述筛选中的表现。目前，LLMs尚未达到推荐用于自动化标题-摘要筛选的水平，因其准确率差异大，且无LLM能在合理精度下实现高召回率。未来，我们将研究影响LLM筛选性能的因素。

> Background: The use of large language models (LLMs) in the title-abstract screening process of systematic reviews (SRs) has shown promising results, but suffers from limited performance evaluation. Aims: Create a benchmark dataset to evaluate the performance of LLMs in the title-abstract screening process of SRs. Provide evidence whether using LLMs in title-abstract screening in software engineering is advisable. Method: We start with 169 SR research artifacts and find 24 of those to be suitable for inclusion in the dataset. Using the dataset we benchmark title-abstract screening using 9 LLMs. Results: We present the SESR-Eval (Software Engineering Systematic Review Evaluation) dataset containing 34,528 labeled primary studies, sourced from 24 secondary studies published in software engineering (SE) journals. Most LLMs performed similarly and the differences in screening accuracy between secondary studies are greater than differences between LLMs. The cost of using an LLM is relatively low - less than $40 per secondary study even for the most expensive model. Conclusions: Our benchmark enables monitoring AI performance in the screening task of SRs in software engineering. At present, LLMs are not yet recommended for automating the title-abstract screening process, since accuracy varies widely across secondary studies, and no LLM managed a high recall with reasonable precision. In future, we plan to investigate factors that influence LLM screening performance between studies.

[Arxiv](https://arxiv.org/abs/2507.19027)