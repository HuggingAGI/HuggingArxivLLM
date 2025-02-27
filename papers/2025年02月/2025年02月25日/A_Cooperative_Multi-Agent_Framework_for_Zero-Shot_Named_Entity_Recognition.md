# # 标题  
用于零样本命名实体识别的协作多智能体框架

发布时间：2025年02月25日

`LLM应用

摘要中提到论文提出了一种新的框架CMAS，利用多个智能体协作解决零样本NER问题，主要应用了大型语言模型。因此，这篇论文属于LLM应用类别。` `机器学习`

> A Cooperative Multi-Agent Framework for Zero-Shot Named Entity Recognition

# 摘要

> 零样本命名实体识别（NER）的目标是从未标注的文本语料库中开发实体识别系统。这一任务由于人工干预极少而面临巨大挑战。最近的研究通过设计专门的提示模板，将大型语言模型（LLMs）应用于零样本NER，同时通过整合自我标注的示例来提升模型的自我学习能力。然而，现有方法仍面临两大挑战：其一，忽略了实体上下文间的关联性，导致类型预测错误或实体遗漏；其二，通过浅层相似度策略检索的示例缺乏辨别，严重误导LLMs在推理过程中的判断。

本文提出了一种名为合作多智能体系统（CMAS）的全新框架，旨在通过多个智能体的集体智慧解决上述问题，实现零样本NER。CMAS包含四个主要智能体：自我标注器、类型相关特征提取器、示例判别器和整体预测器。为了明确捕捉实体上下文间的关联性，CMAS将NER重新定义为两个子任务：识别命名实体及其在目标句子中的类型相关特征。为实现对示例的可控利用，CMAS引入了示例判别器，整合自我反思机制，自动评估目标句子的有用性得分。实验结果表明，CMAS在六个基准测试中显著提升了零样本NER的性能，涵盖特定领域和通用领域场景。此外，CMAS在少量样本设置和多种LLM架构下均表现出色。

> Zero-shot named entity recognition (NER) aims to develop entity recognition systems from unannotated text corpora. This task presents substantial challenges due to minimal human intervention. Recent work has adapted large language models (LLMs) for zero-shot NER by crafting specialized prompt templates. It advances model self-learning abilities by incorporating self-annotated demonstrations. However, two important challenges persist: (i) Correlations between contexts surrounding entities are overlooked, leading to wrong type predictions or entity omissions. (ii) The indiscriminate use of task demonstrations, retrieved through shallow similarity-based strategies, severely misleads LLMs during inference.
  In this paper, we introduce the cooperative multi-agent system (CMAS), a novel framework for zero-shot NER that uses the collective intelligence of multiple agents to address the challenges outlined above. CMAS has four main agents: (i) a self-annotator, (ii) a type-related feature (TRF) extractor, (iii) a demonstration discriminator, and (iv) an overall predictor. To explicitly capture correlations between contexts surrounding entities, CMAS reformulates NER into two subtasks: recognizing named entities and identifying entity type-related features within the target sentence. To enable controllable utilization of demonstrations, a demonstration discriminator is established to incorporate the self-reflection mechanism, automatically evaluating helpfulness scores for the target sentence. Experimental results show that CMAS significantly improves zero-shot NER performance across six benchmarks, including both domain-specific and general-domain scenarios. Furthermore, CMAS demonstrates its effectiveness in few-shot settings and with various LLM backbones.

[Arxiv](https://arxiv.org/abs/2502.18702)