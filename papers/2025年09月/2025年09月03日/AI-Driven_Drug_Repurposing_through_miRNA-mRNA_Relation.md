# 基于miRNA-mRNA关系的AI驱动药物重定位

发布时间：2025年09月03日

`LLM应用` `医疗健康`

> AI-Driven Drug Repurposing through miRNA-mRNA Relation

# 摘要

> miRNA-mRNA关系与多种生物学过程及疾病机制密切相关。在近期研究中，我们评估了大型语言模型（LLMs）从PubMed提取miRNA-mRNA关系的性能，其中PubMedBERT在miRNA-mRNA相互作用语料库（MMIC）上表现最佳，F1分数达0.783。本研究中，我们首先采用微调后的PubMedBERT模型，从PubMed中提取与慢性阻塞性肺疾病（COPD）、阿尔茨海默病（AD）、中风、2型糖尿病（T2DM）、慢性肝病及癌症相关的miRNA-mRNA关系。接着，通过文献挖掘工具KinderMiner获取miRNA-药物关系。随后，我们构建了三个相互作用网络：1）疾病中心网络、2）药物中心网络和3）miRNA中心网络，这些网络包含3497个节点和16417条边，以有向图形式呈现，旨在捕捉复杂的生物学关系。最后，利用MIMIC IV对药物进行验证。通过从PubMed提取的595个miRNA-药物关系，我们的综合方法发现了所研究疾病的已知候选药物和潜在新候选药物。据我们所知，这是首次系统提取并可视化miRNA、mRNA、药物与疾病这四种生物医学实体间关系的研究。

> miRNA mRNA relations are closely linked to several biological processes and disease mechanisms In a recent study we tested the performance of large language models LLMs on extracting miRNA mRNA relations from PubMed PubMedBERT achieved the best performance of 0.783 F1 score for miRNA mRNA Interaction Corpus MMIC Here we first applied the finetuned PubMedBERT model to extract miRNA mRNA relations from PubMed for chronic obstructive pulmonary disease COPD Alzheimers disease AD stroke type 2 diabetes mellitus T2DM chronic liver disease and cancer Next we retrieved miRNA drug relations using KinderMiner a literature mining tool for relation extraction Then we constructed three interaction networks 1 disease centric network 2 drug centric network and 3 miRNA centric network comprising 3497 nodes and 16417 edges organized as a directed graph to capture complex biological relationships Finally we validated the drugs using MIMIC IV Our integrative approach revealed both established and novel candidate drugs for diseases under study through 595 miRNA drug relations extracted from PubMed To the best of our knowledge this is the first study to systematically extract and visualize relationships among four distinct biomedical entities miRNA mRNA drug and disease

[Arxiv](https://arxiv.org/abs/2509.03336)