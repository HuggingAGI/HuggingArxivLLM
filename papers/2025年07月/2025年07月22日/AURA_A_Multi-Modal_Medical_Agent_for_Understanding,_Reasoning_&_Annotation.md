# aura：一个多模态医疗代理，助力理解、推理与标注

发布时间：2025年07月22日

`Agent` `医学影像` `智能体AI`

> AURA: A Multi-Modal Medical Agent for Understanding, Reasoning & Annotation

# 摘要

> 大型语言模型（LLMs）的最新进展催化了一场从静态预测系统到具备推理、工具交互和适应复杂任务能力的智能体AI系统的范式转变。尽管基于LLMs的智能体系统在多个领域展现出巨大潜力，但其在医学影像领域的应用仍处于起步阶段。本文介绍AURA，首个专为全面分析、解释和评估医学影像设计的视觉语言可解释性智能体。通过实现动态交互、上下文解释和假设检验，AURA标志着迈向更透明、更具适应性和临床对齐的AI系统的重大进展。我们强调了智能体AI在将医学影像分析从静态预测转变为交互式决策支持方面的潜力。借助基于LLM的Qwen-32B架构，AURA整合了一个模块化工具箱，包含：(i)具备阶段定位、病理分割和解剖分割功能的分割工具包，用于定位具有临床意义的区域；(ii)支持通过图像级解释进行推理的反事实图像生成模块；(iii)一套评估工具，包括像素级差异图分析、分类和先进前沿组件，用于评估诊断相关性和视觉可解释性。

> Recent advancements in Large Language Models (LLMs) have catalyzed a paradigm shift from static prediction systems to agentic AI agents capable of reasoning, interacting with tools, and adapting to complex tasks. While LLM-based agentic systems have shown promise across many domains, their application to medical imaging remains in its infancy. In this work, we introduce AURA, the first visual linguistic explainability agent designed specifically for comprehensive analysis, explanation, and evaluation of medical images. By enabling dynamic interactions, contextual explanations, and hypothesis testing, AURA represents a significant advancement toward more transparent, adaptable, and clinically aligned AI systems. We highlight the promise of agentic AI in transforming medical image analysis from static predictions to interactive decision support. Leveraging Qwen-32B, an LLM-based architecture, AURA integrates a modular toolbox comprising: (i) a segmentation suite with phase grounding, pathology segmentation, and anatomy segmentation to localize clinically meaningful regions; (ii) a counterfactual image-generation module that supports reasoning through image-level explanations; and (iii) a set of evaluation tools including pixel-wise difference-map analysis, classification, and advanced state-of-the-art components to assess diagnostic relevance and visual interpretability.

[Arxiv](https://arxiv.org/abs/2507.16940)