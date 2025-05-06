# MoxE：基于熵感知路由的xLSTM专家混合模型，实现高效语言建模

发布时间：2025年05月01日

`LLM理论` `人工智能`

> MoxE: Mixture of xLSTM Experts with Entropy-Aware Routing for Efficient Language Modeling

# 摘要

> 本文提出了一种名为MoxE的全新架构，通过巧妙结合扩展长短期记忆（xLSTM）与专家混合（MoE）框架，有效解决了大型语言模型（LLMs）在扩展性和效率方面的关键挑战。该方法不仅充分利用了xLSTM的创新性内存结构，还通过MoE框架引入稀疏性，大幅降低了计算开销。我们的核心创新在于提出了一种基于熵的动态路由机制，能够智能地将令牌分配给专门的专家，从而实现资源的高效和均衡利用。这种熵感知设计使得架构能够灵活应对罕见和常见令牌的处理需求，其中mLSTM块在处理罕见令牌时表现尤为出色。为了进一步提升模型的泛化能力，我们引入了一系列辅助损失函数，包括基于熵和按组平衡的损失，从而确保了模型的稳健性能和高效训练。通过严谨的理论分析和实证评估，我们证明了MoxE在效率和有效性方面相较于现有方法取得了显著提升，标志着在可扩展LLM架构领域的一项重要突破。

> This paper introduces MoxE, a novel architecture that synergistically combines the Extended Long Short-Term Memory (xLSTM) with the Mixture of Experts (MoE) framework to address critical scalability and efficiency challenges in large language models (LLMs). The proposed method effectively leverages xLSTM's innovative memory structures while strategically introducing sparsity through MoE to substantially reduce computational overhead. At the heart of our approach is a novel entropy-based routing mechanism, designed to dynamically route tokens to specialized experts, thereby ensuring efficient and balanced resource utilization. This entropy awareness enables the architecture to effectively manage both rare and common tokens, with mLSTM blocks being favored to handle rare tokens. To further enhance generalization, we introduce a suite of auxiliary losses, including entropy-based and group-wise balancing losses, ensuring robust performance and efficient training. Theoretical analysis and empirical evaluations rigorously demonstrate that MoxE achieves significant efficiency gains and enhanced effectiveness compared to existing approaches, marking a notable advancement in scalable LLM architectures.

[Arxiv](https://arxiv.org/abs/2505.01459)