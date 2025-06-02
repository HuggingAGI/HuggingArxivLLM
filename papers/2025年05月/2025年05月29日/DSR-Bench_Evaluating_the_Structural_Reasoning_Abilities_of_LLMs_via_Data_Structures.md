# DSR-Bench：借助数据结构评测大型语言模型的结构推理能力

发布时间：2025年05月29日

`LLM理论

理由：这篇论文专注于评估大型语言模型在结构化推理方面的表现，并引入了一个新的基准DSR-Bench。它探讨了模型在处理数据结构和推理任务中的能力，分析了现有模型的不足，属于对模型能力的理论分析和评估，因此归类为LLM理论。` `人工智能` `数据结构`

> DSR-Bench: Evaluating the Structural Reasoning Abilities of LLMs via Data Structures

# 摘要

> 大型语言模型（LLMs）在越来越多的现实任务中得到部署，这些任务本质上涉及数据操作。这些任务的核心要求之一是进行结构化推理，即理解并推理数据之间的关系。例如，客户请求需要时间顺序的安排，这可以通过队列等数据结构来表示。然而，现有的基准测试主要侧重于高层次的应用驱动型评估，但并未专门针对这一核心能力进行测试。为了解决这一空白，我们引入了DSR-Bench，这是一个通过数据结构评估大型语言模型结构化推理能力的新基准。数据结构为数据关系提供了可解释的表示形式。DSR-Bench包含20种数据结构、35种操作和4,140个问题实例，采用层次化组织方式，便于对推理限制进行细致分析。我们的评估流程完全自动化且具有确定性，消除了主观的人为或模型判断。其合成特性还确保了可扩展性，并最大限度地降低了数据污染的风险。我们对九种最先进的大型语言模型进行了基准测试。我们的分析表明，指令微调模型在处理基本的多属性和多跳推理时显得力不从心。此外，尽管推理导向的模型表现更佳，但它们在面对复杂和混合结构时仍较为脆弱，最佳模型在挑战子集中的平均得分仅为47%。至关重要的是，模型在处理多维数据和自然语言任务描述时表现不佳，凸显了在现实世界部署中存在关键差距。

> Large language models (LLMs) are increasingly deployed for real-world tasks that fundamentally involve data manipulation. A core requirement across these tasks is the ability to perform structural reasoning--that is, to understand and reason about data relationships. For example, customer requests require a temporal ordering, which can be represented by data structures such as queues. However, existing benchmarks primarily focus on high-level, application-driven evaluations without isolating this fundamental capability. To address this gap, we introduce DSR-Bench, a novel benchmark evaluating LLMs' structural reasoning capabilities through data structures, which provide interpretable representations of data relationships. DSR-Bench includes 20 data structures, 35 operations, and 4,140 problem instances, organized hierarchically for fine-grained analysis of reasoning limitations. Our evaluation pipeline is fully automated and deterministic, eliminating subjective human or model-based judgments. Its synthetic nature also ensures scalability and minimizes data contamination risks. We benchmark nine state-of-the-art LLMs. Our analysis shows that instruction-tuned models struggle with basic multi-attribute and multi-hop reasoning. Furthermore, while reasoning-oriented models perform better, they remain fragile on complex and hybrid structures, with the best model achieving an average score of only 47% on the challenge subset. Crucially, models often perform poorly on multi-dimensional data and natural language task descriptions, highlighting a critical gap for real-world deployment.

[Arxiv](https://arxiv.org/abs/2505.24069)