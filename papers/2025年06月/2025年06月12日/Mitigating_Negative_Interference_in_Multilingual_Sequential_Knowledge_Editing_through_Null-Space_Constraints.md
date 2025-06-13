# 借助零空间约束减轻多语言知识编辑中的负面干扰

发布时间：2025年06月12日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在多语言知识更新方面的挑战，并提出了一种新的框架LangEdit来解决参数干扰问题。它主要涉及模型优化和理论层面的创新，因此属于LLM理论类别。` `多语言模型`

> Mitigating Negative Interference in Multilingual Sequential Knowledge Editing through Null-Space Constraints

# 摘要

> 在大型语言模型（LLMs）中，高效更新多语言知识同时保持跨语言一致的事实表示，仍是长期未解的难题。为每种语言独立部署编辑系统虽看似可行，但管理多个模型成本高昂。更高效的方法是将所有语言的知识更新整合到一个统一模型中。然而，跨语言的顺序编辑常导致破坏性参数干扰，显著降低多语言泛化能力和注入知识的准确性。

为解决这一挑战，我们提出了LangEdit（语言编辑框架），一个新颖的零空间约束框架，旨在精确隔离语言特定的知识更新。LangEdit的核心创新在于将每种语言的参数更新投影到之前更新子空间的正交补空间，这种方法在数学上保证了更新的独立性，同时保留了多语言泛化能力。

我们在三种模型架构、六种语言和四个下游任务上进行了全面评估，结果表明LangEdit有效缓解了参数干扰，并超越了现有的最先进的编辑方法。我们的结果凸显了其在实现LLMs中高效准确的多语言知识更新方面的潜力。代码可在https://github.com/VRCMF/LangEdit.git获取。

> Efficiently updating multilingual knowledge in large language models (LLMs), while preserving consistent factual representations across languages, remains a long-standing and unresolved challenge. While deploying separate editing systems for each language might seem viable, this approach incurs substantial costs due to the need to manage multiple models. A more efficient solution involves integrating knowledge updates across all languages into a unified model. However, performing sequential edits across languages often leads to destructive parameter interference, significantly degrading multilingual generalization and the accuracy of injected knowledge. To address this challenge, we propose LangEdit, a novel null-space constrained framework designed to precisely isolate language-specific knowledge updates. The core innovation of LangEdit lies in its ability to project parameter updates for each language onto the orthogonal complement of previous updated subspaces. This approach mathematically guarantees update independence while preserving multilingual generalization capabilities. We conduct a comprehensive evaluation across three model architectures, six languages, and four downstream tasks, demonstrating that LangEdit effectively mitigates parameter interference and outperforms existing state-of-the-art editing methods. Our results highlight its potential for enabling efficient and accurate multilingual knowledge updates in LLMs. The code is available at https://github.com/VRCMF/LangEdit.git.

[Arxiv](https://arxiv.org/abs/2506.10800)