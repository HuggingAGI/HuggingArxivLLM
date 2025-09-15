# 基于LLM和GCN框架的电商平台在线支付交易欺诈检测与风险评估

发布时间：2025年09月11日

`LLM应用` `金融科技` `零售与电商`

> Fraud detection and risk assessment of online payment transactions on e-commerce platforms based on LLM and GCN frameworks

# 摘要

> 随着电子商务的迅猛发展，在线支付欺诈日趋复杂，严重威胁着金融安全与消费者信任。传统检测方法往往难以捕捉交易数据中蕴含的复杂关系结构。本研究提出一种新颖的欺诈检测框架，将大型语言模型（LLM）与图卷积网络（GCN）相结合，有效识别电子商务在线支付交易中的欺诈行为。研究从亚马逊等主流平台收集了14天内的284万笔交易数据，涉及约2000名美国消费者与30家商家。由于欺诈样本不足6000个，该数据集呈现高度不平衡特征。研究将消费者与商家建模为节点、交易建模为边，构建异构图，并在图上应用GCN学习复杂行为模式。通过GPT-4o与Tabformer提取的语义特征与结构特征相融合，进一步提升了检测性能。实验结果显示，该模型准确率达0.98，能有效平衡欺诈检测的精确率与灵敏度。该框架为保障在线支付环境提供了可扩展的实时解决方案，也为图基深度学习在金融欺诈防范中的应用指明了可行方向。

> With the rapid growth of e-commerce, online payment fraud has become increasingly complex, posing serious threats to financial security and consumer trust. Traditional detection methods often struggle to capture the intricate relational structures inherent in transactional data. This study presents a novel fraud detection framework that combines Large Language Models (LLM) with Graph Convolutional Networks (GCN) to effectively identify fraudulent activities in e-commerce online payment transactions. A dataset of 2,840,000 transactions was collected over 14 days from major platforms such as Amazon, involving approximately 2,000 U.S.-based consumers and 30 merchants. With fewer than 6000 fraudulent instances, the dataset represents a highly imbalanced scenario. Consumers and merchants were modeled as nodes and transactions as edges to form a heterogeneous graph, upon which a GCN was applied to learn complex behavioral patterns. Semantic features extracted via GPT-4o and Tabformer were integrated with structural features to enhance detection performance. Experimental results demonstrate that the proposed model achieves an accuracy of 0.98, effectively balancing precision and sensitivity in fraud detection. This framework offers a scalable and real-time solution for securing online payment environments and provides a promising direction for applying graph-based deep learning in financial fraud prevention.

[Arxiv](https://arxiv.org/abs/2509.09928)