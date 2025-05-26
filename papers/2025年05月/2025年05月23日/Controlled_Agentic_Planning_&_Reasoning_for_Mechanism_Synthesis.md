# 机构综合的可控智能体规划与推理

发布时间：2025年05月23日

`LLM应用` `机械工程` `机制综合`

> Controlled Agentic Planning & Reasoning for Mechanism Synthesis

# 摘要

> 本研究提出了一种双智能体大语言模型（LLM）推理方法，用于机制综合，可在语言和符号层面同时推理，生成几何与动态结果。该模型由一系列明确函数构成，从自然语言规范出发，借助支持方程引用抽象属性，生成并参数化仿真代码，利用符号回归与距离函数提取反馈锚点，形成语言与符号层面的可操作细化循环。在平面机构中，该方法展现出高效且收敛的特性。此外，我们推出全新基准MSynth，深入分析模型组件影响，并证实仅当符号回归提示应用于足够大的架构时，才能揭示机械原理的深层洞见。

> This work presents a dual-agent Large Language Model (LLM)-based reasoning method for mechanism synthesis, capable of reasoning at both linguistic and symbolic levels to generate geometrical and dynamic outcomes. The model consists of a composition of well-defined functions that, starting from a natural language specification, references abstract properties through supporting equations, generates and parametrizes simulation code, and elicits feedback anchor points using symbolic regression and distance functions. This process closes an actionable refinement loop at the linguistic and symbolic layers. The approach is shown to be both effective and convergent in the context of planar mechanisms. Additionally, we introduce MSynth, a novel benchmark for planar mechanism synthesis, and perform a comprehensive analysis of the impact of the model components. We further demonstrate that symbolic regression prompts unlock mechanistic insights only when applied to sufficiently large architectures.

[Arxiv](https://arxiv.org/abs/2505.17607)