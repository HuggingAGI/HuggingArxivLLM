# 可扩展且可解释的上下文多臂老虎机：文献综述与零售优惠原型设计

发布时间：2025年05月22日

`LLM应用` `电子商务`

> Scalable and Interpretable Contextual Bandits: A Literature Review and Retail Offer Prototype

# 摘要

> 本文对上下文多臂老虎机（CMAB）方法进行了简洁综述，并提出一个实验框架，用于解决快速变化优惠带来的挑战，实现可扩展、可解释的优惠选择。该框架在产品类别级别建模上下文，允许优惠跨类别，并实现知识迁移，从而提升动态环境下的学习效率和泛化能力。通过高效的特征工程和模块化设计，框架实现了扩展性，并引入MPG（会员购买间隔）和MF（矩阵分解）等高级功能，捕捉用户与优惠的细微互动，以Python实现支持实际部署。
该框架的关键创新在于大规模可解释性：逻辑回归模型生成透明的权重向量，通过大型语言模型（LLM）界面实现实时、用户级别的偏好演变跟踪和解释，从而生成详细会员档案，识别行为模式，支持个性化优惠优化并增强对自动化决策的信任。通过将我们的原型与广义线性模型和汤普森采样等成熟范式对比，我们展示了其在研究和实际CMAB应用中的价值。

> This paper presents a concise review of Contextual Multi-Armed Bandit (CMAB) methods and introduces an experimental framework for scalable, interpretable offer selection, addressing the challenge of fast-changing offers. The approach models context at the product category level, allowing offers to span multiple categories and enabling knowledge transfer across similar offers. This improves learning efficiency and generalization in dynamic environments. The framework extends standard CMAB methodology to support multi-category contexts, and achieves scalability through efficient feature engineering and modular design. Advanced features such as MPG (Member Purchase Gap) and MF (Matrix Factorization) capture nuanced user-offer interactions, with implementation in Python for practical deployment.
  A key contribution is interpretability at scale: logistic regression models yield transparent weight vectors, accessible via a large language model (LLM) interface for real-time, user-level tracking and explanation of evolving preferences. This enables the generation of detailed member profiles and identification of behavioral patterns, supporting personalized offer optimization and enhancing trust in automated decisions. By situating our prototype alongside established paradigms like Generalized Linear Models and Thompson Sampling, we demonstrate its value for both research and real-world CMAB applications.

[Arxiv](https://arxiv.org/abs/2505.16918)