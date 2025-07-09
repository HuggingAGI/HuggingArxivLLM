# 构建基于LLM的推理工具的现有方法目前较为零散，但我们完全有能力做得更好！

发布时间：2025年07月08日

`LLM理论` `软件工程` `人工智能`

> Current Practices for Building LLM-Powered Reasoning Tools Are Ad Hoc -- and We Can Do Better

# 摘要

> 近年来，关于结合传统符号算法与大型语言模型（LLMs）构建软件验证器、综合器等自动推理（AR）工具的研究蓬勃发展。然而，目前构建这类神经符号AR系统的方法存在两大局限：其一，现有方法是一种缺乏传统符号算法强保证的即兴编程模型；其二，神经网络与符号推理之间尚未实现足够深度的同步，无法充分发挥LLM驱动推理的潜力。本文提出神经符号转换系统作为构建神经符号AR工具的基础设施的原理性计算模型。在此模型中，符号状态与直觉配对，状态转换在符号和直觉之间并行操作。本文阐述了这一新范式如何在保持符号算法强保证的同时，将逻辑推理能力扩展到现有能力之外，并概述了如何将本文提出的计算模型在逻辑编程语言中实现。

> There is growing excitement about building software verifiers, synthesizers, and other Automated Reasoning (AR) tools by combining traditional symbolic algorithms and Large Language Models (LLMs). Unfortunately, the current practice for constructing such neurosymbolic AR systems is an ad hoc programming model that does not have the strong guarantees of traditional symbolic algorithms, nor a deep enough synchronization of neural networks and symbolic reasoning to unlock the full potential of LLM-powered reasoning. I propose Neurosymbolic Transition Systems as a principled computational model that can underlie infrastructure for building neurosymbolic AR tools. In this model, symbolic state is paired with intuition, and state transitions operate over symbols and intuition in parallel. I argue why this new paradigm can scale logical reasoning beyond current capabilities while retaining the strong guarantees of symbolic algorithms, and I sketch out how the computational model I propose can be reified in a logic programming language.

[Arxiv](https://arxiv.org/abs/2507.05886)