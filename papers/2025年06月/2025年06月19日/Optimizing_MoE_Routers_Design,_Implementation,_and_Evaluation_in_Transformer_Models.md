# # 优化 MoE 路由器：Transformer 模型中的设计、实现与评估
混合专家（MoE）路由器的优化在 Transformer 模型中涉及设计、实现和评估三个关键环节。

发布时间：2025年06月19日

`LLM理论` `模型架构` `计算机科学`

> Optimizing MoE Routers: Design, Implementation, and Evaluation in Transformer Models

# 摘要

> 专家混合架构（MoE）提升了大型语言模型的扩展性，但其性能依赖于路由模块。本项目在Transformer模型中设计并实现了不同的路由架构，以克服这些限制。我们测试了六种独特的路由变体：线性、注意力、多层感知机（MLP）、混合、哈希以及我们新提出的MLP-Hadamard。我们使用BERT和Qwen1.5-MoE模型对这些路由进行了表征，评估了参数效率、推理延迟、路由熵和专家利用率模式。我们的评估结果显示了不同的权衡：线性路由提供速度优势，而MLP和注意力路由则具备更高的表达能力。MLP-Hadamard路由展现了在结构化稀疏路由方面的独特能力。我们成功地在复杂且量化的Qwen1.5-MoE模型中替换了默认路由并进行了微调。这项工作对MoE路由设计进行了比较分析，并为大规模模型的高效部署提供了性能优化的见解。

> Mixture of Experts (MoE) architectures increase large language model scalability, yet their performance depends on the router module that moves tokens to specialized experts. Bad routing can load imbalance and reduced accuracy. This project designed and implemented different router architectures within Transformer models to fix these limitations. We experimented with six distinct router variants Linear, Attention, Multi-Layer Perceptron (MLP), Hybrid, Hash, and our new MLP-Hadamard. We characterized these routers using BERT and the Qwen1.5-MoE model, looking at parameter efficiency, inference latency, routing entropy, and expert utilization patterns. Our evaluations showed distinct trade-offs: Linear routers offer speed, while MLP and Attention routers provide greater expressiveness. The MLP-Hadamard router shows a unique capability for structured, sparse routing. We successfully replaced and fine-tuned custom routers within the complex, quantized Qwen1.5-MoE model. This work provides a comparative analysis of MoE router designs and offers insights into optimizing their performance for efficient and effective large-scale model deployment.

[Arxiv](https://arxiv.org/abs/2506.16419)