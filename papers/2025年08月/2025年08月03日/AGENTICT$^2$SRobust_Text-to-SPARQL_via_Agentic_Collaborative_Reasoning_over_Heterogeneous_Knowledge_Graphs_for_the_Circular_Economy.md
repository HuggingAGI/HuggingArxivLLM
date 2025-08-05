# # AGENTICT$^2$S：面向循环经济的智能体协作推理驱动的鲁棒文本到SPARQL转换，基于异构知识图谱。

发布时间：2025年08月03日

`Agent` `知识图谱问答` `循环经济`

> AGENTICT$^2$S:Robust Text-to-SPARQL via Agentic Collaborative Reasoning over Heterogeneous Knowledge Graphs for the Circular Economy

# 摘要

> 异质知识图谱问答（KGQA）需要跨多种模式进行推理，处理不完整的对齐关系以及分散的数据来源。现有的文本到SPARQL方法依赖大规模特定领域的微调，或仅在单一图谱环境下运行，这限制了它们在低资源领域中的泛化能力，也难以处理跨多个图谱的查询。这些挑战在循环经济等领域的尤为突出，因为分类、流程和排放等方面的信息分散在独立管理的知识图谱（KGs）中。我们提出了AgenticT$^2$S，一个模块化框架，将KGQA分解为由专门代理管理的子任务，包括检索、查询生成和验证。调度器采用弱到强的对齐策略将子目标分配到不同图谱。双阶段验证器通过符号验证和反事实一致性检查来检测结构无效和语义不明确的查询。在真实循环经济KG上的实验表明，与最佳基线相比，AgenticT$^2$S将执行精度提升了17.3%，三元组级别F$_1$提升了25.4%，同时平均提示长度减少了46.4%。这些结果证明了基于代理的模式感知推理在可扩展KGQA中的优势，并通过强大的跨图推理支持可持续性领域的决策制定。

> Question answering over heterogeneous knowledge graphs (KGQA) involves reasoning across diverse schemas, incomplete alignments, and distributed data sources. Existing text-to-SPARQL approaches rely on large-scale domain-specific fine-tuning or operate within single-graph settings, limiting their generalizability in low-resource domains and their ability to handle queries spanning multiple graphs. These challenges are particularly relevant in domains such as the circular economy, where information about classifications, processes, and emissions is distributed across independently curated knowledge graphs (KGs). We present AgenticT$^2$S, a modular framework that decomposes KGQA into subtasks managed by specialized agents responsible for retrieval, query generation, and verification. A scheduler assigns subgoals to different graphs using weak-to-strong alignment strategies. A two-stage verifier detects structurally invalid and semantically underspecified queries through symbolic validation and counterfactual consistency checks. Experiments on real-world circular economy KGs demonstrate that AgenticT$^2$S improves execution accuracy by 17.3% and triple level F$_1$ by 25.4% over the best baseline, while reducing the average prompt length by 46.4%. These results demonstrate the benefits of agent-based schema-aware reasoning for scalable KGQA and support decision-making in sustainability domains through robust cross-graph reasoning.

[Arxiv](https://arxiv.org/abs/2508.01815)