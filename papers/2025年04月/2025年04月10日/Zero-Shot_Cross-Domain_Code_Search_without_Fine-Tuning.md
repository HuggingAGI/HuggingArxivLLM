# 无需微调的零样本跨域代码搜索

发布时间：2025年04月10日

`LLM应用

论文摘要：代码搜索的目标是根据自然语言查询检索出语义相关的代码片段。虽然预训练语言模型（PLMs）在这一任务中表现出色，但它们在跨领域场景中往往表现不佳，通常需要进行昂贵的微调或在零样本设置下性能下降。当前，RAPID 是唯一有效的零样本跨领域代码搜索方法，它通过生成合成数据用于模型微调。尽管 RAPID 有效，但其需要大量计算资源进行微调，并且需要为每个领域维护专门的模型，因此亟需一种无需微调的零样本跨领域代码搜索方法。

解决零样本跨领域代码搜索的关键在于弥合各领域之间的差距。在本研究中，我们将代码搜索的查询-代码匹配过程分解为两个更简单的任务：查询-注释匹配和代码-代码匹配。我们的实证研究表明，查询-代码、查询-注释和代码-代码匹配这三种模式在零样本跨领域设置中具有很强的互补性。基于这一发现，我们提出了 CodeBridge，这是一种无需微调的零样本跨领域代码搜索方法。具体而言，CodeBridge 使用大型语言模型（LLMs）生成注释和伪代码，然后通过基于 PLM 的相似性评分和基于采样的融合，结合查询-代码、查询-注释和代码-代码匹配。实验结果表明，我们的方法在 MRR（平均倒数排名）方面分别比最先进的 PLM 基础代码搜索方法 CoCoSoDa 和 UniXcoder 高出 21.4% 和 24.9%，在三个数据集上表现更优。此外，我们的方法还优于或与需要昂贵微调的零样本跨领域代码搜索方法 RAPID 的结果相当。

LLM应用` `代码搜索` `软件工程`

> Zero-Shot Cross-Domain Code Search without Fine-Tuning

# 摘要

> 代码搜索的目标是根据自然语言查询检索出语义相关的代码片段。虽然预训练语言模型（PLMs）在这一任务中表现出色，但它们在跨领域场景中往往表现不佳，通常需要进行昂贵的微调或在零样本设置下性能下降。当前，RAPID 是唯一有效的零样本跨领域代码搜索方法，它通过生成合成数据用于模型微调。尽管 RAPID 有效，但其需要大量计算资源进行微调，并且需要为每个领域维护专门的模型，因此亟需一种无需微调的零样本跨领域代码搜索方法。

解决零样本跨领域代码搜索的关键在于弥合各领域之间的差距。在本研究中，我们将代码搜索的查询-代码匹配过程分解为两个更简单的任务：查询-注释匹配和代码-代码匹配。我们的实证研究表明，查询-代码、查询-注释和代码-代码匹配这三种模式在零样本跨领域设置中具有很强的互补性。基于这一发现，我们提出了 CodeBridge，这是一种无需微调的零样本跨领域代码搜索方法。具体而言，CodeBridge 使用大型语言模型（LLMs）生成注释和伪代码，然后通过基于 PLM 的相似性评分和基于采样的融合，结合查询-代码、查询-注释和代码-代码匹配。实验结果表明，我们的方法在 MRR（平均倒数排名）方面分别比最先进的 PLM 基础代码搜索方法 CoCoSoDa 和 UniXcoder 高出 21.4% 和 24.9%，在三个数据集上表现更优。此外，我们的方法还优于或与需要昂贵微调的零样本跨领域代码搜索方法 RAPID 的结果相当。


> Code search aims to retrieve semantically relevant code snippets for natural language queries. While pre-trained language models (PLMs) have shown remarkable performance in this task, they struggle in cross-domain scenarios, often requiring costly fine-tuning or facing performance drops in zero-shot settings. RAPID, which generates synthetic data for model fine-tuning, is currently the only effective method for zero-shot cross-domain code search. Despite its effectiveness, RAPID demands substantial computational resources for fine-tuning and needs to maintain specialized models for each domain, underscoring the need for a zero-shot, fine-tuning-free approach for cross-domain code search.
  The key to tackling zero-shot cross-domain code search lies in bridging the gaps among domains. In this work, we propose to break the query-code matching process of code search into two simpler tasks: query-comment matching and code-code matching. Our empirical study reveals the strong complementarity among the three matching schemas in zero-shot cross-domain settings, i.e., query-code, query-comment, and code-code matching. Based on the findings, we propose CodeBridge, a zero-shot, fine-tuning-free approach for cross-domain code search. Specifically, CodeBridge uses Large Language Models (LLMs) to generate comments and pseudo-code, then combines query-code, query-comment, and code-code matching via PLM-based similarity scoring and sampling-based fusion. Experimental results show that our approach outperforms the state-of-the-art PLM-based code search approaches, i.e., CoCoSoDa and UniXcoder, by an average of 21.4% and 24.9% in MRR, respectively, across three datasets. Our approach also yields results that are better than or comparable to those of the zero-shot cross-domain code search approach RAPID, which requires costly fine-tuning.

[Arxiv](https://arxiv.org/abs/2504.07740)