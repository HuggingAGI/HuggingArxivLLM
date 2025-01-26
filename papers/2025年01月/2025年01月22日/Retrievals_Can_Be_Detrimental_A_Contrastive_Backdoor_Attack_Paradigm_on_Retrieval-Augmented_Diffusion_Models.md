# 检索可能有害：检索增强扩散模型的对比后门攻击范式

发布时间：2025年01月22日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术在扩散模型中的应用，并提出了一个名为BadRDM的多模态对比攻击方法，揭示了RDM易受后门攻击的漏洞。论文的核心内容围绕RAG技术的应用及其潜在的安全隐患展开，因此将其分类为RAG。` `人工智能` `信息安全`

> Retrievals Can Be Detrimental: A Contrastive Backdoor Attack Paradigm on Retrieval-Augmented Diffusion Models

# 摘要

> # 摘要
扩散模型（DMs）近期展现了强大的生成能力，但其训练往往依赖庞大的计算资源和大规模数据集。为解决这一问题，研究者们借助先进的检索增强生成（RAG）技术，提出了检索增强扩散模型（RDMs）。通过整合辅助数据库中的丰富知识，RAG不仅提升了扩散模型的生成和泛化能力，还大幅减少了模型参数。然而，尽管RAG取得了显著成功，它也可能带来新的安全隐患。本文通过提出一种名为BadRDM的多模态对比攻击方法，揭示了RDM易受后门攻击的漏洞。我们的框架充分考虑了RAG的特性，旨在通过操纵给定文本触发器的检索项来控制生成内容。具体而言，我们首先将少量图像插入检索数据库作为目标毒性替代品，随后采用对比学习的恶意变体将后门注入检索器，从而建立从触发器到毒性替代品的快捷路径。此外，我们通过基于熵的选择和生成增强策略进一步提升了攻击效果，这些策略能够生成更优的毒性替代品。在两个主流任务上的大量实验表明，BadRDM在保持模型正常功能的同时，实现了卓越的攻击效果。

> Diffusion models (DMs) have recently demonstrated remarkable generation capability. However, their training generally requires huge computational resources and large-scale datasets. To solve these, recent studies empower DMs with the advanced Retrieval-Augmented Generation (RAG) technique and propose retrieval-augmented diffusion models (RDMs). By incorporating rich knowledge from an auxiliary database, RAG enhances diffusion models' generation and generalization ability while significantly reducing model parameters. Despite the great success, RAG may introduce novel security issues that warrant further investigation. In this paper, we reveal that the RDM is susceptible to backdoor attacks by proposing a multimodal contrastive attack approach named BadRDM. Our framework fully considers RAG's characteristics and is devised to manipulate the retrieved items for given text triggers, thereby further controlling the generated contents. Specifically, we first insert a tiny portion of images into the retrieval database as target toxicity surrogates. Subsequently, a malicious variant of contrastive learning is adopted to inject backdoors into the retriever, which builds shortcuts from triggers to the toxicity surrogates. Furthermore, we enhance the attacks through novel entropy-based selection and generative augmentation strategies that can derive better toxicity surrogates. Extensive experiments on two mainstream tasks demonstrate the proposed BadRDM achieves outstanding attack effects while preserving the model's benign utility.

[Arxiv](https://arxiv.org/abs/2501.13340)