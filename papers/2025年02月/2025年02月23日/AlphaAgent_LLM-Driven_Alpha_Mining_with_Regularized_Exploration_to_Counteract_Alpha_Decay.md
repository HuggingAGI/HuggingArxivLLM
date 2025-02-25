# AlphaAgent：LLM驱动的阿尔法开采，利用正则化探索对抗衰减

发布时间：2025年02月23日

`Agent` `量化投资`

> AlphaAgent: LLM-Driven Alpha Mining with Regularized Exploration to Counteract Alpha Decay

# 摘要

> 阿尔法因子挖掘是量化投资中的关键环节，专注于在日益复杂的金融市场中发现未来资产回报的预测信号。然而，阿尔法衰减这一普遍问题——即因子随时间推移而失去预测能力——给阿尔法因子挖掘带来了巨大挑战。传统方法如遗传编程因过拟合和复杂性问题导致阿尔法快速衰减，而基于大型语言模型（LLMs）的方法虽有潜力，但往往过度依赖现有知识，生成同质化因子，加剧拥挤并加速衰减。为应对这一挑战，我们提出AlphaAgent——一个自主框架，通过结合LLM代理与特定正则化方法，有效挖掘抗衰减的阿尔法因子。AlphaAgent采用三种关键机制：(i) 基于抽象语法树（ASTs）与现有阿尔法的相似性度量，强制生成具有原创性的因子；(ii) 通过LLM评估市场假设与生成因子之间的语义一致性，实现假设-因子对齐；(iii) 基于AST的结构约束控制复杂度，防止易过拟合的过度工程化构造。这些机制共同引导阿尔法生成过程，在原创性、金融合理性及适应市场变化能力之间取得平衡，从而降低阿尔法衰减风险。大量评估表明，AlphaAgent在牛市和熊市中均优于传统方法和LLM方法，过去四年在中国沪深500和美国标普500市场中持续实现显著阿尔法收益。值得注意的是，AlphaAgent展现出卓越的抗衰减能力，显著提升了生成强大因子的可能性。


> Alpha mining, a critical component in quantitative investment, focuses on discovering predictive signals for future asset returns in increasingly complex financial markets. However, the pervasive issue of alpha decay, where factors lose their predictive power over time, poses a significant challenge for alpha mining. Traditional methods like genetic programming face rapid alpha decay from overfitting and complexity, while approaches driven by Large Language Models (LLMs), despite their promise, often rely too heavily on existing knowledge, creating homogeneous factors that worsen crowding and accelerate decay. To address this challenge, we propose AlphaAgent, an autonomous framework that effectively integrates LLM agents with ad hoc regularizations for mining decay-resistant alpha factors. AlphaAgent employs three key mechanisms: (i) originality enforcement through a similarity measure based on abstract syntax trees (ASTs) against existing alphas, (ii) hypothesis-factor alignment via LLM-evaluated semantic consistency between market hypotheses and generated factors, and (iii) complexity control via AST-based structural constraints, preventing over-engineered constructions that are prone to overfitting. These mechanisms collectively guide the alpha generation process to balance originality, financial rationale, and adaptability to evolving market conditions, mitigating the risk of alpha decay. Extensive evaluations show that AlphaAgent outperforms traditional and LLM-based methods in mitigating alpha decay across bull and bear markets, consistently delivering significant alpha in Chinese CSI 500 and US S&P 500 markets over the past four years. Notably, AlphaAgent showcases remarkable resistance to alpha decay, elevating the potential for yielding powerful factors.

[Arxiv](https://arxiv.org/abs/2502.16789)