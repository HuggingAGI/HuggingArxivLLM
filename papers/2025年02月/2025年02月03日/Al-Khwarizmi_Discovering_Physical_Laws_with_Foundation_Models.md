# Al-Khwarizmi：用基础模型探索物理定律

发布时间：2025年02月03日

`Agent

理由：这篇论文描述了一个名为Al-Khwarizmi的智能体框架，该框架结合了基础模型和稀疏非线性动力学识别（SINDy）方法，用于从数据中发现物理定律。该框架利用大型语言模型（LLMs）、视觉语言模型（VLMs）和检索增强生成（RAG）来自动化物理定律的发现过程，并通过反思迭代优化候选解。这种结合了多种技术并具有自主学习和优化能力的系统，符合“Agent”分类的定义，即具有自主性和智能行为的系统。` `科学发现`

> Al-Khwarizmi: Discovering Physical Laws with Foundation Models

# 摘要

> 从数据中推断物理定律是科学和工程中的核心挑战，涵盖医疗、物理、生物、社会、可持续性、气候和机器人等多个领域。深度网络虽精度高，但缺乏可解释性，因此人们开始关注由简单组件构建的模型。稀疏非线性动力学识别（SINDy）方法因其模块化和可解释性成为首选。SINDy通过L1正则化的稀疏回归从候选函数库中识别关键项，但其对候选库和优化方法的选择依赖大量技术知识，限制了广泛应用。本研究提出Al-Khwarizmi，一种结合基础模型与SINDy的新型智能体框架，用于从数据中发现物理定律。利用LLMs、VLMs和检索增强生成（RAG），我们的方法自动化了物理定律的发现，结合先验知识并通过反思迭代优化候选解。Al-Khwarizmi分两步操作：首先总结系统观察结果（包括文本描述、原始数据和图表），然后生成候选特征库和优化器配置，以正确识别隐藏的物理定律。我们在198多个模型上评估了该算法，展示了其相比替代方案的最先进性能，比最佳替代方案提升了20%。

> Inferring physical laws from data is a central challenge in science and engineering, including but not limited to healthcare, physical sciences, biosciences, social sciences, sustainability, climate, and robotics. Deep networks offer high-accuracy results but lack interpretability, prompting interest in models built from simple components. The Sparse Identification of Nonlinear Dynamics (SINDy) method has become the go-to approach for building such modular and interpretable models. SINDy leverages sparse regression with L1 regularization to identify key terms from a library of candidate functions. However, SINDy's choice of candidate library and optimization method requires significant technical expertise, limiting its widespread applicability. This work introduces Al-Khwarizmi, a novel agentic framework for physical law discovery from data, which integrates foundational models with SINDy. Leveraging LLMs, VLMs, and Retrieval-Augmented Generation (RAG), our approach automates physical law discovery, incorporating prior knowledge and iteratively refining candidate solutions via reflection. Al-Khwarizmi operates in two steps: it summarizes system observations-comprising textual descriptions, raw data, and plots-followed by a secondary step that generates candidate feature libraries and optimizer configurations to identify hidden physics laws correctly. Evaluating our algorithm on over 198 models, we demonstrate state-of-the-art performance compared to alternatives, reaching a 20 percent increase against the best-performing alternative.

[Arxiv](https://arxiv.org/abs/2502.01702)