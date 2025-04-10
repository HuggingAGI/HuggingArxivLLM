# S'MoRE：面向 LLM 微调的结构化残差专家混合模型

发布时间：2025年04月08日

`LLM理论` `人工智能`

> S'MoRE: Structural Mixture of Residual Experts for LLM Fine-tuning

# 摘要

> 微调预训练大型语言模型 (LLMs) 面临平衡参数效率与模型容量的双重挑战。现有方法如低秩适配 (LoRA) 效率高但灵活性不足，而专家混合 (MoE) 架构虽增强容量却增加了参数数量且利用率不高。为解决这些问题，我们提出了结构化残差专家混合 (S'MoRE)，一种将 LoRA 高效性与 MoE 灵活性完美结合的新型框架。具体而言，S'MoRE 通过分层低秩分解专家权重，生成多阶残差并在多层结构中互联。通过将输入令牌路由至残差子树，S'MoRE 仅需少量低秩矩阵即可模拟众多专家的能力。我们将 S'MoRE 残差的跨层传播建模为一种特殊的图神经网络 (GNN)，并证明在相同参数预算下，S'MoRE 以指数级提升了传统 MoE（或低秩适配混合）的结构灵活性。理论分析与实证结果均表明，S'MoRE 实现了更优的微调性能，为高效适应 LLM 提供了一种革命性方法。

> Fine-tuning pre-trained large language models (LLMs) presents a dual challenge of balancing parameter efficiency and model capacity. Existing methods like low-rank adaptations (LoRA) are efficient but lack flexibility, while Mixture-of-Experts (MoE) architectures enhance model capacity at the cost of more & under-utilized parameters. To address these limitations, we propose Structural Mixture of Residual Experts (S'MoRE), a novel framework that seamlessly integrates the efficiency of LoRA with the flexibility of MoE. Specifically, S'MoRE employs hierarchical low-rank decomposition of expert weights, yielding residuals of varying orders interconnected in a multi-layer structure. By routing input tokens through sub-trees of residuals, S'MoRE emulates the capacity of many experts by instantiating and assembling just a few low-rank matrices. We craft the inter-layer propagation of S'MoRE's residuals as a special type of Graph Neural Network (GNN), and prove that under similar parameter budget, S'MoRE improves "structural flexibility" of traditional MoE (or Mixture-of-LoRA) by exponential order. Comprehensive theoretical analysis and empirical results demonstrate that S'MoRE achieves superior fine-tuning performance, offering a transformative approach for efficient LLM adaptation.

[Arxiv](https://arxiv.org/abs/2504.06426)