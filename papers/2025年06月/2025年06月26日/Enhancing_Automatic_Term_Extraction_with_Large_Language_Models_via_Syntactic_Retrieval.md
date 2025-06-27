# 基于大型语言模型的自动术语提取：通过句法检索助力提升性能

发布时间：2025年06月26日

`LLM应用` `机器翻译`

> Enhancing Automatic Term Extraction with Large Language Models via Syntactic Retrieval

# 摘要

> 术语自动提取（ATE）专注于识别对机器翻译和信息检索等下游任务至关重要的领域特定表达。尽管大型语言模型（LLMs）在各种NLP任务上取得了显著进展，但其在ATE方面的潜力尚未得到充分探索。我们提出了一种基于检索的提示策略，在少量样本的情况下，根据句法而非语义相似性选择示例。这种句法检索方法具有领域无关性，并为捕捉术语边界提供了更可靠的指导。我们在同一领域和跨领域设置下评估了该方法，分析了查询句子与其检索到的示例之间的词汇重叠如何影响性能。在三个专门的ATE基准上进行的实验表明，句法检索提高了F1分数。这些发现强调了在将LLMs适应术语提取任务时，句法线索的重要性。

> Automatic Term Extraction (ATE) identifies domain-specific expressions that are crucial for downstream tasks such as machine translation and information retrieval. Although large language models (LLMs) have significantly advanced various NLP tasks, their potential for ATE has scarcely been examined. We propose a retrieval-based prompting strategy that, in the few-shot setting, selects demonstrations according to \emph{syntactic} rather than semantic similarity. This syntactic retrieval method is domain-agnostic and provides more reliable guidance for capturing term boundaries. We evaluate the approach in both in-domain and cross-domain settings, analyzing how lexical overlap between the query sentence and its retrieved examples affects performance. Experiments on three specialized ATE benchmarks show that syntactic retrieval improves F1-score. These findings highlight the importance of syntactic cues when adapting LLMs to terminology-extraction tasks.

[Arxiv](https://arxiv.org/abs/2506.21222)