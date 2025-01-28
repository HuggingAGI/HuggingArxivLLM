# MultiMend: 多语言程序修复——上下文增强与多块补丁生成

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论了基于学习的自动程序修复（APR）方法MultiMend，该方法利用了预训练的编码器-解码器变换器模型（CodeT5）来生成修复错误的补丁。虽然论文中提到了检索增强生成（RAG）技术，但其核心应用是使用大型语言模型（LLM）来提升程序修复的性能。因此，这篇论文更适合归类为LLM应用。` `软件工程` `编程语言`

> MultiMend: Multilingual Program Repair with Context Augmentation and Multi-Hunk Patch Generation

# 摘要

> # 背景
代码中的错误不可避免，可能引发从安全漏洞到操作故障的严重后果。尽管测试和验证技术不断进步，调试软件仍具挑战性，往往需要大量手动工作。基于学习的自动程序修复（APR）在减少手动修复错误的时间、精力和成本方面展现出潜力。然而，现有技术面临语言依赖、错误上下文利用不足以及处理跨多个代码位置的错误等挑战。

# 目标
本文提出MultiMend，一种基于学习的APR方法，旨在通过语言无关的上下文增强和多块补丁生成，提升多种编程语言的修复性能。

# 方法
MultiMend微调了预训练的编码器-解码器变换器模型（CodeT5），用于生成修复错误的补丁。它嵌入源代码行，并在补丁生成过程中应用检索增强生成，以增强错误上下文的相关行。该方法系统性地构建多块错误的补丁，减少补丁验证需求。我们在四个基准测试中评估了MultiMend，涵盖四种编程语言，并与最先进方法进行了对比。

# 结果
实验结果显示，MultiMend在有效性和效率上均表现出色。在所有基准测试中，MultiMend修复了2,077个错误，其中1,455个与开发者补丁一致，106个为多块错误。上下文增强和多块补丁生成均对结果有积极贡献。

# 结论
MultiMend在基准测试中表现优异，研究结果凸显了其在现实世界软件维护中的适用性，以及减少手动调试工作的潜力。

> Context: Bugs in code are inevitable and can lead to severe consequences, ranging from security vulnerabilities to operational failures. Debugging software remains challenging despite advances in testing and verification, often requiring extensive manual effort. Learning-based automated program repair (APR) has shown promise in reducing the time, effort, and cost of manually fixing bugs. However, existing techniques face several challenges, including language-dependent strategies, limited bug context utilization, and difficulties in handling bugs that span multiple locations in the code.
  Objective: This paper introduces MultiMend, a learning-based APR approach designed to improve repair performance on multiple programming languages with language-independent context augmentation and multi-hunk patch generation.
  Method: MultiMend fine-tunes a pre-trained encoder-decoder transformer model (CodeT5) to generate bug-fixing patches. It embeds source code lines and applies retrieval-augmented generation to augment the buggy context with relevant lines during patch generation. The approach systematically constructs patches for multi-hunk bugs to reduce the needed patch validations. We evaluate MultiMend on four benchmarks with four programming languages and compare it with state-of-the-art methods.
  Results: Experimental results show that MultiMend achieves competitive effectiveness and efficiency against compared tools. Across all benchmarks, MultiMend fixes 2,077 bugs, of which 1,455 are identical to the developer's patch, and 106 are for multi-hunk bugs. Both context augmentation and multi-hunk patch generation positively contribute to the results.
  Conclusion: MultiMend shows promising performance across benchmarks. The findings highlight its applicability to real-world software maintenance and its potential to reduce manual debugging efforts.

[Arxiv](https://arxiv.org/abs/2501.16044)