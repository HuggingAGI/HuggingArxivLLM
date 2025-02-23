# 事实还是猜测？大型语言模型医学知识的结构化单跳判断评测

发布时间：2025年02月20日

`RAG` `知识图谱`

> Fact or Guesswork? Evaluating Large Language Model's Medical Knowledge with Structured One-Hop Judgment

# 摘要

> 大型语言模型 (LLMs) 在各领域下游任务中广泛应用，但其直接回忆和应用事实性医学知识的能力仍有待探索。现有医学问答基准多关注复杂推理或多跳推理，难以单独评估 LLMs 的医学知识储备。鉴于医学应用的高风险性，错误信息可能带来严重后果，因此评估 LLMs 对基本医学事实的编码、保留和回忆能力至关重要。
    为弥补这一研究空白，我们推出了医学知识判断 (Medical Knowledge Judgment, MKJ) 数据集，专为衡量 LLMs 的单跳事实性医学知识而设计。该数据集基于统一医学语言系统 (UMLS) 构建，这是一个大规模的标准生物医学词汇和知识图谱存储库。我们将知识评估定义为二元判断任务，要求 LLMs 验证从可靠且结构化的知识来源中提取的医学陈述的正确性。
    实验结果表明，LLMs 在事实性医学知识的保留方面表现欠佳，尤其在罕见医学状况上存在显著差异。此外，LLMs 的校准能力不佳，常对错误答案过于自信。为解决这些问题，我们探索了检索增强生成 (retrieval-augmented generation)，证明其在提高事实准确性以及降低医学决策不确定性方面具有显著效果。

> Large language models (LLMs) have been widely adopted in various downstream task domains. However, their ability to directly recall and apply factual medical knowledge remains under-explored. Most existing medical QA benchmarks assess complex reasoning or multi-hop inference, making it difficult to isolate LLMs' inherent medical knowledge from their reasoning capabilities. Given the high-stakes nature of medical applications, where incorrect information can have critical consequences, it is essential to evaluate how well LLMs encode, retain, and recall fundamental medical facts.
  To bridge this gap, we introduce the Medical Knowledge Judgment, a dataset specifically designed to measure LLMs' one-hop factual medical knowledge. MKJ is constructed from the Unified Medical Language System (UMLS), a large-scale repository of standardized biomedical vocabularies and knowledge graphs. We frame knowledge assessment as a binary judgment task, requiring LLMs to verify the correctness of medical statements extracted from reliable and structured knowledge sources.
  Our experiments reveal that LLMs struggle with factual medical knowledge retention, exhibiting significant performance variance across different semantic categories, particularly for rare medical conditions. Furthermore, LLMs show poor calibration, often being overconfident in incorrect answers. To mitigate these issues, we explore retrieval-augmented generation, demonstrating its effectiveness in improving factual accuracy and reducing uncertainty in medical decision-making.

[Arxiv](https://arxiv.org/abs/2502.14275)