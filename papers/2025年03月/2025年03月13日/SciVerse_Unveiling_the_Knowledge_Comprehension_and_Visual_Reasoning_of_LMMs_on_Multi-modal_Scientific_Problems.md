# # SciVerse: 多模态模型在多模态科学问题中的知识理解与视觉推理能力研究
SciVerse：研究多模态模型在多模态科学问题中的知识理解与视觉推理能力。

发布时间：2025年03月13日

`LLM应用

理由：这篇论文探讨了大型多模态模型（LMMs）在科学问题解决中的应用，并引入了SciVerse作为评估基准，重点分析了模型在科学知识理解、多模态内容解析和推理能力方面的表现。研究集中在模型的应用和评估，属于LLM的应用层面。` `多模态模型`

> SciVerse: Unveiling the Knowledge Comprehension and Visual Reasoning of LMMs on Multi-modal Scientific Problems

# 摘要

> 大型多模态模型（LMMs）的快速发展为科学问题解决提供了应用可能，但其精细能力仍有待深入探索。本文中，我们引入了SciVerse，一个多模态科学评估基准，旨在全面评估LMMs在5735个测试实例和五个不同版本中的表现。我们的研究聚焦于LMMs的三大核心维度：科学知识理解、多模态内容解析以及Chain-of-Thought（CoT）推理能力。为了检验LMMs是否具备足够的科学专业知识，我们首先将每个问题转化为三个不同知识要求的版本，即无知识（Knowledge-free）、轻知识（-lite）和富知识（-rich）版本。接着，为了探究LMMs如何解析多模态科学内容，我们标注了另外两个版本，即视觉丰富（Vision-rich）和视觉仅（-only）版本，将更多问题信息从文本标注到图表中。通过对比不同版本的结果，SciVerse系统性地考察了LMMs在科学领域的专业知识储备和视觉感知技能。此外，为了严谨评估CoT推理能力，我们提出了一种新的科学CoT评估策略，对模型输出中的知识和逻辑错误进行分步评估。我们在SciVerse上对不同LMMs的广泛评估揭示了它们在科学专业性方面的关键局限性，并为未来的发展提供了新的见解。项目页面：https://sciverse-cuhk.github.io

> The rapid advancement of Large Multi-modal Models (LMMs) has enabled their application in scientific problem-solving, yet their fine-grained capabilities remain under-explored. In this paper, we introduce SciVerse, a multi-modal scientific evaluation benchmark to thoroughly assess LMMs across 5,735 test instances in five distinct versions. We aim to investigate three key dimensions of LMMs: scientific knowledge comprehension, multi-modal content interpretation, and Chain-of-Thought (CoT) reasoning. To unveil whether LMMs possess sufficient scientific expertise, we first transform each problem into three versions containing different levels of knowledge required for solving, i.e., Knowledge-free, -lite, and -rich. Then, to explore how LMMs interpret multi-modal scientific content, we annotate another two versions, i.e., Vision-rich and -only, marking more question information from texts to diagrams. Comparing the results of different versions, SciVerse systematically examines the professional knowledge stock and visual perception skills of LMMs in scientific domains. In addition, to rigorously assess CoT reasoning, we propose a new scientific CoT evaluation strategy, conducting a step-wise assessment on knowledge and logical errors in model outputs. Our extensive evaluation of different LMMs on SciVerse reveals critical limitations in their scientific proficiency and provides new insights into future developments. Project page: https://sciverse-cuhk.github.io

[Arxiv](https://arxiv.org/abs/2503.10627)