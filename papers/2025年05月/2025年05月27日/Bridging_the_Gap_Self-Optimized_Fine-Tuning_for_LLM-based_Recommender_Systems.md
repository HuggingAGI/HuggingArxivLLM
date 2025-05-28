# 填补空白：为基于大型语言模型的推荐系统实现自动优化微调

发布时间：2025年05月27日

`LLM应用

论文摘要讨论了大型语言模型（LLMs）在推荐系统（RS）中的应用，并提出了一种新的方法来提升其推荐能力。该方法结合了上下文学习和监督微调的优势，并引入了课程学习的概念，通过自蒸馏技术和自适应课程调度器来优化模型性能。研究结果表明，这种方法显著提高了推荐精度，属于LLM在实际应用中的优化和应用研究，因此归类为LLM应用。` `推荐系统` `电子商务`

> Bridging the Gap: Self-Optimized Fine-Tuning for LLM-based Recommender Systems

# 摘要

> 近年来，大型语言模型（LLMs）在推荐系统（RS）领域的应用研究取得了显著进展。目前，赋予LLMs推荐能力的两大主流策略分别是：1）“仅指导”策略，通过上下文学习充分挖掘并增强LLMs的语义理解和项目推荐能力；2）“仅微调”策略，借助监督微调（SFT）对LLMs进行优化，使其更好地适应真实推荐数据。然而，这两种策略均未能有效弥合LLMs知识空间与推荐任务之间的鸿沟，实际表现也未达预期。

为更好地赋能LLMs掌握推荐知识，我们融合上述两种策略的优势，创新性地提出了“指导+微调”方法——自适应优化微调（SOFT），并引入了课程学习的理念。该方法首先通过自蒸馏技术，从微调后的LLMs构建一个辅助的易于学习但具有实际意义的数据集；随后，借助自适应课程调度器，使LLMs逐步从简单数据（自蒸馏数据）学习过渡到更具挑战性的数据（真实RS数据）。大量实验结果表明，SOFT显著提升了基于LLMs方法的推荐精度，平均提升幅度达到37.59%。代码可通过https://anonymous.4open.science/r/Self-Optimized-Fine-Tuning-264E获取。


> Recent years have witnessed extensive exploration of Large Language Models (LLMs) on the field of Recommender Systems (RS). There are currently two commonly used strategies to enable LLMs to have recommendation capabilities: 1) The "Guidance-Only" strategy uses in-context learning to exploit and amplify the inherent semantic understanding and item recommendation capabilities of LLMs; 2) The "Tuning-Only" strategy uses supervised fine-tuning (SFT) to fine-tune LLMs with the aim of fitting them to real recommendation data. However, neither of these strategies can effectively bridge the gap between the knowledge space of LLMs and recommendation, and their performance do not meet our expectations.
  To better enable LLMs to learn recommendation knowledge, we combine the advantages of the above two strategies and proposed a novel "Guidance+Tuning" method called Self-Optimized Fine-Tuning (SOFT), which adopts the idea of curriculum learning. It first employs self-distillation to construct an auxiliary easy-to-learn but meaningful dataset from a fine-tuned LLM. Then it further utilizes a self-adaptive curriculum scheduler to enable LLMs to gradually learn from simpler data (self-distilled data) to more challenging data (real RS data). Extensive experiments demonstrate that SOFT significantly enhances the recommendation accuracy (37.59\% on average) of LLM-based methods. The code is available via https://anonymous.4open.science/r/Self-Optimized-Fine-Tuning-264E

[Arxiv](https://arxiv.org/abs/2505.20771)