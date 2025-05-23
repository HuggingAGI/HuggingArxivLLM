# MuseRAG：大规模创意独创性评分

发布时间：2025年05月22日

`LLM应用` `创造力研究` `心理学`

> MuseRAG: Idea Originality Scoring At Scale

# 摘要

> 评估创意想法新颖性的客观途径是衡量其在群体中的稀有程度。这一方法在创造力研究中长期被采用，但难以在大规模上实现自动化。手动分类创意想法的不同表述来统计响应频率，这一过程费时费力，容易出错，并且在处理大规模语料库时显得脆弱。我们提出了一种经过心理测量验证的完全自动化流程，用于基于频率的新颖性评分。我们的方法MuseRAG结合了大型语言模型（LLMs）与一个外部编排的检索增强生成（RAG）框架。针对一个新的创意想法，系统会检索语义相似的先前创意分类，并通过零样本提示让LLM判断新想法是属于现有分类还是形成了一个新的分类。由此产生的分类结果使得可以计算基于频率的新颖性指标。在五个数据集（N=1143，n_ideas=16294）上，MuseRAG在创意想法的聚类结构和分辨率（AMI=0.59）以及个体层面的评分（r=0.89）上与人工标注者的表现相匹配——同时展现出强大的收敛效度和外部效度。我们的工作实现了意图敏感且与人类一致的大规模新颖性评分，从而助力创造力研究。

> An objective, face-valid way to assess the originality of creative ideas is to measure how rare each idea is within a population -- an approach long used in creativity research but difficult to automate at scale. Tabulating response frequencies via manual bucketing of idea rephrasings is labor-intensive, error-prone, and brittle under large corpora. We introduce a fully automated, psychometrically validated pipeline for frequency-based originality scoring. Our method, MuseRAG, combines large language models (LLMs) with an externally orchestrated retrieval-augmented generation (RAG) framework. Given a new idea, the system retrieves semantically similar prior idea buckets and zero-shot prompts the LLM to judge whether the new idea belongs to an existing bucket or forms a new one. The resulting buckets enable computation of frequency-based originality metrics. Across five datasets (N=1143, n_ideas=16294), MuseRAG matches human annotators in idea clustering structure and resolution (AMI = 0.59) and in participant-level scoring (r = 0.89) -- while exhibiting strong convergent and external validity. Our work enables intent-sensitive, human-aligned originality scoring at scale to aid creativity research.

[Arxiv](https://arxiv.org/abs/2505.16232)