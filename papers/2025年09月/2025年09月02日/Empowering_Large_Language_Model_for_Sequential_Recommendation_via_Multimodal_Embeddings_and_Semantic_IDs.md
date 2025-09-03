# 借助多模态嵌入与语义ID赋能大型语言模型实现序列推荐

发布时间：2025年09月02日

`LLM应用` `零售与电商`

> Empowering Large Language Model for Sequential Recommendation via Multimodal Embeddings and Semantic IDs

# 摘要

> 序列推荐（SR）旨在根据用户的历史交互捕捉其动态兴趣和序列模式。近年来，大型语言模型（LLMs）凭借强大能力被广泛应用于序列推荐领域。然而，我们发现现有基于LLM的序列推荐方法存在两个关键挑战：一是整合预训练协同嵌入时出现的嵌入坍缩问题，二是使用语义ID时量化嵌入的灾难性遗忘问题。这些问题不仅降低了模型的可扩展性，还导致推荐性能欠佳。为此，我们基于Llama3-8B-instruct等LLM，提出了一种名为MME-SID的新型序列推荐框架，该框架整合多模态嵌入与量化嵌入，以缓解嵌入坍缩问题。此外，我们提出了多模态残差量化变分自编码器（MM-RQ-VAE），将最大均值差异作为重构损失，并结合对比学习进行模态对齐，该模型能分别有效保留模态内距离信息和捕捉模态间相关性。为进一步缓解灾难性遗忘，我们利用训练好的多模态代码嵌入对模型进行初始化。最后，我们采用LoRA以多模态频率感知融合方式对LLM进行高效微调。在三个公开数据集上的大量实验验证了MME-SID的优越性能，这得益于其缓解嵌入坍缩和灾难性遗忘的能力。相关实现代码和数据集已公开，便于复现：https://github.com/Applied-Machine-Learning-Lab/MME-SID。

> Sequential recommendation (SR) aims to capture users' dynamic interests and sequential patterns based on their historical interactions. Recently, the powerful capabilities of large language models (LLMs) have driven their adoption in SR. However, we identify two critical challenges in existing LLM-based SR methods: 1) embedding collapse when incorporating pre-trained collaborative embeddings and 2) catastrophic forgetting of quantized embeddings when utilizing semantic IDs. These issues dampen the model scalability and lead to suboptimal recommendation performance. Therefore, based on LLMs like Llama3-8B-instruct, we introduce a novel SR framework named MME-SID, which integrates multimodal embeddings and quantized embeddings to mitigate embedding collapse. Additionally, we propose a Multimodal Residual Quantized Variational Autoencoder (MM-RQ-VAE) with maximum mean discrepancy as the reconstruction loss and contrastive learning for alignment, which effectively preserve intra-modal distance information and capture inter-modal correlations, respectively. To further alleviate catastrophic forgetting, we initialize the model with the trained multimodal code embeddings. Finally, we fine-tune the LLM efficiently using LoRA in a multimodal frequency-aware fusion manner. Extensive experiments on three public datasets validate the superior performance of MME-SID thanks to its capability to mitigate embedding collapse and catastrophic forgetting. The implementation code and datasets are publicly available for reproduction: https://github.com/Applied-Machine-Learning-Lab/MME-SID.

[Arxiv](https://arxiv.org/abs/2509.02017)