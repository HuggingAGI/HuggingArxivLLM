# # 摘要
迈向稳健的事实核查：一种结合先进证据检索技术的多智能体系统

发布时间：2025年06月21日

`Agent

理由：该论文提出了一种多智能体系统，专注于自动事实核查。系统由四个专门的智能体组成，每个智能体负责不同的任务，如声明分解、子查询生成、证据检索和判断预测。该系统的设计和实现主要围绕多智能体协作，因此归类为Agent。` `信息验证`

> Towards Robust Fact-Checking: A Multi-Agent System with Advanced Evidence Retrieval

# 摘要

> 数字时代虚假信息的迅速传播给公共讨论带来了严峻挑战，亟需更强大、可扩展的事实核查解决方案。传统基于人工的事实核查方法虽具可信度，但在处理网络内容的海量与高速方面力不从心，推动了基于大型语言模型（LLMs）的自动系统的引入。然而，现有自动化方法常面临诸多限制，如处理复杂声明、确保来源可信度及保持透明度。本文提出了一种全新的多智能体自动事实核查系统，旨在提升准确性、效率和可解释性。该系统包含四个专门智能体：输入摄取智能体用于声明分解，查询生成智能体用于制定针对性子查询，证据检索智能体用于从可信来源获取证据，以及判决预测智能体用于综合真实判断并生成人类可理解的解释。在基准数据集（FEVEROUS、HOVER、SciFact）上的评估显示，与基线方法相比，本系统实现了12.3%的Macro F1-score提升。该系统能够有效分解复杂声明，从可靠来源检索证据，并为验证决策生成透明解释。我们的方法为不断发展的自动事实核查领域做出了贡献，提供了一种更准确、高效且透明的验证方法论，与人工事实核查实践相契合，同时保持了面向现实应用的可扩展性。我们的源代码可在https://github.com/HySonLab/FactAgent获取

> The rapid spread of misinformation in the digital era poses significant challenges to public discourse, necessitating robust and scalable fact-checking solutions. Traditional human-led fact-checking methods, while credible, struggle with the volume and velocity of online content, prompting the integration of automated systems powered by Large Language Models (LLMs). However, existing automated approaches often face limitations, such as handling complex claims, ensuring source credibility, and maintaining transparency. This paper proposes a novel multi-agent system for automated fact-checking that enhances accuracy, efficiency, and explainability. The system comprises four specialized agents: an Input Ingestion Agent for claim decomposition, a Query Generation Agent for formulating targeted subqueries, an Evidence Retrieval Agent for sourcing credible evidence, and a Verdict Prediction Agent for synthesizing veracity judgments with human-interpretable explanations. Evaluated on benchmark datasets (FEVEROUS, HOVER, SciFact), the proposed system achieves a 12.3% improvement in Macro F1-score over baseline methods. The system effectively decomposes complex claims, retrieves reliable evidence from trusted sources, and generates transparent explanations for verification decisions. Our approach contributes to the growing field of automated fact-checking by providing a more accurate, efficient, and transparent verification methodology that aligns with human fact-checking practices while maintaining scalability for real-world applications. Our source code is available at https://github.com/HySonLab/FactAgent

[Arxiv](https://arxiv.org/abs/2506.17878)