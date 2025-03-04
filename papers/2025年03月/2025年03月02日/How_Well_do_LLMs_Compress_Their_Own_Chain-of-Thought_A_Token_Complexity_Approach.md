# 大型语言模型的思维链压缩能力如何？基于Token复杂度的分析

发布时间：2025年03月02日

`LLM理论` `人工智能`

> How Well do LLMs Compress Their Own Chain-of-Thought? A Token Complexity Approach

# 摘要

> 思维链提示已成为一项强大的技术，使大型语言模型能够解决复杂的推理任务。然而，冗长的推理链引发了对效率的担忧。近期研究通过简单的提示策略（如“要简洁”）尝试缩短回答长度。本研究首次系统性地研究了压缩指令（如“使用10个单词以内”或“删除所有标点”）与模型性能之间的关系。我们发现，推理链长度与准确性之间存在一种普遍的权衡关系，即使在非常不同的推理链中也持续存在。我们证明，这种权衡源于问题层面的阈值行为：每个任务都有一个固有的“token复杂度”——成功解决问题所需的最小token数量。我们展示了如何利用token复杂度来计算准确率与压缩之间的信息理论极限，并发现基于提示的压缩策略远未达到这些理论极限。这表明，推理效率方面可能存在显著的改进空间，我们的框架为此提供了一个基准，帮助研究人员评估进展。我们的工作还强调了自适应压缩的重要性——即对简单问题提供更短的回答——并且我们展示了token复杂度是衡量这种能力的有用工具。


> Chain-of-thought prompting has emerged as a powerful technique for enabling large language models (LLMs) to solve complex reasoning tasks. However, these reasoning chains can be verbose, raising concerns about efficiency. In response, recent works have sought to decrease response lengths through simple prompting strategies (e.g. 'be concise'). In this work, we conduct the first systematic study of the relationship between reasoning length and model performance across a diverse range of compression instructions (e.g. 'use 10 words or less' or 'remove all punctuation'). In doing so, we discover a universal tradeoff between reasoning length and accuracy that persists across even very distinct reasoning chains. We demonstrate that this tradeoff emerges from a sharp threshold behavior at the question level: each task has an intrinsic 'token complexity' - a minimal number of tokens required for successful problem-solving. We show how token complexity enables us to compute information-theoretic limits on the accuracy-compression tradeoff, and find that prompt-based compression strategies operate far from these theoretical limits. This suggests there may be significant room for improvement and our framework provides a benchmark to help researchers evaluate progress in reasoning efficiency. Our work also highlights the importance of adaptive compression -- giving shorter responses for easier questions -- and we show that token complexity is a useful tool for measuring this capability.

[Arxiv](https://arxiv.org/abs/2503.01141)