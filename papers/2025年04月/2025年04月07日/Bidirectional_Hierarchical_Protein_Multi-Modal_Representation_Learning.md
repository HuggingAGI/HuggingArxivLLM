# 双向性与层次化蛋白质多模态表示方法研究

发布时间：2025年04月07日

`LLM应用` `生物信息学`

> Bidirectional Hierarchical Protein Multi-Modal Representation Learning

# 摘要

> 蛋白质表示学习在生物领域具有重要意义。基于大规模蛋白质序列预训练的大型Transformer蛋白质语言模型（pLMs）在序列任务中表现优异，但缺乏结构信息。图神经网络（GNNs）擅长利用3D结构信息，但在标注结构数据有限的情况下效果受限。我们提出了一种多模态双向分层融合框架，通过注意力和门控机制，实现pLMs生成的序列表示与GNN提取的结构特征的有效交互，提升信息传递与增强。基于该框架，我们开发了局部双向分层融合（带门控）和全局双向分层融合（带多头自注意力）方法。在多种蛋白质相关任务的实验中，我们的方法在包括反应（酶/EC分类）、模型质量评估（MQA）、蛋白质-配体结合亲和力预测（LBA）、蛋白质-蛋白质结合位点预测（PPBS）以及B细胞表位预测（BCEs）等多种基准上，显著优于现有方法。我们的研究为多模态蛋白质表示学习设定了新的state-of-the-art水平，证明了双向分层融合在连接序列与结构模态中的有效性。


> Protein representation learning is critical for numerous biological tasks. Recently, large transformer-based protein language models (pLMs) pretrained on large scale protein sequences have demonstrated significant success in sequence-based tasks. However, pLMs lack structural information. Conversely, graph neural networks (GNNs) designed to leverage 3D structural information have shown promising generalization in protein-related prediction tasks, but their effectiveness is often constrained by the scarcity of labeled structural data. Recognizing that sequence and structural representations are complementary perspectives of the same protein entity, we propose a multimodal bidirectional hierarchical fusion framework to effectively merge these modalities. Our framework employs attention and gating mechanisms to enable effective interaction between pLMs-generated sequential representations and GNN-extracted structural features, improving information exchange and enhancement across layers of the neural network. Based on the framework, we further introduce local Bi-Hierarchical Fusion with gating and global Bi-Hierarchical Fusion with multihead self-attention approaches. Through extensive experiments on a diverse set of protein-related tasks, our method demonstrates consistent improvements over strong baselines and existing fusion techniques in a variety of protein representation learning benchmarks, including react (enzyme/EC classification), model quality assessment (MQA), protein-ligand binding affinity prediction (LBA), protein-protein binding site prediction (PPBS), and B cell epitopes prediction (BCEs). Our method establishes a new state-of-the-art for multimodal protein representation learning, emphasizing the efficacy of BIHIERARCHICAL FUSION in bridging sequence and structural modalities.

[Arxiv](https://arxiv.org/abs/2504.04770)