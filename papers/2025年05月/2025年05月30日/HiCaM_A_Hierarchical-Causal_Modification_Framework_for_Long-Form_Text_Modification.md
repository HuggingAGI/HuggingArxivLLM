# HiCaM: 专为长文本修改设计的分层因果框架

发布时间：2025年05月30日

`LLM应用

理由：这篇论文探讨了大型语言模型在长文本修改任务中的应用，提出了一种新的分层因果修改框架HiCaM，并通过实验验证了其有效性。因此，它属于LLM应用类别。` `文本生成`

> HiCaM: A Hierarchical-Causal Modification Framework for Long-Form Text Modification

# 摘要

> 大型语言模型（LLMs）在多个领域取得了显著成功。然而，在处理长文本修改任务时，它们仍然面临两大主要问题：（1）通过不恰当的修改或总结无关内容，产生不需要的修改；（2）未能对隐含相关但对保持文档连贯性至关重要的段落进行必要的修改。为了解决这些问题，我们提出了一种名为HiCaM的分层因果修改框架，该框架通过分层摘要树和因果图进行操作。此外，为了评估HiCaM，我们从多个基准测试中提取了一个跨领域数据集，为评估其有效性提供了资源。在该数据集上的全面评估表明，与强大的LLMs相比，HiCaM有显著改进，我们的方法达到了79.50%的胜率。这些结果突显了我们方法的全面性，展示了在多个模型和领域中持续的性能提升。

> Large Language Models (LLMs) have achieved remarkable success in various domains. However, when handling long-form text modification tasks, they still face two major problems: (1) producing undesired modifications by inappropriately altering or summarizing irrelevant content, and (2) missing necessary modifications to implicitly related passages that are crucial for maintaining document coherence. To address these issues, we propose HiCaM, a Hierarchical-Causal Modification framework that operates through a hierarchical summary tree and a causal graph. Furthermore, to evaluate HiCaM, we derive a multi-domain dataset from various benchmarks, providing a resource for assessing its effectiveness. Comprehensive evaluations on the dataset demonstrate significant improvements over strong LLMs, with our method achieving up to a 79.50\% win rate. These results highlight the comprehensiveness of our approach, showing consistent performance improvements across multiple models and domains.

[Arxiv](https://arxiv.org/abs/2505.24319)