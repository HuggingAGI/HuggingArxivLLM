# 以恒应变：基于 LLM 的指令微调方法在非独立同分布网络流量分类中的应用

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在加密流量分类中的应用，提出了一种结合自监督指令微调范式的新型流量表示模型ETooL，并展示了其在分类任务中的有效性。因此，它属于LLM应用类别。` `网络安全性` `加密流量`

> Respond to Change with Constancy: Instruction-tuning with LLM for Non-I.I.D. Network Traffic Classification

# 摘要

> 加密流量分类在网络安全性中极具挑战性，因为需要从内容不可知的流量数据中提取健壮的特征。现有方法面临两个关键问题：(i) 依赖封闭世界的假设导致分布漂移，限制了其对现实世界中不断变化模式的适应能力；(ii) 对标记数据的依赖限制了其在数据稀缺或不可用情况下的应用。大型语言模型（LLMs）在提供广泛任务的通用解决方案方面展现出巨大潜力，并在多个专业领域取得了显著成功。然而，由于难以适应流量领域特有的要求，它们在流量分析中的有效性仍然受到限制。本文提出了一种名为Encrypted Traffic Out-of-Distribution Instruction Tuning with LLM (ETooL) 的新型流量表示模型，通过自监督指令微调范式将LLMs与流量结构知识相结合。该框架在文本信息与流量交互之间建立了联系。ETooL在监督和零样本流量分类任务中表现出更强大的分类性能和更卓越的泛化能力。值得注意的是，它在F1分数方面取得了显著提升：APP53 (I.I.D.) 提升至93.19%（6.62%），APP53 (O.O.D.) 提升至74.88%（18.17%），ISCX-Botnet (O.O.D.) 提升至95.03%（9.16%）。此外，我们构建了NETD，一个支持动态分布偏移的流量数据集，并利用它在不同分布条件下验证ETooL的有效性。此外，我们评估了通过ETooL的指令微调方法所获得的效率提升。

> Encrypted traffic classification is highly challenging in network security due to the need for extracting robust features from content-agnostic traffic data. Existing approaches face critical issues: (i) Distribution drift, caused by reliance on the closedworld assumption, limits adaptability to realworld, shifting patterns; (ii) Dependence on labeled data restricts applicability where such data is scarce or unavailable. Large language models (LLMs) have demonstrated remarkable potential in offering generalizable solutions across a wide range of tasks, achieving notable success in various specialized fields. However, their effectiveness in traffic analysis remains constrained by challenges in adapting to the unique requirements of the traffic domain. In this paper, we introduce a novel traffic representation model named Encrypted Traffic Out-of-Distribution Instruction Tuning with LLM (ETooL), which integrates LLMs with knowledge of traffic structures through a self-supervised instruction tuning paradigm. This framework establishes connections between textual information and traffic interactions. ETooL demonstrates more robust classification performance and superior generalization in both supervised and zero-shot traffic classification tasks. Notably, it achieves significant improvements in F1 scores: APP53 (I.I.D.) to 93.19%(6.62%) and 92.11%(4.19%), APP53 (O.O.D.) to 74.88%(18.17%) and 72.13%(15.15%), and ISCX-Botnet (O.O.D.) to 95.03%(9.16%) and 81.95%(12.08%). Additionally, we construct NETD, a traffic dataset designed to support dynamic distributional shifts, and use it to validate ETooL's effectiveness under varying distributional conditions. Furthermore, we evaluate the efficiency gains achieved through ETooL's instruction tuning approach.

[Arxiv](https://arxiv.org/abs/2505.20866)