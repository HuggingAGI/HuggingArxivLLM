# DFPE: 多样化指纹集合，提升LLM性能

发布时间：2025年01月29日

`LLM应用

**理由**：该论文提出了一种集成方法（DFPE），通过整合多个大型语言模型（LLMs）的优势来提升模型性能。这种方法直接应用于LLMs的性能优化和任务处理，属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `机器学习`

> DFPE: A Diverse Fingerprint Ensemble for Enhancing LLM Performance

# 摘要

> 大型语言模型（LLMs）在多种自然语言处理任务中表现出色，但在复杂或多样化领域中表现参差不齐。我们提出了一种新颖的集成方法——多样化指纹集成（DFPE），通过整合多个LLMs的互补优势，提升模型性能。该方法包括：（1）基于响应“指纹”模式对模型进行聚类，（2）使用分位数过滤机制在每个主题级别剔除表现不佳的模型，（3）根据模型在主题级别的验证准确率动态分配权重。在MMLU基准测试中，DFPE的整体准确率比最佳单一模型高出3%，学科级别准确率高出5%。这一方法显著增强了LLMs的鲁棒性和泛化能力，展示了模型选择、多样性保持和性能驱动权重分配在应对复杂语言理解任务中的有效性。

> Large Language Models (LLMs) have shown remarkable capabilities across various natural language processing tasks but often struggle to excel uniformly in diverse or complex domains. We propose a novel ensemble method - Diverse Fingerprint Ensemble (DFPE), which leverages the complementary strengths of multiple LLMs to achieve more robust performance. Our approach involves: (1) clustering models based on response "fingerprints" patterns, (2) applying a quantile-based filtering mechanism to remove underperforming models at a per-subject level, and (3) assigning adaptive weights to remaining models based on their subject-wise validation accuracy. In experiments on the Massive Multitask Language Understanding (MMLU) benchmark, DFPE outperforms the best single model by 3% overall accuracy and 5% in discipline-level accuracy. This method increases the robustness and generalization of LLMs and underscores how model selection, diversity preservation, and performance-driven weighting can effectively address challenging, multi-faceted language understanding tasks.

[Arxiv](https://arxiv.org/abs/2501.17479)