# LLM-TabFlow：生成合成表格数据，同时保留跨列逻辑关系

发布时间：2025年03月03日

`LLM应用`

> LLM-TabFlow: Synthetic Tabular Data Generation with Inter-column Logical Relationship Preservation

# 摘要

> 合成表格数据在医疗、金融和供应链等领域有广泛应用，得益于其保护隐私和缓解数据稀缺性的潜力。然而，现有的生成模型在生成合成表格数据时，仍难以在保持列间逻辑关系的同时确保数据的现实性。为解决这些挑战，我们提出了LLM-TabFlow这一创新方法，该方法利用大型语言模型（LLM）推理来捕捉复杂的列间关系并压缩表格数据，同时采用基于分数的扩散模型在潜在空间中建模压缩数据的分布。此外，我们还引入了一个评估框架，这是文献中所缺乏的，以公平评估合成表格数据生成方法在实际场景中的性能。通过这一框架，我们在两个真实工业数据集上进行了大量实验，将LLM-TabFlow与其他五种基线方法进行对比，包括基于插值的SMOTE方法和其他最先进的生成模型。实验结果显示，LLM-TabFlow在所有基线方法中表现最优，在保持列间关系的同时，实现了数据保真性、实用性和隐私保护的最佳平衡。本研究首次明确关注合成表格数据生成中的列间关系 preservation，为开发更现实、更可靠的表格数据生成方法提供了新的见解。

> Synthetic tabular data have widespread applications in industrial domains such as healthcare, finance, and supply chains, owing to their potential to protect privacy and mitigate data scarcity. However, generating realistic synthetic tabular data while preserving inter-column logical relationships remains a significant challenge for the existing generative models. To address these challenges, we propose LLM-TabFlow, a novel approach that leverages Large Language Model (LLM) reasoning to capture complex inter-column relationships and compress tabular data, while using Score-based Diffusion to model the distribution of the compressed data in latent space. Additionally, we introduce an evaluation framework, which is absent in literature, to fairly assess the performance of synthetic tabular data generation methods in real-world contexts. Using this framework, we conduct extensive experiments on two real-world industrial datasets, evaluating LLM-TabFlow against other five baseline methods, including SMOTE (an interpolation-based approach) and other state-of-the-art generative models. Our results show that LLM-TabFlow outperforms all baselines, fully preserving inter-column relationships while achieving the best balance between data fidelity, utility, and privacy. This study is the first to explicitly address inter-column relationship preservation in synthetic tabular data generation, offering new insights for developing more realistic and reliable tabular data generation methods.

[Arxiv](https://arxiv.org/abs/2503.02161)