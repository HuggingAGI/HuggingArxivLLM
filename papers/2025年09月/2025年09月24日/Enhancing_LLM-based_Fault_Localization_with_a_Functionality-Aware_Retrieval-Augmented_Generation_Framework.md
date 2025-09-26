# 借助功能感知检索增强生成框架提升基于LLM的故障定位

发布时间：2025年09月24日

`RAG` `基础理论`

> Enhancing LLM-based Fault Localization with a Functionality-Aware Retrieval-Augmented Generation Framework

# 摘要

> 故障定位（FL）是软件调试中至关重要却耗时费力的环节，核心目标是找出有缺陷的代码元素。尽管大型语言模型（LLMs）在故障定位领域展现出潜力，但面对复杂系统时，它们常因缺乏项目专属知识、难以驾驭大型项目而力不从心。为此，我们提出了FaR-Loc——一种将LLMs与检索增强生成（RAG）深度融合的新型框架，旨在提升方法级故障定位能力。FaR-Loc包含三大核心组件：LLM功能提取、语义密集检索和LLM重排序。具体而言，首先给定失败测试及其堆栈跟踪，LLM功能提取模块会生成简洁的自然语言描述来捕捉故障行为；接着，语义密集检索组件借助预训练的代码理解编码器，将功能描述（自然语言）与被覆盖方法（代码）嵌入共享语义空间，实现相似功能行为方法的精准检索；最后，LLM重排序模块根据上下文相关性对检索结果重新排序。在Defects4J基准测试集上的实验显示，FaR-Loc性能卓越：Top-1准确率较最先进的基于LLM的基线模型SoapFL和AutoFL分别提升14.6%和9.1%，Top-5准确率则分别提高19.2%和22.1%；它还无需重新训练，就在所有Top-N指标上超越了所有基于学习和频谱的传统基线模型。此外，我们发现融合代码结构的预训练代码嵌入模型（如UniXcoder）能显著优化故障定位效果，Top-1准确率最高可提升49.0%。最后，我们通过案例研究验证了FaR-Loc的有效性，并为其实际应用提供了实用见解。

> Fault localization (FL) is a critical but time-consuming task in software debugging, aiming to identify faulty code elements. While recent advances in large language models (LLMs) have shown promise for FL, they often struggle with complex systems due to the lack of project-specific knowledge and the difficulty of navigating large projects. To address these limitations, we propose FaR-Loc, a novel framework that enhances method-level FL by integrating LLMs with retrieval-augmented generation (RAG). FaR-Loc consists of three key components: LLM Functionality Extraction, Semantic Dense Retrieval, and LLM Re-ranking. First, given a failed test and its associated stack trace, the LLM Functionality Extraction module generates a concise natural language description that captures the failing behavior. Next, the Semantic Dense Retrieval component leverages a pre-trained code-understanding encoder to embed both the functionality description (natural language) and the covered methods (code) into a shared semantic space, enabling the retrieval of methods with similar functional behavior. Finally, the LLM Re-ranking module reorders the retrieved methods based on their contextual relevance. Our experiments on the widely used Defects4J benchmark show that FaR-Loc outperforms state-of-the-art LLM-based baselines SoapFL and AutoFL, by 14.6% and 9.1% in Top-1 accuracy, by 19.2% and 22.1% in Top-5 accuracy, respectively. It also surpasses all learning-based and spectrum-based baselines across all Top-N metrics without requiring re-training. Furthermore, we find that pre-trained code embedding models that incorporate code structure, such as UniXcoder, can significantly improve fault localization performance by up to 49.0% in Top-1 accuracy. Finally, we conduct a case study to illustrate the effectiveness of FaR-Loc and to provide insights for its practical application.

[Arxiv](https://arxiv.org/abs/2509.20552)