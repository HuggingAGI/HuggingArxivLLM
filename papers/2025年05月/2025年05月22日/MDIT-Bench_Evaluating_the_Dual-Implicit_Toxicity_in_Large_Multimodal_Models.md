# # **MDIT-Bench：评测大型多模态模型中的双隐式毒性**

发布时间：2025年05月22日

`LLM应用`

> MDIT-Bench: Evaluating the Dual-Implicit Toxicity in Large Multimodal Models

# 摘要

> 大型多模态模型 (LMMs) 的广泛应用引发了对模型毒性的担忧。当前研究主要关注显性毒性，而对偏见和歧视相关的隐性毒性关注较少。为弥补这一不足，我们提出了一种名为“双隐性毒性”的新型毒性类型，并开发了 MDIT-Bench：多模态双隐性毒性基准测试。我们采用多阶段人机交互上下文生成方法创建了包含双隐性毒性的 MDIT 数据集。基于该数据集，构建了 MDIT-Bench，涵盖 12 个类别、23 个子类别和 780 个主题，共计 317,638 个问题，用于评估模型对双隐性毒性的敏感性。该基准测试包含三个难度级别，并引入了一个衡量模型毒性差距的指标。实验中，我们对 13 个著名 LMM 进行了测试，结果显示这些模型在应对双隐性毒性方面表现不佳，尤其在困难级别上性能显著下降，表明这些模型中仍潜藏大量可激活的隐性毒性。数据可在 https://github.com/nuo1nuo/MDIT-Bench 获取。

> The widespread use of Large Multimodal Models (LMMs) has raised concerns about model toxicity. However, current research mainly focuses on explicit toxicity, with less attention to some more implicit toxicity regarding prejudice and discrimination. To address this limitation, we introduce a subtler type of toxicity named dual-implicit toxicity and a novel toxicity benchmark termed MDIT-Bench: Multimodal Dual-Implicit Toxicity Benchmark. Specifically, we first create the MDIT-Dataset with dual-implicit toxicity using the proposed Multi-stage Human-in-loop In-context Generation method. Based on this dataset, we construct the MDIT-Bench, a benchmark for evaluating the sensitivity of models to dual-implicit toxicity, with 317,638 questions covering 12 categories, 23 subcategories, and 780 topics. MDIT-Bench includes three difficulty levels, and we propose a metric to measure the toxicity gap exhibited by the model across them. In the experiment, we conducted MDIT-Bench on 13 prominent LMMs, and the results show that these LMMs cannot handle dual-implicit toxicity effectively. The model's performance drops significantly in hard level, revealing that these LMMs still contain a significant amount of hidden but activatable toxicity. Data are available at https://github.com/nuo1nuo/MDIT-Bench.

[Arxiv](https://arxiv.org/abs/2505.17144)