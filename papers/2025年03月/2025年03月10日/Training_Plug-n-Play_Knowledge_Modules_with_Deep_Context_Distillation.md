# 即插即用知识模块的深度上下文蒸馏训练方法

发布时间：2025年03月10日

`LLM应用

理由：这篇论文主要探讨了在大型语言模型中模块化知识存储和训练方法，属于LLM的应用和改进。虽然提到了RAG，但核心内容集中在知识模块的训练和应用上，因此归类为LLM应用。` `文档管理`

> Training Plug-n-Play Knowledge Modules with Deep Context Distillation

# 摘要

> 在（大型）语言模型预训练后，动态整合新信息或快速演进的信息仍具挑战性，尤其在数据量少或处理私人及专业文档时。上下文学习和检索增强生成（RAG）面临诸多限制，包括推理成本高昂，无法捕捉全局文档信息。本文提出了一种通过训练文档级知识模块（KMs）来模块化知识的方法。KMs是轻量级组件，作为参数高效的LoRA模块实现，旨在存储新文档信息，并可按需轻松集成到模型中。我们发现，将下一个词预测作为KMs的训练目标效果不佳。因此，我们提出深度上下文蒸馏：通过学习KMs参数，模拟将文档作为上下文输入的教师模型的隐藏状态和对数概率。我们的方法在两个数据集上优于标准的下一个词预测和预指令训练技术。最后，我们探讨了KMs与检索增强生成之间的协同效应。

> Dynamically integrating new or rapidly evolving information after (Large) Language Model pre-training remains challenging, particularly in low-data scenarios or when dealing with private and specialized documents. In-context learning and retrieval-augmented generation (RAG) face limitations, including their high inference costs and their inability to capture global document information. In this paper, we propose a way of modularizing knowledge by training document-level Knowledge Modules (KMs). KMs are lightweight components implemented as parameter-efficient LoRA modules, which are trained to store information about new documents and can be easily plugged into models on demand. We show that next-token prediction performs poorly as the training objective for KMs. We instead propose Deep Context Distillation: we learn KMs parameters such as to simulate hidden states and logits of a teacher that takes the document in context. Our method outperforms standard next-token prediction and pre-instruction training techniques, across two datasets. Finally, we highlight synergies between KMs and retrieval-augmented generation.

[Arxiv](https://arxiv.org/abs/2503.08727)