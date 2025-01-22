# Poison-RAG: 推荐系统中检索增强生成的对抗性数据投毒攻击

发布时间：2025年01月20日

`RAG

理由：该论文主要研究的是针对基于检索增强生成（RAG）的推荐系统的对抗性数据投毒攻击，提出了Poison-RAG框架，并探讨了如何通过操纵项目元数据来影响推荐结果。论文的核心内容围绕RAG系统的安全性和防御机制展开，因此应归类为RAG。` `推荐系统` `数据安全`

> Poison-RAG: Adversarial Data Poisoning Attacks on Retrieval-Augmented Generation in Recommender Systems

# 摘要

> 本研究提出了Poison-RAG框架，专门针对基于检索增强生成（RAG）的推荐系统进行对抗性数据投毒攻击。该框架通过操纵项目元数据（如标签和描述）来影响推荐结果。我们利用大型语言模型（LLM）生成的项目元数据和OpenAI API提供的嵌入，研究了对抗性投毒攻击对提供方的影响，旨在推广长尾项目并降低热门项目的推荐。我们提出了两种攻击策略：局部修改策略，使用BERT嵌入为每个项目个性化标签；全局修改策略，在整个数据集中应用统一标签。在MovieLens数据集上的黑盒实验显示，局部策略将操纵效果提升了50%，而全局策略则可能进一步推高热门项目。结果表明，热门项目更容易受到攻击，而长尾项目则更难操纵。约70%的项目缺乏标签，带来了冷启动挑战；我们提出了数据增强和合成作为潜在的防御机制，以增强基于RAG的系统的韧性。研究结果强调了强大的元数据管理对保护推荐框架的重要性。代码和数据可在https://github.com/atenanaz/Poison-RAG获取。

> This study presents Poison-RAG, a framework for adversarial data poisoning attacks targeting retrieval-augmented generation (RAG)-based recommender systems. Poison-RAG manipulates item metadata, such as tags and descriptions, to influence recommendation outcomes. Using item metadata generated through a large language model (LLM) and embeddings derived via the OpenAI API, we explore the impact of adversarial poisoning attacks on provider-side, where attacks are designed to promote long-tail items and demote popular ones. Two attack strategies are proposed: local modifications, which personalize tags for each item using BERT embeddings, and global modifications, applying uniform tags across the dataset. Experiments conducted on the MovieLens dataset in a black-box setting reveal that local strategies improve manipulation effectiveness by up to 50\%, while global strategies risk boosting already popular items. Results indicate that popular items are more susceptible to attacks, whereas long-tail items are harder to manipulate. Approximately 70\% of items lack tags, presenting a cold-start challenge; data augmentation and synthesis are proposed as potential defense mechanisms to enhance RAG-based systems' resilience. The findings emphasize the need for robust metadata management to safeguard recommendation frameworks. Code and data are available at https://github.com/atenanaz/Poison-RAG.

[Arxiv](https://arxiv.org/abs/2501.11759)