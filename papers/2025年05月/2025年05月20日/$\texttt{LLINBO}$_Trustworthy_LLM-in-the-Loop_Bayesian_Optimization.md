# $	exttt{LLINBO}$：可信的循环贝叶斯优化

发布时间：2025年05月20日

`LLM应用` `3D打印` `优化算法`

> $\texttt{LLINBO}$: Trustworthy LLM-in-the-Loop Bayesian Optimization

# 摘要

> 贝叶斯优化 (BO) 作为一种序贯决策工具，在优化昂贵黑箱函数方面应用广泛。近期，大型语言模型 (LLMs) 在小数据场景下展现出出色的适应性，使其有望通过利用上下文知识提出高质量查询点，成为黑箱优化的有力工具。然而，单纯依赖 LLMs 作为优化代理存在风险，原因在于它们缺乏显式的代理建模和校准的不确定性，以及其本质上不透明的内部机制。这种结构性不透明使得难以表征或控制探索与利用之间的权衡，最终削弱了理论可处理性和可靠性。为解决这一问题，我们提出 LLINBO：LLM-in-the-Loop BO，这是一种结合 LLMs 和统计代理专家（例如高斯过程 (GP)）的混合 BO 框架。其核心理念是利用 LLMs 在早期探索中的上下文推理优势，同时依赖于原理严谨的统计模型来指导高效的利用。具体而言，我们引入了三种机制以实现这种协作，并建立了它们的理论保证。本文以 3D 打印场景下的实际概念验证案例结束。欲复现结果，可访问 https://github.com/UMDataScienceLab/LLM-in-the-Loop-BO。


> Bayesian optimization (BO) is a sequential decision-making tool widely used for optimizing expensive black-box functions. Recently, Large Language Models (LLMs) have shown remarkable adaptability in low-data regimes, making them promising tools for black-box optimization by leveraging contextual knowledge to propose high-quality query points. However, relying solely on LLMs as optimization agents introduces risks due to their lack of explicit surrogate modeling and calibrated uncertainty, as well as their inherently opaque internal mechanisms. This structural opacity makes it difficult to characterize or control the exploration-exploitation trade-off, ultimately undermining theoretical tractability and reliability. To address this, we propose LLINBO: LLM-in-the-Loop BO, a hybrid framework for BO that combines LLMs with statistical surrogate experts (e.g., Gaussian Processes (GP)). The core philosophy is to leverage contextual reasoning strengths of LLMs for early exploration, while relying on principled statistical models to guide efficient exploitation. Specifically, we introduce three mechanisms that enable this collaboration and establish their theoretical guarantees. We end the paper with a real-life proof-of-concept in the context of 3D printing. The code to reproduce the results can be found at https://github.com/UMDataScienceLab/LLM-in-the-Loop-BO.

[Arxiv](https://arxiv.org/abs/2505.14756)