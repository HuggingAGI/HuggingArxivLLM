# # FinAgentBench：面向金融问答中智能体检索的基准数据集

发布时间：2025年09月06日

`LLM应用` `金融科技`

> FinAgentBench: A Benchmark Dataset for Agentic Retrieval in Financial Question Answering

# 摘要

> 在金融领域，准确的信息检索（IR）至关重要：投资者需从海量文档中识别关键信息。但传统检索方法（无论稀疏还是密集型）在准确性上常不尽如人意——这既需捕捉语义相似性，还需对文档结构和领域知识做细粒度推理。近年来，大型语言模型（LLMs）的突破为“多步推理检索”开辟了新可能：模型通过迭代推理判断信息与查询的相关性，进而对段落排序。然而，金融领域尚缺乏评估此类能力的基准。为此，我们推出首个大规模金融多步推理检索基准FinAgentBench（我们称之为“智能体检索”）。该基准含3429个标普100上市公司的专家标注样本，聚焦两大能力评估：（1）从候选类型中识别最相关文档；（2）在选定文档中定位关键段落。我们的评估框架将这两步推理明确分离，以破解上下文限制；这种设计为理解金融领域“检索型LLM”行为提供了定量依据。通过测试一系列最先进模型，我们进一步证实：针对性微调可显著提升智能体检索性能。该基准为研究金融复杂任务中检索型LLM的行为奠定了基础。

> Accurate information retrieval (IR) is critical in the financial domain, where investors must identify relevant information from large collections of documents. Traditional IR methods-whether sparse or dense-often fall short in retrieval accuracy, as it requires not only capturing semantic similarity but also performing fine-grained reasoning over document structure and domain-specific knowledge. Recent advances in large language models (LLMs) have opened up new opportunities for retrieval with multi-step reasoning, where the model ranks passages through iterative reasoning about which information is most relevant to a given query. However, there exists no benchmark to evaluate such capabilities in the financial domain. To address this gap, we introduce FinAgentBench, the first large-scale benchmark for evaluating retrieval with multi-step reasoning in finance -- a setting we term agentic retrieval. The benchmark consists of 3,429 expert-annotated examples on S&P-100 listed firms and assesses whether LLM agents can (1) identify the most relevant document type among candidates, and (2) pinpoint the key passage within the selected document. Our evaluation framework explicitly separates these two reasoning steps to address context limitations. This design enables to provide a quantitative basis for understanding retrieval-centric LLM behavior in finance. We evaluate a suite of state-of-the-art models and further demonstrated how targeted fine-tuning can significantly improve agentic retrieval performance. Our benchmark provides a foundation for studying retrieval-centric LLM behavior in complex, domain-specific tasks for finance.

[Arxiv](https://arxiv.org/abs/2508.14052)