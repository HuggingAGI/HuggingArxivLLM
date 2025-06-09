# 研究结合大型语言模型和图神经网络实现个性化金融产品推荐

发布时间：2025年06月06日

`LLM应用` `金融科技` `推荐系统`

> Research on Personalized Financial Product Recommendation by Integrating Large Language Models and Graph Neural Networks

# 摘要

> 金融科技的迅猛发展使个性化金融产品推荐变得日益重要。然而，传统的协同过滤和内容推荐模型往往难以捕捉用户的潜在偏好和复杂关系。我们提出了一种结合大型语言模型（LLMs）和图神经网络（GNNs）的创新框架。该框架利用预训练的LLM将文本数据（如用户评论）转化为丰富的特征向量，同时通过异构用户-产品图建模用户与产品之间的交互和社交关系。通过定制的消息传递机制，框架实现了文本信息与图信息的深度融合，从而在GNN中实现嵌入表示的联合优化。在公共和真实金融数据集上的实验结果表明，我们的模型在准确性、召回率和NDCG等关键指标上均显著超越了单独使用LLM或GNN的方法，且具有出色的可解释性。这项研究不仅为个性化金融推荐提供了新思路，也为更广泛的推荐任务中的跨模态融合开辟了新的研究方向。

> With the rapid growth of fintech, personalized financial product recommendations have become increasingly important. Traditional methods like collaborative filtering or content-based models often fail to capture users' latent preferences and complex relationships. We propose a hybrid framework integrating large language models (LLMs) and graph neural networks (GNNs). A pre-trained LLM encodes text data (e.g., user reviews) into rich feature vectors, while a heterogeneous user-product graph models interactions and social ties. Through a tailored message-passing mechanism, text and graph information are fused within the GNN to jointly optimize embeddings. Experiments on public and real-world financial datasets show our model outperforms standalone LLM or GNN in accuracy, recall, and NDCG, with strong interpretability. This work offers new insights for personalized financial recommendations and cross-modal fusion in broader recommendation tasks.

[Arxiv](https://arxiv.org/abs/2506.05873)