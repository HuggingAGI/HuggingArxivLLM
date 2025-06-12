# Llama-Affinity：结合抗体序列的Llama3主干架构预测模型

发布时间：2025年05月17日

`LLM应用

论文摘要：抗体介导的免疫反应是身体对抗病原体、病毒和外来入侵者的基石。抗体通过特异性结合并中和抗原，对维持免疫功能至关重要。近年来，生物工程的突破大大加速了治疗性抗体的研发进程。这些抗体药物在治疗癌症、SARS-CoV-2、自身免疫性疾病和传染病方面表现尤为突出。传统实验方法在测量抗体亲和力方面耗时且成本高昂。人工智能的出现为药物研发带来了革命性变化，特别是机器学习的最新进展，尤其是利用大型语言模型（LLMs）对抗体进行表征，为AI辅助设计和亲和力预测提供了全新途径。本文介绍了一种基于开源Llama 3框架的先进抗体-抗原结合亲和力预测模型（LlamaAffinity），该模型利用来自观察抗体空间（OAS）数据库的抗体序列数据。与现有最先进的方法（AntiFormer、AntiBERTa、AntiBERTy）相比，本模型在多个评估指标上均表现出显著优势。具体而言，模型实现了0.9640的准确率，0.9643的F1分数，0.9702的精确率，0.9586的召回率，以及0.9936的ROC曲线下面积。此外，本方法在计算效率方面也表现出色，五次累计训练时间平均仅为0.46小时，远低于以往研究。

LLM应用` `人工智能`

> Llama-Affinity: A Predictive Antibody Antigen Binding Model Integrating Antibody Sequences with Llama3 Backbone Architecture

# 摘要

> 抗体介导的免疫反应是身体对抗病原体、病毒和外来入侵者的基石。抗体通过特异性结合并中和抗原，对维持免疫功能至关重要。近年来，生物工程的突破大大加速了治疗性抗体的研发进程。这些抗体药物在治疗癌症、SARS-CoV-2、自身免疫性疾病和传染病方面表现尤为突出。传统实验方法在测量抗体亲和力方面耗时且成本高昂。人工智能的出现为药物研发带来了革命性变化，特别是机器学习的最新进展，尤其是利用大型语言模型（LLMs）对抗体进行表征，为AI辅助设计和亲和力预测提供了全新途径。本文介绍了一种基于开源Llama 3框架的先进抗体-抗原结合亲和力预测模型（LlamaAffinity），该模型利用来自观察抗体空间（OAS）数据库的抗体序列数据。与现有最先进的方法（AntiFormer、AntiBERTa、AntiBERTy）相比，本模型在多个评估指标上均表现出显著优势。具体而言，模型实现了0.9640的准确率，0.9643的F1分数，0.9702的精确率，0.9586的召回率，以及0.9936的ROC曲线下面积。此外，本方法在计算效率方面也表现出色，五次累计训练时间平均仅为0.46小时，远低于以往研究。

> Antibody-facilitated immune responses are central to the body's defense against pathogens, viruses, and other foreign invaders. The ability of antibodies to specifically bind and neutralize antigens is vital for maintaining immunity. Over the past few decades, bioengineering advancements have significantly accelerated therapeutic antibody development. These antibody-derived drugs have shown remarkable efficacy, particularly in treating cancer, SARS-CoV-2, autoimmune disorders, and infectious diseases. Traditionally, experimental methods for affinity measurement have been time-consuming and expensive. With the advent of artificial intelligence, in silico medicine has been revolutionized; recent developments in machine learning, particularly the use of large language models (LLMs) for representing antibodies, have opened up new avenues for AI-based design and improved affinity prediction. Herein, we present an advanced antibody-antigen binding affinity prediction model (LlamaAffinity), leveraging an open-source Llama 3 backbone and antibody sequence data sourced from the Observed Antibody Space (OAS) database. The proposed approach shows significant improvement over existing state-of-the-art (SOTA) methods (AntiFormer, AntiBERTa, AntiBERTy) across multiple evaluation metrics. Specifically, the model achieved an accuracy of 0.9640, an F1-score of 0.9643, a precision of 0.9702, a recall of 0.9586, and an AUC-ROC of 0.9936. Moreover, this strategy unveiled higher computational efficiency, with a five-fold average cumulative training time of only 0.46 hours, significantly lower than in previous studies.

[Arxiv](https://arxiv.org/abs/2506.09052)