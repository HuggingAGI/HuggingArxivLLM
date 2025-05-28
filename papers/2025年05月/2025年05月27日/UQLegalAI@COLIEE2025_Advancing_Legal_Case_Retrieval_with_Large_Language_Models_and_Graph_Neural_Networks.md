# UQLegalAI@COLIEE2025：结合大型语言模型与图神经网络，助力法律案例检索技术突破

发布时间：2025年05月27日

`LLM应用`

> UQLegalAI@COLIEE2025: Advancing Legal Case Retrieval with Large Language Models and Graph Neural Networks

# 摘要

> 法律案例检索在法律领域发挥着关键作用，它能够高效地识别相关案件，帮助法律专业人士和研究人员提出法律论点并做出明智的决策。为了提高检索的准确性，每年都会举办法律信息抽取与蕴含竞赛（COLIEE），提供最新的基准数据集用于评估。本文详细介绍了CaseLink，这是在COLIEE 2025任务1中排名第二的UQLegalAI团队所采用的方法。CaseLink模型利用归纳图学习和全局案例图来捕捉案件之间的内在联系，从而提升法律案例检索的准确性。具体而言，该模型采用了一种专门用于文本嵌入的大语言模型，将法律文本转化为嵌入表示，这些表示作为构建的案例图中节点的特征表示。此外，我们提出了一种新的对比目标，其中包含了对案例节点度的正则化，以利用案例引用关系中的信息进行模型优化。我们在方法中使用的主代码库基于CaseLink的开源仓库：https://github.com/yanran-tang/CaseLink.

> Legal case retrieval plays a pivotal role in the legal domain by facilitating the efficient identification of relevant cases, supporting legal professionals and researchers to propose legal arguments and make informed decision-making. To improve retrieval accuracy, the Competition on Legal Information Extraction and Entailment (COLIEE) is held annually, offering updated benchmark datasets for evaluation. This paper presents a detailed description of CaseLink, the method employed by UQLegalAI, the second highest team in Task 1 of COLIEE 2025. The CaseLink model utilises inductive graph learning and Global Case Graphs to capture the intrinsic case connectivity to improve the accuracy of legal case retrieval. Specifically, a large language model specialized in text embedding is employed to transform legal texts into embeddings, which serve as the feature representations of the nodes in the constructed case graph. A new contrastive objective, incorporating a regularization on the degree of case nodes, is proposed to leverage the information within the case reference relationship for model optimization. The main codebase used in our method is based on an open-sourced repo of CaseLink: https://github.com/yanran-tang/CaseLink.

[Arxiv](https://arxiv.org/abs/2505.20743)