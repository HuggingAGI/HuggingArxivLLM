# 基于KG-SMILE的可解释知识图谱检索增强生成（KG-RAG）

发布时间：2025年09月03日

`RAG` `医疗健康`

> Explainable Knowledge Graph Retrieval-Augmented Generation (KG-RAG) with KG-SMILE

# 摘要

> 生成式人工智能（如大型语言模型LLMs）发展迅猛，成果斐然，但仍存在幻觉输出和无法验证的问题，在医疗等对精度要求极高的敏感领域，其可靠性仍受制约。检索增强生成（RAG）技术通过将输出锚定在外部知识中提升了准确性，但本质上仍是一个不透明的黑箱，且严重依赖数据质量。为此，我们开发了一种与具体方法无关的基于扰动的框架——知识图谱（KG）-SMILE，它利用SMILE实现了图RAG在令牌和组件层面的互操作性。该框架通过施加受控扰动、计算相似度及训练加权线性替代模型，精准定位出对生成结果影响最大的图实体与关系，有效提升了RAG的透明度。我们通过保真度、忠实度、一致性、稳定性和准确性等全面的归因指标体系对KG-SMILE进行评估，结果显示其能生成稳定且符合人类认知的解释，在模型效果与可解释性之间取得平衡，为机器学习技术带来更高的透明度和可信度。

> Generative AI, such as Large Language Models (LLMs), has achieved impressive progress but still produces hallucinations and unverifiable claims, limiting reliability in sensitive domains. Retrieval-Augmented Generation (RAG) improves accuracy by grounding outputs in external knowledge, especially in domains like healthcare, where precision is vital. However, RAG remains opaque and essentially a black box, heavily dependent on data quality. We developed a method-agnostic, perturbation-based framework that provides token and component-level interoperability for Graph RAG using SMILE and named it as Knowledge-Graph (KG)-SMILE. By applying controlled perturbations, computing similarities, and training weighted linear surrogates, KG-SMILE identifies the graph entities and relations most influential to generated outputs, thereby making RAG more transparent. We evaluate KG-SMILE using comprehensive attribution metrics, including fidelity, faithfulness, consistency, stability, and accuracy. Our findings show that KG-SMILE produces stable, human-aligned explanations, demonstrating its capacity to balance model effectiveness with interpretability and thereby fostering greater transparency and trust in machine learning technologies.

[Arxiv](https://arxiv.org/abs/2509.03626)