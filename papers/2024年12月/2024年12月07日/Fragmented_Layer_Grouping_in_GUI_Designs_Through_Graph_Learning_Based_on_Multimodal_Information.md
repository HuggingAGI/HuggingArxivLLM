# 基于多模态信息的图学习在 GUI 设计中的碎片化层分组

发布时间：2024年12月07日

`其他` `GUI 设计`

> Fragmented Layer Grouping in GUI Designs Through Graph Learning Based on Multimodal Information

# 摘要

> 自动构建不同粒度的 GUI 组是实现 GUI 设计与实现任务自动化的关键智能步骤。具体来说，在工业 GUI 转代码的流程中，碎片化的层可能会降低生成代码的可读性和可维护性，而在设计原型中对语义一致的碎片化层进行分组则能缓解这一问题。本研究旨在依据设计原型中的多模态信息，提出一种基于图学习的方法来解决碎片化层分组难题。我们的图学习模块包含自注意力和图神经网络模块。以 GUI 层的多模态融合表示为输入，我们通过同时对 GUI 层进行分类和回归相应 GUI 组件的边界框，创新性地对碎片化层进行分组。在两个真实世界数据集上的实验表明，我们的模型性能达到了先进水平。此外，还开展了进一步的用户研究，以证实我们的方法能够助力智能下游工具生成更具可维护性和可读性的前端代码。

> Automatically constructing GUI groups of different granularities constitutes a critical intelligent step towards automating GUI design and implementation tasks. Specifically, in the industrial GUI-to-code process, fragmented layers may decrease the readability and maintainability of generated code, which can be alleviated by grouping semantically consistent fragmented layers in the design prototypes. This study aims to propose a graph-learning-based approach to tackle the fragmented layer grouping problem according to multi-modal information in design prototypes. Our graph learning module consists of self-attention and graph neural network modules. By taking the multimodal fused representation of GUI layers as input, we innovatively group fragmented layers by classifying GUI layers and regressing the bounding boxes of the corresponding GUI components simultaneously. Experiments on two real-world datasets demonstrate that our model achieves state-of-the-art performance. A further user study is also conducted to validate that our approach can assist an intelligent downstream tool in generating more maintainable and readable front-end code.

[Arxiv](https://arxiv.org/abs/2412.05555)