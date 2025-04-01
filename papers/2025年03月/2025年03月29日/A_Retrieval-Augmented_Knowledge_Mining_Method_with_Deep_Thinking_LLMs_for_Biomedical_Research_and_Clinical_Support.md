# 基于深度思考大语言模型的检索增强知识挖掘方法，用于生物医学研究和临床支持

发布时间：2025年03月29日

`LLM应用` `生物医学`

> A Retrieval-Augmented Knowledge Mining Method with Deep Thinking LLMs for Biomedical Research and Clinical Support

# 摘要

> 知识图谱和大型语言模型（LLMs）在生物医学知识整合与推理中发挥着关键作用，不仅能够对科学文章进行结构化整理，还能揭示复杂的语义关系。然而，现有方法在知识图谱构建和推理能力方面仍面临诸多挑战：复杂术语、数据异质性以及知识的快速演变限制了知识图谱的构建，而大型语言模型在跨文档关联发现和推理路径构建方面表现有限。针对这些问题，我们提出了一种创新性管道方法：首先利用LLMs从大规模文章中构建生物医学知识图谱（BioStrataKG），并构建跨文档问答数据集（BioCDQA）来评估潜在知识检索与多跳推理能力。在此基础上，我们提出了集成与渐进式增强的检索增强推理（IP-RAR），通过集成推理式检索最大化信息召回，同时借助渐进推理式生成精炼知识，利用自我反思实现深度思考与精准语境理解，从而显著提升检索精度与知识推理能力。实验结果表明，相较于现有方法，IP-RAR使文档检索F1值提升了20%，答案生成准确率提升了25%。这一框架不仅帮助医生高效整合治疗证据，为个性化用药方案提供支持，还赋能研究人员分析研究进展与空白，加速科学发现与决策过程。

> Knowledge graphs and large language models (LLMs) are key tools for biomedical knowledge integration and reasoning, facilitating structured organization of scientific articles and discovery of complex semantic relationships. However, current methods face challenges: knowledge graph construction is limited by complex terminology, data heterogeneity, and rapid knowledge evolution, while LLMs show limitations in retrieval and reasoning, making it difficult to uncover cross-document associations and reasoning pathways. To address these issues, we propose a pipeline that uses LLMs to construct a biomedical knowledge graph (BioStrataKG) from large-scale articles and builds a cross-document question-answering dataset (BioCDQA) to evaluate latent knowledge retrieval and multi-hop reasoning. We then introduce Integrated and Progressive Retrieval-Augmented Reasoning (IP-RAR) to enhance retrieval accuracy and knowledge reasoning. IP-RAR maximizes information recall through Integrated Reasoning-based Retrieval and refines knowledge via Progressive Reasoning-based Generation, using self-reflection to achieve deep thinking and precise contextual understanding. Experiments show that IP-RAR improves document retrieval F1 score by 20\% and answer generation accuracy by 25\% over existing methods. This framework helps doctors efficiently integrate treatment evidence for personalized medication plans and enables researchers to analyze advancements and research gaps, accelerating scientific discovery and decision-making.

[Arxiv](https://arxiv.org/abs/2503.23029)