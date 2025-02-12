# RAG-Verus：基于增强生成的大型语言模型仓库级程序验证

发布时间：2025年02月07日

`RAG` `软件工程` `计算机科学`

> RAG-Verus: Repository-Level Program Verification with LLMs using Retrieval Augmented Generation

# 摘要

> 将自动形式验证扩展到现实项目，需要解决跨模块依赖和全局上下文问题，这些问题被现有函数中心方法忽视。我们引入了RagVerus框架，该框架结合检索增强生成与上下文感知提示，以实现多模块仓库的自动化证明合成。在我们全新的RepoVBench基准上，RagVerus实现了27%的相对提升——这是首个针对Verus的仓库级数据集，包含383个证明完成任务。在受限语言模型预算下，RagVerus使证明通过率提高了三倍，展示了其可扩展性和样本高效的验证能力。

> Scaling automated formal verification to real-world projects requires resolving cross-module dependencies and global contexts, which are challenges overlooked by existing function-centric methods. We introduce RagVerus, a framework that synergizes retrieval-augmented generation with context-aware prompting to automate proof synthesis for multi-module repositories, achieving a 27% relative improvement on our novel RepoVBench benchmark -- the first repository-level dataset for Verus with 383 proof completion tasks. RagVerus triples proof pass rates on existing benchmarks under constrained language model budgets, demonstrating a scalable and sample-efficient verification.

[Arxiv](https://arxiv.org/abs/2502.05344)