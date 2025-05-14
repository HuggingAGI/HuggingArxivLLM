# TrialMatchAI：一款AI驱动的端到端临床试验推荐系统，助力高效匹配患者与临床试验。

发布时间：2025年05月13日

`RAG` `临床试验` `精准医学`

> TrialMatchAI: An End-to-End AI-powered Clinical Trial Recommendation System to Streamline Patient-to-Trial Matching

# 摘要

> 患者招募一直是临床试验的主要瓶颈，亟需可扩展且自动化的解决方案。我们推出了TrialMatchAI，这是一个基于人工智能的推荐系统，通过处理结构化记录和非结构化医生笔记等异构临床数据，实现患者与临床试验的精准匹配。

TrialMatchAI基于检索增强生成框架中的微调开源大型语言模型（LLMs）构建，确保透明性和可重复性，同时保持轻量级部署，适合临床环境。该系统通过医疗领域的链式推理对生物医学实体进行标准化，并采用结合词汇和语义相似性的混合搜索策略检索相关试验，重新排序结果，并在准则层面进行资格评估。这一流程提供可解释的输出，具有可追溯的决策依据。

在现实世界验证中，92%的肿瘤患者在前20项推荐中至少有一个相关试验被检索到。通过对合成和真实临床数据集的评估，TrialMatchAI证实了其达到前沿水平的性能，专家评估证实其在准则层面的资格分类准确率超过90%，尤其在生物标志物驱动的匹配方面表现突出。

TrialMatchAI设计为模块化和隐私保护，支持Phenopackets标准化数据，支持安全的本地部署，并允许无缝替换LLM组件，以适应未来更先进的模型。通过提升效率和可解释性，以及提供轻量级、开源的部署方案，TrialMatchAI为精准医学中的AI驱动临床试验匹配提供了一个可扩展的解决方案。

> Patient recruitment remains a major bottleneck in clinical trials, calling for scalable and automated solutions. We present TrialMatchAI, an AI-powered recommendation system that automates patient-to-trial matching by processing heterogeneous clinical data, including structured records and unstructured physician notes. Built on fine-tuned, open-source large language models (LLMs) within a retrieval-augmented generation framework, TrialMatchAI ensures transparency and reproducibility and maintains a lightweight deployment footprint suitable for clinical environments. The system normalizes biomedical entities, retrieves relevant trials using a hybrid search strategy combining lexical and semantic similarity, re-ranks results, and performs criterion-level eligibility assessments using medical Chain-of-Thought reasoning. This pipeline delivers explainable outputs with traceable decision rationales. In real-world validation, 92 percent of oncology patients had at least one relevant trial retrieved within the top 20 recommendations. Evaluation across synthetic and real clinical datasets confirmed state-of-the-art performance, with expert assessment validating over 90 percent accuracy in criterion-level eligibility classification, particularly excelling in biomarker-driven matches. Designed for modularity and privacy, TrialMatchAI supports Phenopackets-standardized data, enables secure local deployment, and allows seamless replacement of LLM components as more advanced models emerge. By enhancing efficiency and interpretability and offering lightweight, open-source deployment, TrialMatchAI provides a scalable solution for AI-driven clinical trial matching in precision medicine.

[Arxiv](https://arxiv.org/abs/2505.08508)