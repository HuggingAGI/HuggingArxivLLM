# 超越图卷积：采用拓扑感知多层感知机的多模态推荐

发布时间：2024年12月16日

`其他` `推荐系统` `多模态数据`

> Beyond Graph Convolution: Multimodal Recommendation with Topology-aware MLPs

# 摘要

> 鉴于不同模态产生的大量辅助信息，多模态推荐系统愈发关键，因其能挖掘出超越用户-项目交互的更丰富语义信息。近期研究表明，借助图卷积网络（GCNs）明确构建多模态项目-项目关系，可显著提升推荐性能。然而，因 GCNs 固有的过平滑问题，现有模型仅能从表示能力有限的浅层 GCNs 中获益。在面对诸如多模态数据这类复杂高维模式时，此缺陷尤为突出，因其需要大容量模型来适应复杂的关联。为此，本文研究在构建多模态项目-项目关系时避开 GCNs。具体而言，我们提出了一种拓扑感知多层感知机（TMLP），用 MLP 替代 GCNs 来构建项目间的关系。TMLP 借助拓扑剪枝为 MLP 增效，以对项目-项目关系降噪，并通过内部（跨）模态学习整合高阶模态的相关性。在三个真实世界数据集上开展的大量实验，证实了 TMLP 相对于九个基线模型的优越性。我们还发现，摒弃 GCNs 中对节点连接敏感的内部消息传递，TMLP 在训练效率和相对于现有模型的鲁棒性方面均有显著提升。

> Given the large volume of side information from different modalities, multimodal recommender systems have become increasingly vital, as they exploit richer semantic information beyond user-item interactions. Recent works highlight that leveraging Graph Convolutional Networks (GCNs) to explicitly model multimodal item-item relations can significantly enhance recommendation performance. However, due to the inherent over-smoothing issue of GCNs, existing models benefit only from shallow GCNs with limited representation power. This drawback is especially pronounced when facing complex and high-dimensional patterns such as multimodal data, as it requires large-capacity models to accommodate complicated correlations. To this end, in this paper, we investigate bypassing GCNs when modeling multimodal item-item relationship. More specifically, we propose a Topology-aware Multi-Layer Perceptron (TMLP), which uses MLPs instead of GCNs to model the relationships between items. TMLP enhances MLPs with topological pruning to denoise item-item relations and intra (inter)-modality learning to integrate higher-order modality correlations. Extensive experiments on three real-world datasets verify TMLP's superiority over nine baselines. We also find that by discarding the internal message passing in GCNs, which is sensitive to node connections, TMLP achieves significant improvements in both training efficiency and robustness against existing models.

[Arxiv](https://arxiv.org/abs/2412.11747)