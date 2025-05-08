# OmniGIRL：一个多语言多模态的GitHub问题处理基准

发布时间：2025年05月07日

`LLM应用` `软件工程` `跨领域`

> OmniGIRL: A Multilingual and Multimodal Benchmark for GitHub Issue Resolution

# 摘要

> GitHub问题解决任务致力于自动解决仓库中报告的问题。随着大型语言模型（LLMs）的发展，这一任务逐渐受到关注，已有多个基准测试被提出以评估LLMs的问题解决能力。然而，现有基准测试存在三大局限性：首先，它们主要聚焦于单一编程语言，难以全面评估多语言仓库的问题；其次，涵盖的领域范围有限，可能无法代表现实世界问题的多样性；第三，仅依赖于问题描述的文本信息，忽视了图片等多模态信息。本文提出OmniGIRL，这是一个多语言、多模态、跨领域的GitHub问题解决基准测试。OmniGIRL包含959个任务实例，覆盖四种编程语言（Python、JavaScript、TypeScript、Java）和八个领域。评估结果显示，当前LLMs在OmniGIRL上的表现有限。值得注意的是，性能最佳的模型GPT-4o仅能解决8.6%的问题。此外，LLMs在需要理解图片的问题上表现尤为困难，最佳模型Claude-3.5-Sonnet仅能解决10.5%包含图片信息的问题。最后，我们分析了LLMs在OmniGIRL上表现不佳的原因，为未来改进提供了重要启示。

> The GitHub issue resolution task aims to resolve issues reported in repositories automatically. With advances in large language models (LLMs), this task has gained increasing attention, and several benchmarks are proposed to evaluate the issue resolution ability of LLMs. However, existing benchmarks have three main limitations. First, current benchmarks focus on a single programming language, limiting the evaluation of issues from repositories across different languages. Second, they usually cover a narrow range of domains, which may fail to represent the diversity of real-world issues. Third, existing benchmarks rely solely on textual information in issue descriptions, overlooking multimodal information such as images in issues. In this paper, we propose OmniGIRL, a GitHub Issue ResoLution benchmark that is multilingual, multimodal, and multi-domain. OmniGIRL includes 959 task instances, which are collected from repositories across four programming languages (i.e., Python, JavaScript, TypeScript, and Java) and eight different domains. Our evaluation shows that current LLMs show limited performances on OmniGIRL. Notably, the best-performing model, GPT-4o, resolves only 8.6% of the issues. Besides, we find that current LLMs struggle to resolve issues requiring understanding images. The best performance is achieved by Claude-3.5-Sonnet, which resolves only 10.5% of the issues with image information. Finally, we analyze the reasons behind current LLMs' failure on OmniGIRL, providing insights for future improvements.

[Arxiv](https://arxiv.org/abs/2505.04606)