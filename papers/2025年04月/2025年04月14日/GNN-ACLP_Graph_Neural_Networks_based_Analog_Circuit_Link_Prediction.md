# GNN-ACLP：基于图神经网络的模拟电路链接预测

发布时间：2025年04月14日

`LLM应用` `电子设计自动化` `电路设计`

> GNN-ACLP: Graph Neural Networks based Analog Circuit Link Prediction

# 摘要

> 电路链接预测是从不完整网表中识别缺失组件连接的关键技术，对自动化模拟电路设计至关重要。现有方法面临三大挑战：1）电路图中拓扑模式的利用不足导致预测精度受限；2）标注复杂引发的数据稀缺性限制了模型泛化能力；3）难以适应多种网表格式。我们提出了基于图神经网络（GNNs）的GNN-ACLP框架，通过三大创新突破这些难题。首先，我们引入了SEAL框架，在电路链接预测中实现了端口级精度。其次，我们开发了Netlist Babel Fish工具，通过检索增强生成（RAG）技术结合大型语言模型（LLM），显著提升了网表格式的兼容性。最后，我们构建了SpiceNetlist数据集，包含10种组件类别、775个标注电路。实验结果表明，相比现有方法，我们的框架在SpiceNetlist数据集上性能提升了15.05%，在Image2Net数据集上提升了12.01%。

> Circuit link prediction identifying missing component connections from incomplete netlists is crucial in automating analog circuit design. However, existing methods face three main challenges: 1) Insufficient use of topological patterns in circuit graphs reduces prediction accuracy; 2) Data scarcity due to the complexity of annotations hinders model generalization; 3) Limited adaptability to various netlist formats. We propose GNN-ACLP, a Graph Neural Networks (GNNs) based framework featuring three innovations to tackle these challenges. First, we introduce the SEAL (Subgraphs, Embeddings, and Attributes for Link Prediction) framework and achieve port-level accuracy in circuit link prediction. Second, we propose Netlist Babel Fish, a netlist format conversion tool leveraging retrieval-augmented generation (RAG) with large language model (LLM) to enhance the compatibility of netlist formats. Finally, we construct SpiceNetlist, a comprehensive dataset that contains 775 annotated circuits across 10 different classes of components. The experimental results demonstrate an improvement of 15.05% on the SpiceNetlist dataset and 12.01% on the Image2Net dataset over the existing approach.

[Arxiv](https://arxiv.org/abs/2504.10240)