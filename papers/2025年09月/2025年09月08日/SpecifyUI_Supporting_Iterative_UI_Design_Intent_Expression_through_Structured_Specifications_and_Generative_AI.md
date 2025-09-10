# SpecifyUI：基于结构化规范与生成式AI，助力迭代式UI设计意图的表达

发布时间：2025年09月08日

`LLM应用` `媒体与娱乐`

> SpecifyUI: Supporting Iterative UI Design Intent Expression through Structured Specifications and Generative AI

# 摘要

> 大型语言模型（LLMs）有望加速UI设计，然而现有工具却面临两大核心难题：一是难以外化设计师的意图，二是难以控制迭代变更。为此，我们提出了SPEC——一种结构化、参数化、分层的中间表示，它能将UI元素转化为可调控的参数。基于SPEC，我们开发了交互式系统SpecifyUI。该系统通过区域分割与视觉-语言模型从UI参考中提取SPEC，能跨多源组合UI，并支持在全局、区域及组件层面进行精准编辑。多智能体生成器可将SPEC渲染为高保真设计，从而打通了意图表达与可控生成之间的闭环。定量实验显示，相比基于提示的基线方法，基于SPEC的生成能更精准地捕捉参考意图。在16名专业设计师参与的用户研究中，SpecifyUI在人机协作创作的意图对齐、设计质量、可控性及整体体验上均显著优于Stitch。研究结果表明，SPEC是一种规范驱动的范式，它将LLM辅助设计从一次性提示转变为迭代协作的工作流。

> Large language models (LLMs) promise to accelerate UI design, yet current tools struggle with two fundamentals: externalizing designers' intent and controlling iterative change. We introduce SPEC, a structured, parameterized, hierarchical intermediate representation that exposes UI elements as controllable parameters. Building on SPEC, we present SpecifyUI, an interactive system that extracts SPEC from UI references via region segmentation and vision-language models, composes UIs across multiple sources, and supports targeted edits at global, regional, and component levels. A multi-agent generator renders SPEC into high-fidelity designs, closing the loop between intent expression and controllable generation. Quantitative experiments show SPEC-based generation more faithfully captures reference intent than prompt-based baselines. In a user study with 16 professional designers, SpecifyUI significantly outperformed Stitch on intent alignment, design quality, controllability, and overall experience in human-AI co-creation. Our results position SPEC as a specification-driven paradigm that shifts LLM-assisted design from one-shot prompting to iterative, collaborative workflows.

[Arxiv](https://arxiv.org/abs/2509.07334)