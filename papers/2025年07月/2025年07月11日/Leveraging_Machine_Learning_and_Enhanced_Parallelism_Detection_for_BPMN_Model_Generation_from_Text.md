# 基于机器学习与增强并行检测的文本到BPMN模型生成方法

发布时间：2025年07月11日

`LLM应用` `流程管理` `业务流程建模`

> Leveraging Machine Learning and Enhanced Parallelism Detection for BPMN Model Generation from Text

# 摘要

> 高效的规划、资源管理和持续运营离不开将文本流程文档转化为正式的业务流程模型与符号（BPMN）模型。然而，这一转换过程依然耗时且成本高昂。现有的方法，无论是基于规则的还是机器学习的，仍然难以应对多样的写作风格，常常无法识别流程描述中的并行结构。

    本文提出了一种从文本中提取BPMN模型的自动化流程，充分利用机器学习和大型语言模型的优势。这项研究的关键贡献在于引入了一个全新的标注数据集，显著提升了训练效果。具体来说，我们在PET数据集的基础上新增了15份标注文档，其中包含了32个并行网关用于模型训练。这一关键特征在现有数据集中往往被忽视。新增的数据使模型能够更好地捕捉并行结构，这是流程描述中常见但复杂的要素。我们的方法在重建准确度方面表现出色，为组织加速BPMN模型创建提供了有力的基石。
    

> Efficient planning, resource management, and consistent operations often rely on converting textual process documents into formal Business Process Model and Notation (BPMN) models. However, this conversion process remains time-intensive and costly. Existing approaches, whether rule-based or machine-learning-based, still struggle with writing styles and often fail to identify parallel structures in process descriptions.
  This paper introduces an automated pipeline for extracting BPMN models from text, leveraging the use of machine learning and large language models. A key contribution of this work is the introduction of a newly annotated dataset, which significantly enhances the training process. Specifically, we augment the PET dataset with 15 newly annotated documents containing 32 parallel gateways for model training, a critical feature often overlooked in existing datasets. This addition enables models to better capture parallel structures, a common but complex aspect of process descriptions. The proposed approach demonstrates adequate performance in terms of reconstruction accuracy, offering a promising foundation for organizations to accelerate BPMN model creation.

[Arxiv](https://arxiv.org/abs/2507.08362)