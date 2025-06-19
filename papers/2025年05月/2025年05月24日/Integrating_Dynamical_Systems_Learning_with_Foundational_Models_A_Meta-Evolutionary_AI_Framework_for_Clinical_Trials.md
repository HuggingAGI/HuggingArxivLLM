# 融合动力系统学习与基础模型：一种在临床试验中的元进化AI框架

发布时间：2025年05月24日

`其他` `临床试验`

> Integrating Dynamical Systems Learning with Foundational Models: A Meta-Evolutionary AI Framework for Clinical Trials

# 摘要

> 人工智能（AI）已经演变为一个由各种“专业物种”组成的生态系统，各有所长。我们聚焦其中两种代表：DeepSeek-V3，一个拥有6710亿参数的专家混合模型（Mixture of Experts）大型语言模型（LLM），展现了规模驱动的通用性；以及NetraAI，一个专为小规模临床试验数据集设计的动力系统框架，致力于稳定性和可解释性。我们从理论层面解析了NetraAI的根基，融合了压缩映射、信息几何和进化算法，用于识别具有预测性的患者群体。特征被嵌入到度量空间中，并通过迭代压缩向稳定吸引子收敛，从而定义潜在的子群体。伪时间嵌入和长程记忆功能支持对高阶特征交互的探索，而内部进化循环则选择紧凑、可解释的2-4变量组合（“人格”）。为了引导发现过程，我们引入了一个LLM策略师作为元进化层，它观察“人格”输出、优先考虑有前景的变量、注入领域知识并评估稳健性。这种双层架构模仿了人类的科学研究过程：NetraAI扮演实验者的角色，而LLM则扮演理论家的角色，形成一个自我改进的循环。在案例研究（精神分裂症、抑郁症、胰腺癌）中，NetraAI识别出了小规模但效应显著的亚群体，仅使用少量特征就将弱基线模型（AUC ~0.50-0.68）转变为近乎完美的分类器。我们将NetraAI定位在动力系统、信息几何和进化学习的交汇处，与LeCun的联合嵌入预测架构（JEPA）等新兴的概念级推理范式相契合。通过优先考虑可靠且可解释的知识，NetraAI为临床发现提供了一个新型的自适应、自我反思的AI系统。

> Artificial intelligence (AI) has evolved into an ecosystem of specialized "species," each with unique strengths. We analyze two: DeepSeek-V3, a 671-billion-parameter Mixture of Experts large language model (LLM) exemplifying scale-driven generality, and NetraAI, a dynamical system-based framework engineered for stability and interpretability on small clinical trial datasets. We formalize NetraAI's foundations, combining contraction mappings, information geometry, and evolutionary algorithms to identify predictive patient cohorts. Features are embedded in a metric space and iteratively contracted toward stable attractors that define latent subgroups. A pseudo-temporal embedding and long-range memory enable exploration of higher-order feature interactions, while an internal evolutionary loop selects compact, explainable 2-4-variable bundles ("Personas").
  To guide discovery, we introduce an LLM Strategist as a meta-evolutionary layer that observes Persona outputs, prioritizes promising variables, injects domain knowledge, and assesses robustness. This two-tier architecture mirrors the human scientific process: NetraAI as experimentalist, the LLM as theorist, forming a self-improving loop.
  In case studies (schizophrenia, depression, pancreatic cancer), NetraAI uncovered small, high-effect-size subpopulations that transformed weak baseline models (AUC ~0.50-0.68) into near-perfect classifiers using only a few features. We position NetraAI at the intersection of dynamical systems, information geometry, and evolutionary learning, aligned with emerging concept-level reasoning paradigms such as LeCun's Joint Embedding Predictive Architecture (JEPA). By prioritizing reliable, explainable knowledge, NetraAI offers a new generation of adaptive, self-reflective AI to accelerate clinical discovery.

[Arxiv](https://arxiv.org/abs/2506.14782)