# DrSR：基于大语言模型的科学方程发现，通过数据与经验双推理

发布时间：2025年06月04日

`LLM应用`

> DrSR: LLM based Scientific Equation Discovery with Dual Reasoning from Data and Experience

# 摘要

> 符号回归是科学与工程领域中发现可解释数学表达式的核心工具。近期，大型语言模型（LLMs）凭借内置的科学先验知识和推理能力，在该任务中表现优异，超越了传统方法。然而，现有基于LLM的方法（如LLM-SR）往往过分依赖内部先验知识，在方程生成过程中缺乏对数据的明确理解与系统性反思。为解决这一问题，我们提出DrSR（双重推理符号回归）——一个结合数据驱动洞察与反思学习的框架，旨在提升模型的鲁棒性和发现能力。具体而言，DrSR引导LLMs深入分析数据中的结构关系（如单调性、非线性及关联性），并生成结构化描述。同时，它实时监控方程性能，建立反馈循环以优化后续生成。通过在闭环系统中整合数据理解与生成反思，DrSR实现了对符号表达式空间的更高效探索。跨学科数据集的实验表明，DrSR显著提升了有效方程的生成率，并在准确性、泛化能力和搜索效率方面始终优于传统方法和近期基于LLM的方法。这些成果凸显了其在科学方程发现领域的巨大潜力。

> Symbolic regression is a fundamental tool for discovering interpretable mathematical expressions from data, with broad applications across scientific and engineering domains. Recently, large language models (LLMs) have demonstrated strong performance in this task, leveraging embedded scientific priors and reasoning capabilities to surpass traditional methods. However, existing LLM-based approaches, such as LLM-SR, often over-rely on internal priors, lacking explicit data understanding and systematic reflection during equation generation. To address these limitations, we propose DrSR (Dual Reasoning Symbolic Regression), a framework that combines data-driven insight with reflective learning to enhance both robustness and discovery capability. Specifically, DrSR guides LLMs to analyze structural relationships (e.g., monotonicity, nonlinearity, and correlation) within the data to generate structured descriptions. Simultaneously, it monitors equation performance and establishes a feedback loop to refine subsequent generations. By integrating data understanding and generation reflection in a closed loop, DrSR enables more efficient exploration of the symbolic expression space. Experiments across interdisciplinary datasets in physics, chemistry, biology, and materials science demonstrate that DrSR substantially improves the valid equation rate and consistently outperforms both classical and recent LLM-based methods in terms of accuracy, generalization, and search efficiency. These results underscore its potential for scientific equation discovery.

[Arxiv](https://arxiv.org/abs/2506.04282)