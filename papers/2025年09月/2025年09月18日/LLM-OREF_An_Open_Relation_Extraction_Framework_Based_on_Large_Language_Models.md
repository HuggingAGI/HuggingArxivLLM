# LLM-OREF：基于大型语言模型的开放关系抽取框架

发布时间：2025年09月18日

`LLM应用` `基础理论`

> LLM-OREF: An Open Relation Extraction Framework Based on Large Language Models

# 摘要

> 开放关系抽取（OpenRE）旨在开发能泛化到训练时未见过的新关系的关系抽取（RE）模型。现有研究多将其视作聚类任务：先按实例相似度对测试实例聚类，再人工为每个簇分配新关系。但这种对人工标注的依赖严重限制了实用性。本文提出一种基于大型语言模型（LLMs）的OpenRE框架，无需人工干预，直接借助LLMs的语言理解与生成能力预测测试实例的新关系。该框架包含两个核心组件：（1）关系发现器（RD）——基于已知关系训练实例构建的	extit{演示样本}，预测测试实例的新关系；（2）关系预测器（RP）——基于实例组成的	extit{演示样本}，从n个候选关系中为测试实例挑选最可能的关系。为提升新关系预测能力，我们设计三阶段自校正推理策略：关系发现、关系去噪、关系预测。第一阶段，利用RD对所有测试实例进行新关系初步预测；随后通过交叉验证，借助RP从RD的预测结果中为每个新关系筛选高可靠性测试实例；第三阶段，基于这些可靠实例构建演示样本，再用RP重新预测所有测试实例的关系。在三个OpenRE数据集上的大量实验验证了我们框架的有效性，代码已发布于https://github.com/XMUDeepLIT/LLM-OREF.git。

> The goal of open relation extraction (OpenRE) is to develop an RE model that can generalize to new relations not encountered during training. Existing studies primarily formulate OpenRE as a clustering task. They first cluster all test instances based on the similarity between the instances, and then manually assign a new relation to each cluster. However, their reliance on human annotation limits their practicality. In this paper, we propose an OpenRE framework based on large language models (LLMs), which directly predicts new relations for test instances by leveraging their strong language understanding and generation abilities, without human intervention. Specifically, our framework consists of two core components: (1) a relation discoverer (RD), designed to predict new relations for test instances based on \textit{demonstrations} formed by training instances with known relations; and (2) a relation predictor (RP), used to select the most likely relation for a test instance from $n$ candidate relations, guided by \textit{demonstrations} composed of their instances. To enhance the ability of our framework to predict new relations, we design a self-correcting inference strategy composed of three stages: relation discovery, relation denoising, and relation prediction. In the first stage, we use RD to preliminarily predict new relations for all test instances. Next, we apply RP to select some high-reliability test instances for each new relation from the prediction results of RD through a cross-validation method. During the third stage, we employ RP to re-predict the relations of all test instances based on the demonstrations constructed from these reliable test instances. Extensive experiments on three OpenRE datasets demonstrate the effectiveness of our framework. We release our code at https://github.com/XMUDeepLIT/LLM-OREF.git.

[Arxiv](https://arxiv.org/abs/2509.15089)