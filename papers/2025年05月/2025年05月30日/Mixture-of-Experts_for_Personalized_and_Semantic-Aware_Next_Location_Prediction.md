# 个性化语义感知的下一个位置预测的混合专家模型

发布时间：2025年05月30日

`LLM应用` `地理信息系统`

> Mixture-of-Experts for Personalized and Semantic-Aware Next Location Prediction

# 摘要

> 预测下一个位置对理解人类移动模式至关重要。但现有方法存在两大局限：无法充分捕捉真实世界地点的复杂多维语义，也无法有效建模不同用户群体间的行为差异。为此，我们推出NextLocMoE，一个基于大型语言模型（LLMs）并采用双层专家混合（MoE）设计的创新框架。该架构包含两个关键模块：位置语义MoE在嵌入层面运作，擅长编码地点的丰富功能性语义；个性化MoE嵌入Transformer主干，能动态适应个体用户的独特移动模式。此外，我们还引入了历史感知路由机制，利用长期轨迹数据优化专家选择并确保预测稳定。在多个真实城市数据集上的实证研究表明，NextLocMoE在预测准确性、跨域泛化能力和可解释性方面均表现出色。

> Next location prediction plays a critical role in understanding human mobility patterns. However, existing approaches face two core limitations: (1) they fall short in capturing the complex, multi-functional semantics of real-world locations; and (2) they lack the capacity to model heterogeneous behavioral dynamics across diverse user groups. To tackle these challenges, we introduce NextLocMoE, a novel framework built upon large language models (LLMs) and structured around a dual-level Mixture-of-Experts (MoE) design. Our architecture comprises two specialized modules: a Location Semantics MoE that operates at the embedding level to encode rich functional semantics of locations, and a Personalized MoE embedded within the Transformer backbone to dynamically adapt to individual user mobility patterns. In addition, we incorporate a history-aware routing mechanism that leverages long-term trajectory data to enhance expert selection and ensure prediction stability. Empirical evaluations across several real-world urban datasets show that NextLocMoE achieves superior performance in terms of predictive accuracy, cross-domain generalization, and interpretability

[Arxiv](https://arxiv.org/abs/2505.24597)