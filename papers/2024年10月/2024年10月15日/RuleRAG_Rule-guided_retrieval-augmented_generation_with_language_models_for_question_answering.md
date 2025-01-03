# RuleRAG: 规则引导的检索增强生成与语言模型在问答中的应用

发布时间：2024年10月15日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）框架的改进，特别是通过引入符号规则来指导检索器和生成器的工作。论文的核心内容围绕如何通过规则增强RAG框架的性能，并提出了具体的改进方法（如RuleRAG-ICL和RuleRAG-FT）。因此，这篇论文应归类为RAG。` `问答系统` `知识管理`

> RuleRAG: Rule-guided retrieval-augmented generation with language models for question answering

# 摘要

> 检索增强生成（RAG）框架在知识密集型问答（QA）任务中展现了巨大潜力，它通过检索外部语料库并基于增强的上下文生成答案。然而，现有方法仅关注查询本身，既未指定检索器的检索偏好，也未告知生成器如何参考检索到的文档生成答案，这对QA性能构成了挑战。为此，我们提出了基于规则指导的检索增强生成（RuleRAG-ICL），通过引入符号规则作为上下文学习的示范，指导检索器在规则方向上检索逻辑相关的文档，并统一指导生成器根据同一组规则生成答案。此外，查询和规则的组合还可用于监督微调数据，更新检索器和生成器（RuleRAG-FT），以提升基于规则的指令跟随能力，从而检索到更多支持性结果并生成更可接受的答案。为强调规则的归因，我们构建了五个规则感知的QA基准，包括三个时间相关和两个静态场景，并为RuleRAG配备了多种检索器和生成器。实验表明，无需训练的RuleRAG-ICL在五个基准上平均提高了+89.2%的Recall@10检索质量和+103.1%的精确匹配生成准确率，而进一步微调的RuleRAG-FT则持续带来了更显著的性能提升。广泛分析表明，RuleRAG在检索文档数量增加时具有良好的扩展性，并对未训练规则表现出泛化能力。

> Retrieval-augmented generation (RAG) framework has shown promising potential in knowledge-intensive question answering (QA) by retrieving external corpus and generating based on augmented context. However, existing approaches only consider the query itself, neither specifying the retrieval preferences for the retrievers nor informing the generators of how to refer to the retrieved documents for the answers, which poses a significant challenge to the QA performance. To address these issues, we propose Rule-Guided Retrieval-Augmented Generation with LMs, which explicitly introduces symbolic rules as demonstrations for in-context learning (RuleRAG-ICL) to guide retrievers to retrieve logically related documents in the directions of rules and uniformly guide generators to generate answers attributed by the guidance of the same set of rules. Moreover, the combination of queries and rules can be further used as supervised fine-tuning data to update retrievers and generators (RuleRAG-FT) to achieve better rule-based instruction following capability, leading to retrieve more supportive results and generate more acceptable answers. To emphasize the attribution of rules, we construct five rule-aware QA benchmarks, including three temporal and two static scenarios, and equip RuleRAG with several kinds of retrievers and generators. Experiments demonstrate that training-free RuleRAG-ICL effectively improves the retrieval quality of +89.2% in Recall@10 scores and generation accuracy of +103.1% in exact match scores over standard RAG on average across the five benchmarks, and further fine-tuned RuleRAG-FT consistently yields more significant performance enhancement. Extensive analyses indicate that RuleRAG scales well with increasing numbers of retrieved documents and exhibits generalization ability for untrained rules.

[Arxiv](https://arxiv.org/abs/2410.22353)