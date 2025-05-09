# MatMMFuse：用于材料属性预测的多模态融合模型

发布时间：2025年04月30日

`LLM应用` `材料科学`

> MatMMFuse: Multi-Modal Fusion model for Material Property Prediction

# 摘要

> 近年来，基于图结构编码的晶体结构在高通量材料属性预测方面取得了显著成功。然而，单一模态模型的使用限制了我们通过结合不同表示方法来充分利用增强特征空间的优势。具体而言，预训练的大型语言模型（LLMs）能够编码大量知识，这对模型训练非常有益。此外，图编码器能够学习局部特征，而文本编码器则能够学习全局信息，例如空间群和晶体对称性。在本研究中，我们提出了Material Multi-Modal Fusion（MatMMFuse），这是一种基于多头注意力机制的融合模型，结合了来自Crystal Graph Convolution Network（CGCNN）的结构感知嵌入和来自SciBERT模型的文本嵌入。我们在端到端框架中使用材料基因组项目数据集（Materials Project Dataset）对模型进行训练。实验结果表明，与传统的CGCNN和SciBERT模型相比，我们提出的模型在四个关键属性——形成能、带隙、能量高于凸包以及费米能级——上均表现出性能提升。具体而言，与传统CGCNN模型相比，我们在预测每原子形成能方面观察到40%的提升，与SciBERT模型相比则提升了68%。更重要的是，我们在精心整理的小型数据集（包括钙钛矿、硫族化合物以及Jarvis数据集）上展示了训练模型的零样本性能。结果表明，与单独使用传统CGCNN和SciBERT模型相比，我们的模型在零样本学习方面表现更优。这使得研究人员能够将该模型部署到工业应用中，特别是在训练数据收集成本高昂的场景中。

> The recent progress of using graph based encoding of crystal structures for high throughput material property prediction has been quite successful. However, using a single modality model prevents us from exploiting the advantages of an enhanced features space by combining different representations. Specifically, pre-trained Large language models(LLMs) can encode a large amount of knowledge which is beneficial for training of models. Moreover, the graph encoder is able to learn the local features while the text encoder is able to learn global information such as space group and crystal symmetry. In this work, we propose Material Multi-Modal Fusion(MatMMFuse), a fusion based model which uses a multi-head attention mechanism for the combination of structure aware embedding from the Crystal Graph Convolution Network (CGCNN) and text embeddings from the SciBERT model. We train our model in an end-to-end framework using data from the Materials Project Dataset. We show that our proposed model shows an improvement compared to the vanilla CGCNN and SciBERT model for all four key properties: formation energy, band gap, energy above hull and fermi energy. Specifically, we observe an improvement of 40% compared to the vanilla CGCNN model and 68% compared to the SciBERT model for predicting the formation energy per atom. Importantly, we demonstrate the zero shot performance of the trained model on small curated datasets of Perovskites, Chalcogenides and the Jarvis Dataset. The results show that the proposed model exhibits better zero shot performance than the individual plain vanilla CGCNN and SciBERT model. This enables researchers to deploy the model for specialized industrial applications where collection of training data is prohibitively expensive.

[Arxiv](https://arxiv.org/abs/2505.04634)