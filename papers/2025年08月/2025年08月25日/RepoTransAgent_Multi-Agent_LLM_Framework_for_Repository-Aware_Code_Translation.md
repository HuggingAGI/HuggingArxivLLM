# RepoTransAgent：面向仓库感知代码翻译的多智能体LLM框架

发布时间：2025年08月25日

`Agent` `工业与制造`

> RepoTransAgent: Multi-Agent LLM Framework for Repository-Aware Code Translation

# 摘要

> 仓库感知代码翻译对遗留系统现代化、提升可维护性及实现跨编程语言互操作性至关重要。尽管大型语言模型（LLMs）的最新进展已改善代码翻译质量，但现有方法在实际应用中仍面临三大挑战：上下文理解不足、提示设计僵化及错误纠正机制薄弱。这些局限严重阻碍了复杂真实代码仓库的准确高效翻译。为解决上述问题，我们提出RepoTransAgent——一种新型仓库感知代码翻译多智能体LLM框架。该框架将翻译过程系统分解为三大专门子任务：上下文检索、动态提示构建和迭代代码优化，每个子任务由专门智能体负责。我们的方法通过检索增强生成（RAG）收集上下文信息，采用针对不同仓库场景定制的自适应提示，并引入基于反思的系统错误纠正机制。我们在六个流行开源项目的数百对Java-C#翻译对上对RepoTransAgent进行了评估。实验结果显示，RepoTransAgent在编译率和通过率上均显著优于当前最先进的基线模型，其中编译率最高达55.34%，通过率达45.84%。综合分析证实，RepoTransAgent在不同LLM上均具备良好的鲁棒性和通用性，充分证明了其在实际仓库感知代码翻译任务中的有效性。

> Repository-aware code translation is critical for modernizing legacy systems, enhancing maintainability, and enabling interoperability across diverse programming languages. While recent advances in large language models (LLMs) have improved code translation quality, existing approaches face significant challenges in practical scenarios: insufficient contextual understanding, inflexible prompt designs, and inadequate error correction mechanisms. These limitations severely hinder accurate and efficient translation of complex, real-world code repositories. To address these challenges, we propose RepoTransAgent, a novel multi-agent LLM framework for repository-aware code translation. RepoTransAgent systematically decomposes the translation process into specialized subtasks-context retrieval, dynamic prompt construction, and iterative code refinement-each handled by dedicated agents. Our approach leverages retrieval-augmented generation (RAG) for contextual information gathering, employs adaptive prompts tailored to varying repository scenarios, and introduces a reflection-based mechanism for systematic error correction. We evaluate RepoTransAgent on hundreds of Java-C# translation pairs from six popular open-source projects. Experimental results demonstrate that RepoTransAgent significantly outperforms state-of-the-art baselines in both compile and pass rates. Specifically, RepoTransAgent achieves up to 55.34% compile rate and 45.84% pass rate. Comprehensive analysis confirms the robustness and generalizability of RepoTransAgent across different LLMs, establishing its effectiveness for real-world repository-aware code translation.

[Arxiv](https://arxiv.org/abs/2508.17720)