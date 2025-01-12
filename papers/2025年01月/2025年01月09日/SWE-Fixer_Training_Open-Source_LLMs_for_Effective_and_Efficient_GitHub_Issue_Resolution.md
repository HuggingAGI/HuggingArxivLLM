# SWE-Fixer: 训练开源 LLM，高效解决 GitHub 问题

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决软件工程中的实际问题，特别是通过修复GitHub用户报告的问题。论文提出了一个名为SWE-Fixer的开源LLM，并详细描述了其核心模块（代码文件检索模块和代码编辑模块）以及如何通过这些模块来生成补丁。此外，论文还提到了构建一个包含110K个GitHub问题及其补丁的数据集，并在基准测试中取得了领先的成绩。这些内容都表明该论文主要关注LLM在实际应用中的使用和优化，因此应归类为“LLM应用”。` `软件工程`

> SWE-Fixer: Training Open-Source LLMs for Effective and Efficient GitHub Issue Resolution

# 摘要

> 大型语言模型（LLMs）在各类复杂任务中表现出色，尤其在软件工程领域，通过修复GitHub用户报告的问题来解决实际任务。然而，现有方法多依赖专有LLMs，限制了可重复性、可访问性和透明度。LLMs在解决软件工程问题中的关键组件及其能力提升方式尚不明确。为此，我们推出了SWE-Fixer，一个开源LLM，旨在高效解决GitHub问题。SWE-Fixer包含两个核心模块：代码文件检索模块和代码编辑模块。检索模块结合BM25和轻量级LLM模型，实现从粗到细的文件检索。代码编辑模块则利用另一个LLM模型为识别出的文件生成补丁。为弥补公开数据集的不足，我们构建了一个包含110K个GitHub问题及其补丁的广泛数据集，并分别训练SWE-Fixer的两个模块。在SWE-Bench Lite和Verified基准测试中，我们的方法在开源模型中分别取得了23.3%和30.2%的领先成绩，证明了其有效性。我们将在https://github.com/InternLM/SWE-Fixer上公开模型、数据集和代码。

> Large Language Models (LLMs) have demonstrated remarkable proficiency across a variety of complex tasks. One significant application of LLMs is in tackling software engineering challenges, particularly in resolving real-world tasks on GitHub by fixing code based on the issues reported by the users. However, many current approaches rely on proprietary LLMs, which limits reproducibility, accessibility, and transparency. The critical components of LLMs for addressing software engineering issues and how their capabilities can be effectively enhanced remain unclear. To address these challenges, we introduce SWE-Fixer, a novel open-source LLM designed to effectively and efficiently resolve GitHub issues. SWE-Fixer comprises two essential modules: a code file retrieval module and a code editing module. The retrieval module employs BM25 along with a lightweight LLM model to achieve coarse-to-fine file retrieval. Subsequently, the code editing module utilizes the other LLM model to generate patches for the identified files. Then, to mitigate the lack of publicly available datasets, we compile an extensive dataset that includes 110K GitHub issues along with their corresponding patches, and train the two modules of SWE-Fixer separately. We assess our approach on the SWE-Bench Lite and Verified benchmarks, achieving state-of-the-art performance among open-source models with scores of 23.3% and 30.2%, respectively. These outcomes highlight the efficacy of our approach. We will make our model, dataset, and code publicly available at https://github.com/InternLM/SWE-Fixer.

[Arxiv](https://arxiv.org/abs/2501.05040)