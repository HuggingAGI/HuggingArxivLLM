# 大语言模型时代下，基于查询的KGQA系统在处理复杂和时间相关问题中的优势

发布时间：2025年07月16日

`LLM应用` `问答系统` `知识图谱`

> The benefits of query-based KGQA systems for complex and temporal questions in LLM era

# 摘要

> 大型语言模型在问答（QA）任务中表现优异，但在多跳推理和时间相关问题上仍显吃力。基于查询的知识图问答（KGQA）通过生成可执行查询而非直接提供答案，提供了一种模块化的替代方案。我们针对WikiData问答探索了多阶段查询框架，提出了一种多阶段方法，旨在提升在具有挑战性的多跳和时间基准测试中的性能。通过泛化和拒绝研究，我们评估了在多跳和时间问答数据集上的鲁棒性。此外，我们引入了一种新的基于CoT推理的实体链接和谓词匹配方法。实验结果表明，基于查询的多阶段KGQA框架在提升小型语言模型的多跳和时间问答性能方面具有潜力。代码和数据已开源：https://github.com/ar2max/NLDB-KGQA-System

> Large language models excel in question-answering (QA) yet still struggle with multi-hop reasoning and temporal questions. Query-based knowledge graph QA (KGQA) offers a modular alternative by generating executable queries instead of direct answers. We explore multi-stage query-based framework for WikiData QA, proposing multi-stage approach that enhances performance on challenging multi-hop and temporal benchmarks. Through generalization and rejection studies, we evaluate robustness across multi-hop and temporal QA datasets. Additionally, we introduce a novel entity linking and predicate matching method using CoT reasoning. Our results demonstrate the potential of query-based multi-stage KGQA framework for improving multi-hop and temporal QA with small language models. Code and data: https://github.com/ar2max/NLDB-KGQA-System

[Arxiv](https://arxiv.org/abs/2507.11954)