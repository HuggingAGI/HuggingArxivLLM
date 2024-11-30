# 面对仓库级自动程序修复任务，大型语言模型的表现究竟如何呢？

发布时间：2024年03月01日

`LLM应用`

> When Large Language Models Confront Repository-Level Automatic Program Repair: How Well They Done?

# 摘要

> 近年来，LLMs 在 APR 任务上崭露头角，但在评估其性能时，研究焦点仅限于包含错误的单个函数或文件，忽略了仓库级上下文中的丰富信息资源。本研究推出 RepoBugs，一个由124个源自开源仓库的典型仓库级bug组成的新基准测试集。实验证明，在利用 GPT3.5 处理RepoBugs时，仅凭错误所在函数上下文的修复率低至22.58%，明显低于其在函数级bug修复上的表现，揭示了在处理仓库级问题时充分考虑仓库全局上下文的重要性。但现有的初步方法所提取的仓库级上下文往往过于冗余和不准确，而且很容易超出LLMs的输入长度限制。因此，我们创新设计了一种简洁普适的仓库级上下文提取策略RLCE，旨在为仓库级代码修复任务提供更为精准的上下文环境。通过对比测试三种主流LLMs，结果显示RLCE能够显著提升修复仓库级bug的成功率，最高可比原有方法提高达160%。同时，我们深入剖析了RLCE的有效性和局限性，以及LLMs应对仓库级bug挑战的潜力，为后续研究提供了宝贵的洞见。

> In recent years, large language models (LLMs) have demonstrated substantial potential in addressing automatic program repair (APR) tasks. However, the current evaluation of these models for APR tasks focuses solely on the limited context of the single function or file where the bug is located, overlooking the valuable information in the repository-level context. This paper investigates the performance of popular LLMs in handling repository-level repair tasks. We introduce RepoBugs, a new benchmark comprising 124 typical repository-level bugs from open-source repositories. Preliminary experiments using GPT3.5 based on the function where the error is located, reveal that the repair rate on RepoBugs is only 22.58%, significantly diverging from the performance of GPT3.5 on function-level bugs in related studies. This underscores the importance of providing repository-level context when addressing bugs at this level. However, the repository-level context offered by the preliminary method often proves redundant and imprecise and easily exceeds the prompt length limit of LLMs. To solve the problem, we propose a simple and universal repository-level context extraction method (RLCE) designed to provide more precise context for repository-level code repair tasks. Evaluations of three mainstream LLMs show that RLCE significantly enhances the ability to repair repository-level bugs. The improvement reaches a maximum of 160% compared to the preliminary method. Additionally, we conduct a comprehensive analysis of the effectiveness and limitations of RLCE, along with the capacity of LLMs to address repository-level bugs, offering valuable insights for future research.

[Arxiv](https://arxiv.org/abs/2403.00448)