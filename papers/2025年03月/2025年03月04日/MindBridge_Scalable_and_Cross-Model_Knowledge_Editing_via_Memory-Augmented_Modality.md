# MindBridge: 基于增强记忆的模态实现可扩展跨模型知识编辑

发布时间：2025年03月04日

`LLM应用` `知识管理` `人工智能`

> MindBridge: Scalable and Cross-Model Knowledge Editing via Memory-Augmented Modality

# 摘要

> 知识编辑是一种高效准确地更新大型语言模型（LLMs）知识的技术，旨在解决知识过时和错误修正问题。然而，现有方法大多针对特定模型优化，导致每次LLM更新都需要重新编辑知识，在快速发展的开源社区中尤为不便。为解决这一难题，我们提出了跨模型知识编辑的概念，并推出了MindBridge——一个受多模态模型启发的可扩展解决方案。MindBridge创新性地引入了“记忆模态”概念，将编辑后的知识独立编码为一种新型模态。它首先对记忆模态进行通用预训练，再将其与各类LLMs无缝集成。实验结果表明，MindBridge不仅能在处理数万条知识时保持出色性能，还能灵活适应不同LLMs。我们的代码已开源，地址为https://github.com/CrashBugger/MindBridge。

> Knowledge editing is a technique for efficiently and accurately updating the knowledge of large language models (LLMs) to alleviate obsolescence and correct errors. However, most existing methods overfit to specific models, causing edited knowledge to be discarded during each LLM update and requiring frequent re-editing, which is particularly burdensome in today's rapidly evolving open-source community. To address this issue, we propose the problem of cross-model knowledge editing and introduce MindBridge, a scalable solution inspired by the low coupling between modality processing and LLMs in multi-modal models. MindBridge introduces the novel concept of memory modality, which encodes edited knowledge as an independent modality. It first performs LLM-agnostic pre-training of the memory modality and then integrates it with various LLMs. Extensive experiments on multiple LLMs and popular knowledge editing datasets demonstrate that MindBridge achieves superior performance even in editing tens of thousands of knowledge entries and can flexibly adapt to different LLMs. Our code is available at https://github.com/CrashBugger/MindBridge.

[Arxiv](https://arxiv.org/abs/2503.02701)