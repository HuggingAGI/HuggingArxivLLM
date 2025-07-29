# evalSmarT —— 基于大型语言模型的智能合约注释评估框架

发布时间：2025年07月28日

`LLM应用` `区块链` `人工智能`

> evalSmarT: An LLM-Based Framework for Evaluating Smart Contract Generated Comments

# 摘要

> **智能合约注释生成**作为一种提升区块链系统代码可理解性和可维护性的方法，近年来受到广泛关注。然而，评估生成注释的质量仍是一个难题。传统的BLEU和ROUGE等指标难以捕捉特定领域的细微差别，而人工评估成本高昂且难以扩展。本文中，我们提出了	exttt{evalSmarT}，一个模块化且可扩展的框架，利用大型语言模型（LLMs）作为评估器。该系统通过结合约40种LLMs与10种提示策略，支持超过400种评估器配置。我们展示了其在评估注释生成工具和选择最富信息量输出中的应用。实验结果表明，提示设计对与人工判断的一致性影响显著，而基于LLM的评估为现有方法提供了一种可扩展且语义丰富的替代方案。

> Smart contract comment generation has gained traction as a means to improve code comprehension and maintainability in blockchain systems. However, evaluating the quality of generated comments remains a challenge. Traditional metrics such as BLEU and ROUGE fail to capture domain-specific nuances, while human evaluation is costly and unscalable. In this paper, we present \texttt{evalSmarT}, a modular and extensible framework that leverages large language models (LLMs) as evaluators. The system supports over 400 evaluator configurations by combining approximately 40 LLMs with 10 prompting strategies. We demonstrate its application in benchmarking comment generation tools and selecting the most informative outputs. Our results show that prompt design significantly impacts alignment with human judgment, and that LLM-based evaluation offers a scalable and semantically rich alternative to existing methods.

[Arxiv](https://arxiv.org/abs/2507.20774)