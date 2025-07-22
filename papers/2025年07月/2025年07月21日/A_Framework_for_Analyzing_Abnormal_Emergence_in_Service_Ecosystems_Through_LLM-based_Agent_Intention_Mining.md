# 基于LLM的智能体意图挖掘，研究服务生态系统中异常涌现的分析框架

发布时间：2025年07月21日

`Agent` `服务生态系统` `O2O服务系统`

> A Framework for Analyzing Abnormal Emergence in Service Ecosystems Through LLM-based Agent Intention Mining

# 摘要

> 随着服务计算、云计算和物联网的兴起，服务生态系统变得日益复杂。智能体之间的复杂交互使得异常涌现分析变得困难，因为传统的因果方法主要关注个体轨迹。大型语言模型通过链式推理为基于智能体的建模提供了新方法，以揭示智能体意图。然而，现有方法仍局限于微观和静态分析。本文提出了一种框架：基于多智能体意图的涌现分析（EAMI），它能够实现动态且可解释的涌现分析。EAMI首先采用双重视角的思维轨迹机制，其中Inspector Agent和Analysis Agent分别在有限理性和完美理性下提取智能体意图。然后，通过k-means聚类识别群体意图的相变点，接着使用意图时间涌现图进行动态分析。实验在复杂的线上到线下（O2O）服务系统和斯坦福AI Town实验中验证了EAMI的有效性，消融研究进一步确认了其有效性、泛化性和效率。该框架为服务生态系统中的异常涌现和因果分析提供了新范式。代码可在https://anonymous.4open.science/r/EAMI-B085获取。

> With the rise of service computing, cloud computing, and IoT, service ecosystems are becoming increasingly complex. The intricate interactions among intelligent agents make abnormal emergence analysis challenging, as traditional causal methods focus on individual trajectories. Large language models offer new possibilities for Agent-Based Modeling (ABM) through Chain-of-Thought (CoT) reasoning to reveal agent intentions. However, existing approaches remain limited to microscopic and static analysis. This paper introduces a framework: Emergence Analysis based on Multi-Agent Intention (EAMI), which enables dynamic and interpretable emergence analysis. EAMI first employs a dual-perspective thought track mechanism, where an Inspector Agent and an Analysis Agent extract agent intentions under bounded and perfect rationality. Then, k-means clustering identifies phase transition points in group intentions, followed by a Intention Temporal Emergence diagram for dynamic analysis. The experiments validate EAMI in complex online-to-offline (O2O) service system and the Stanford AI Town experiment, with ablation studies confirming its effectiveness, generalizability, and efficiency. This framework provides a novel paradigm for abnormal emergence and causal analysis in service ecosystems. The code is available at https://anonymous.4open.science/r/EAMI-B085.

[Arxiv](https://arxiv.org/abs/2507.15770)