# 分布式特化：大型语言模型中的稀有标记神经元

发布时间：2025年09月25日

`LLM理论` `基础理论`

> Distributed Specialization: Rare-Token Neurons in Large Language Models

# 摘要

> 尽管稀有标记在专业领域至关重要，但大型语言模型（LLMs）在表示和生成这类标记时仍面临挑战。我们探究LLMs是通过离散的模块化架构，还是通过分布式参数级分化来形成内部专门化机制。通过对多个模型家族最后一层MLP神经元的系统分析，我们发现稀有标记处理通过	extit{分布式专门化}实现：即功能协同但空间分布的子网络，这些子网络呈现出三个独特的组织原则。首先，我们发现了一种可重复的三区域影响层级结构，由高影响力的平台神经元（又称稀有标记神经元）、幂律衰减神经元和最小贡献神经元组成，而这一结构在常见标记处理中并不存在。其次，平台神经元呈现出协同激活模式（有效维度降低），且始终保持空间分布，而非形成离散簇。第三，这些专门化机制可通过标准注意力通路直接调用，无需专用的路由电路。训练动态显示，功能专门化通过参数分化逐步形成，专门化神经元的权重相关谱呈现出越来越明显的重尾特性，这与重尾自正则化特征相符。我们的研究证实，LLMs处理稀有标记时依靠的是共享架构内的分布式协同，而非专家混合式的模块化结构。这些结果为可解释模型编辑、计算效率优化，以及理解Transformer网络中涌现的功能组织提供了重要启示。

> Large language models (LLMs) struggle with representing and generating rare tokens despite their importance in specialized domains. We investigate whether LLMs develop internal specialization mechanisms through discrete modular architectures or distributed parameter-level differentiation. Through systematic analysis of final-layer MLP neurons across multiple model families, we discover that rare-token processing emerges via \textit{distributed specialization}: functionally coordinated but spatially distributed subnetworks that exhibit three distinct organizational principles. First, we identify a reproducible three-regime influence hierarchy comprising highly influential plateau neurons(also termed as rare-token neurons), power-law decay neurons, and minimally contributing neurons, which is absent in common-token processing. Second, plateau neurons demonstrate coordinated activation patterns (reduced effective dimensionality) while remaining spatially distributed rather than forming discrete clusters. Third, these specialized mechanisms are universally accessible through standard attention pathways without requiring dedicated routing circuits. Training dynamics reveal that functional specialization emerges gradually through parameter differentiation, with specialized neurons developing increasingly heavy-tailed weight correlation spectra consistent with Heavy-Tailed Self-Regularization signatures. Our findings establish that LLMs process rare-tokens through distributed coordination within shared architectures rather than mixture-of-experts-style modularity. These results provide insights for interpretable model editing, computational efficiency optimization, and understanding emergent functional organization in transformer networks.

[Arxiv](https://arxiv.org/abs/2509.21163)