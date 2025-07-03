# 简单到令人惊讶的检索方法，助力挑战性与推理密集型基准测试

发布时间：2025年07月01日

`RAG` `问答系统` `数据集`

> Frustratingly Simple Retrieval Improves Challenging, Reasoning-Intensive Benchmarks

# 摘要

> 检索增强生成（RAG）主要应用于事实性问答等有限场景，而在需要复杂推理的基准测试中表现有限。针对这一现状，我们对现有观点提出了挑战，重点研究了MMLU、MMLU Pro、AGI Eval、GPQA和MATH等推理密集型基准测试。我们发现，以往研究中缺乏一个关键要素：一个与预训练数据规模相匹配的高质量、多样化、大规模网络数据集。为此，我们推出了CompactDS——一个单节点即可实现高检索准确性和亚秒级延迟的多样化、高质量、大规模网络数据集。我们的主要发现包括：（1）大部分网络内容可通过过滤去除而不影响覆盖范围，一个紧凑且高质量的子集已足够；（2）内存中的近似最近邻（ANN）检索与磁盘上的精确搜索相结合，可以在速度和召回率之间取得平衡。借助CompactDS，我们证明了一个简单的RAG流水线在所有基准测试和模型规模（8B至70B）上均实现了显著的性能提升，具体表现为MMLU提升10%，MMLU Pro提升33%，GPQA提升14%，MATH提升19%。单一数据源无法满足需求，凸显了数据源多样性的重要性（包括网络爬虫、精选数学内容、学术论文和教科书）。最后，我们展示了我们的内部数据集不仅能够匹敌Google Search等网络搜索引擎，还能超越最近提出的复杂基于代理的RAG系统——这一切都保持了简单性、可重复性和自洽性。我们公开了CompactDS和我们的检索流水线，以支持未来对基于检索的AI系统的研究。

> Retrieval-augmented Generation (RAG) has primarily been studied in limited settings, such as factoid question answering; more challenging, reasoning-intensive benchmarks have seen limited success from minimal RAG. In this work, we challenge this prevailing view on established, reasoning-intensive benchmarks: MMLU, MMLU Pro, AGI Eval, GPQA, and MATH. We identify a key missing component in prior work: a usable, web-scale datastore aligned with the breadth of pretraining data. To this end, we introduce CompactDS: a diverse, high-quality, web-scale datastore that achieves high retrieval accuracy and subsecond latency on a single-node. The key insights are (1) most web content can be filtered out without sacrificing coverage, and a compact, high-quality subset is sufficient; and (2) combining in-memory approximate nearest neighbor (ANN) retrieval and on-disk exact search balances speed and recall. Using CompactDS, we show that a minimal RAG pipeline achieves consistent accuracy improvements across all benchmarks and model sizes (8B--70B), with relative gains of 10% on MMLU, 33% on MMLU Pro, 14% on GPQA, and 19% on MATH. No single data source suffices alone, highlighting the importance of diversity of sources (web crawls, curated math, academic papers, textbooks). Finally, we show that our carefully designed in-house datastore matches or outperforms web search engines such as Google Search, as well as recently proposed, complex agent-based RAG systems--all while maintaining simplicity, reproducibility, and self-containment. We release CompactDS and our retrieval pipeline, supporting future research exploring retrieval-based AI systems.

[Arxiv](https://arxiv.org/abs/2507.01297)