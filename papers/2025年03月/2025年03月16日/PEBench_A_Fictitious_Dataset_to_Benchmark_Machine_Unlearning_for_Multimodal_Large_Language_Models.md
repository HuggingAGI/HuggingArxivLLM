# PEBench：用于评估多模态大型语言模型机器遗忘能力的虚构数据集

发布时间：2025年03月16日

`LLM应用`

> PEBench: A Fictitious Dataset to Benchmark Machine Unlearning for Multimodal Large Language Models

# 摘要

> 近年来，多模态大型语言模型（MLLMs）在视觉问答、理解及推理等领域取得了显著进展。然而，这些成就建立在从互联网获取的海量数据之上，引发了对隐私和安全的重大担忧。为应对这一挑战，机器遗忘（MU）作为一种创新解决方案应运而生，能够在不重新训练模型的情况下移除特定知识。尽管MLLMs的MU研究受到关注，但现有评估仍不完善，且问题定义不够清晰，限制了更安全可信系统的发展。为此，我们推出PEBench基准测试，包含个人实体数据集及其对应的一般事件场景，旨在全面评估MLLMs中MU的性能。通过PEBench，我们致力于构建一个标准化、稳健的研究框架，推动安全隐私保护的多模态模型发展。通过对6种MU方法的基准测试，我们揭示了它们的优缺点，并为MLLMs中的MU研究指明了关键挑战与机遇。

> In recent years, Multimodal Large Language Models (MLLMs) have demonstrated remarkable advancements in tasks such as visual question answering, visual understanding, and reasoning. However, this impressive progress relies on vast amounts of data collected from the internet, raising significant concerns about privacy and security. To address these issues, machine unlearning (MU) has emerged as a promising solution, enabling the removal of specific knowledge from an already trained model without requiring retraining from scratch. Although MU for MLLMs has gained attention, current evaluations of its efficacy remain incomplete, and the underlying problem is often poorly defined, which hinders the development of strategies for creating more secure and trustworthy systems. To bridge this gap, we introduce a benchmark, named PEBench, which includes a dataset of personal entities and corresponding general event scenes, designed to comprehensively assess the performance of MU for MLLMs. Through PEBench, we aim to provide a standardized and robust framework to advance research in secure and privacy-preserving multimodal models. We benchmarked 6 MU methods, revealing their strengths and limitations, and shedding light on key challenges and opportunities for MU in MLLMs.

[Arxiv](https://arxiv.org/abs/2503.12545)