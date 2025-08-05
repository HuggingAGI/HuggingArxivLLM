# MArgE：从多个大型语言模型中融合论证证据，实现可辩护声明的验证

发布时间：2025年08月04日

`LLM应用

理由：这篇论文讨论了如何通过结合多个大型语言模型（LLMs）来提高任务的性能和减少错误生成，特别是通过引入结构化的论点树来增强可信度。虽然它提出了一个新的框架（MArgE），但主要关注的是如何在实际任务中应用和优化多个LLMs，因此归类为LLM应用。` `知识图谱` `论辩系统`

> MArgE: Meshing Argumentative Evidence from Multiple Large Language Models for Justifiable Claim Verification

# 摘要

> 利用多个大型语言模型（LLMs）的输出，我们可以在广泛的任务中发挥其能力，同时减少它们的错误生成能力，例如幻觉现象。然而，当前结合多个LLMs见解的方法通常涉及非结构化的交互（例如自由辩论），导致模型生成的结果缺乏可信的依据。在本研究中，我们引入了MArgE，一个新颖的框架，旨在为每个LLM提供的证据赋予正式的结构，具体表现为提取的论点树，用于声明验证任务。我们采用了一种基于计算论辩领域中的框架和语义驱动的LLMs变体，即基于论辩的LLMs（ArgLLMs），为给定的声明构建结构化的论点树。这一过程创建了一个可检查的路径，从初始论点到最终的声明验证决策，从而提供了对该决策的可信依据。我们通过实验展示了MArgE在性能上显著超越单一LLMs，包括三个开源模型（4B到8B参数）、GPT-4o-mini以及现有的ArgLLMs，同时也优于之前用于非结构化多LLM辩论的方法。这证明了在结合多个LLM输出时，整合正式的、基于论辩的推理机制的优势。

> Leveraging outputs from multiple large language models (LLMs) is emerging as a method for harnessing their power across a wide range of tasks while mitigating their capacity for making errors, e.g., hallucinations. However, current approaches to combining insights from multiple LLMs often involve unstructured interactions (e.g., free debate), resulting in model generations that are not faithfully justifiable. In this work, we introduce MArgE, a novel framework to provide formal structure to the evidence from each LLM, in the form of a tree of extracted arguments, for the task of claim verification. We use a variant of Argumentative LLMs (ArgLLMs), i.e. LLMs driven by frameworks and semantics from the field of computational argumentation, to construct structured argument trees for given claims. This process creates an inspectable pathway from the initial arguments to the final claim verification decisions, providing a faithful justification thereof. We show experimentally that MArgE can significantly outperform single LLMs, including three open-source models (4B to 8B parameters), GPT-4o-mini and existing ArgLLMs, as well as prior methods for unstructured multi-LLM debates. We thus demonstrate the advantages of incorporating formal, argumentative reasoning mechanisms when combining multiple LLM outputs.

[Arxiv](https://arxiv.org/abs/2508.02584)