# # REANIMATOR: 用提取和合成资源重焕检索测试集活力

发布时间：2025年04月10日

`RAG` `信息检索` `文档管理`

> REANIMATOR: Reanimate Retrieval Test Collections with Extracted and Synthetic Resources

# 摘要

> 检索测试集是评估信息检索系统的关键，但往往难以跨任务通用。为突破这一限制，我们推出REANIMATOR——一个灵活的框架，通过丰富现有测试集的提取和合成资源，实现其再利用。REANIMATOR解析PDF中的全文和机器可读表格，结合上下文信息，增强测试集。随后，它借助先进的大型语言模型生成合成的相关性标签。通过可选的人工介入步骤，可进一步验证提取和生成的资源。我们以焕然一新的TREC-COVID测试集为例，展示了REANIMATOR的潜力，揭示了检索增强生成系统的发展，并探讨了表格对其的影响。REANIMATOR不仅降低了成本，还让传统资源焕发新生，为新应用提供了更多可能。

> Retrieval test collections are essential for evaluating information retrieval systems, yet they often lack generalizability across tasks. To overcome this limitation, we introduce REANIMATOR, a versatile framework designed to enable the repurposing of existing test collections by enriching them with extracted and synthetic resources. REANIMATOR enhances test collections from PDF files by parsing full texts and machine-readable tables, as well as related contextual information. It then employs state-of-the-art large language models to produce synthetic relevance labels. Including an optional human-in-the-loop step can help validate the resources that have been extracted and generated. We demonstrate its potential with a revitalized version of the TREC-COVID test collection, showcasing the development of a retrieval-augmented generation system and evaluating the impact of tables on retrieval-augmented generation. REANIMATOR enables the reuse of test collections for new applications, lowering costs and broadening the utility of legacy resources.

[Arxiv](https://arxiv.org/abs/2504.07584)