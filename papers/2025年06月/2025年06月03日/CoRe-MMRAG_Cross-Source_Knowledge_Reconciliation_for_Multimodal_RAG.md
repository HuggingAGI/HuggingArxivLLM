# CoRe-MMRAG：跨源知识对齐的多模态 RAG 方法

发布时间：2025年06月03日

`RAG` `问答系统` `计算机视觉`

> CoRe-MMRAG: Cross-Source Knowledge Reconciliation for Multimodal RAG

# 摘要

> 为了提升多模态大语言模型的能力，多模态检索增强生成（MMRAG）被提出，通过整合外部检索的多模态知识来增强模型性能。然而，这一方法带来了两个主要挑战：参数化检索知识不一致性（PRKI）和视觉文本知识不一致性（VTKI）。针对这些问题，我们提出了跨源知识协调的多模态RAG框架（CoRe-MMRAG），这是一种创新的端到端解决方案，能够有效协调不同知识源之间的不一致。CoRe-MMRAG采用四阶段流水线：首先基于模型内部的参数化知识生成初步响应，然后通过多模态证据的联合相似性评估筛选出最相关的外部信息，接着生成基于外部知识的响应，最后将两者整合以生成最终的可靠答案。此外，我们设计了一种专门的训练范式，进一步优化了模型在知识源区分、多模态整合以及统一答案生成方面的能力。实验结果表明，在KB-VQA基准测试中，CoRe-MMRAG相比基线方法取得了显著性能提升，在InfoSeek和Encyclopedic-VQA两个数据集上分别实现了5.6%和9.3%的性能提升。为了促进研究，我们开源了代码和数据集，访问链接为\href{https://github.com/TyangJN/CoRe-MMRAG}{https://github.com/TyangJN/CoRe-MMRAG}。

> Multimodal Retrieval-Augmented Generation (MMRAG) has been introduced to enhance Multimodal Large Language Models by incorporating externally retrieved multimodal knowledge, but it introduces two challenges: Parametric-Retrieved Knowledge Inconsistency (PRKI), where discrepancies between parametric and retrieved knowledge create uncertainty in determining reliability, and Visual-Textual Knowledge Inconsistency (VTKI), where misalignment between visual and textual sources disrupts entity representation. To address these challenges, we propose \textbf{C}r\textbf{o}ss-source knowledge \textbf{Re}conciliation for \textbf{M}ulti\textbf{M}odal \textbf{RAG} (CoRe-MMRAG), a novel end-to-end framework that effectively reconciles inconsistencies across knowledge sources. CoRe-MMRAG follows a four-stage pipeline: it first generates an internal response from parametric knowledge, then selects the most relevant multimodal evidence via joint similarity assessment, generates an external response, and finally integrates both to produce a reliable answer. Additionally, a specialized training paradigm enhances knowledge source discrimination, multimodal integration, and unified answer generation. Experiments on KB-VQA benchmarks show that CoRe-MMRAG achieves substantial improvements over baseline methods, achieving 5.6\% and 9.3\% performance gains on InfoSeek and Encyclopedic-VQA, respectively. We release code and data at \href{https://github.com/TyangJN/CoRe-MMRAG}{https://github.com/TyangJN/CoRe-MMRAG}.

[Arxiv](https://arxiv.org/abs/2506.02544)