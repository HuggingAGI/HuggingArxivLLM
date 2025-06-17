# 结合大型语言模型的知识图谱融合，实现准确且可解释的制造流程规划

发布时间：2025年06月15日

`LLM应用` `机械加工`

> Knowledge Graph Fusion with Large Language Models for Accurate, Explainable Manufacturing Process Planning

# 摘要

> 在计算机数字控制（CNC）加工中，精准的工艺规划要求对刀具选择、进给速度配对以及多轴路径进行快速且上下文感知的决策，这给工程师从设计规范到最终零件检验带来了巨大的认知和程序负担。传统的基于规则的计算机辅助工艺规划和知识工程外壳将专业知识固化为静态表格，这在处理未见的拓扑结构、新颖的材料状态、变化的成本-质量-可持续性权重或车间限制（如工具不可用和能源上限）时变得有限。大型语言模型（LLMs）承诺为任务提供灵活的指令驱动推理，但它们经常捏造数值并提供无来源的信息。我们提出了增强检索知识网络的搜索与合成（ARKNESS），这是一个端到端的框架，结合零样本知识图谱（KG）构建与检索增强生成，为CNC工艺规划提供可验证且数值精确的答案。ARKNESS（1）能够自动从异构加工文档、G代码注释和供应商数据表中提炼出增强的三元组和多关系图，无需人工标注；（2）将任何本地LLM与一个检索器相结合，该检索器注入回答查询所需的最小证据链接子图。在涵盖刀具尺寸和进给速度优化的155个行业精选问题上进行基准测试，轻量级的30亿参数Llama-3通过ARKNESS增强后，与GPT-4的准确性相匹配，同时在多项选择题准确率上提高了25个百分点，在F1上提高了22.4个百分点，在开放回答的ROUGE-L上提高了8.1倍。

> Precision process planning in Computer Numerical Control (CNC) machining demands rapid, context-aware decisions on tool selection, feed-speed pairs, and multi-axis routing, placing immense cognitive and procedural burdens on engineers from design specification through final part inspection. Conventional rule-based computer-aided process planning and knowledge-engineering shells freeze domain know-how into static tables, which become limited when dealing with unseen topologies, novel material states, shifting cost-quality-sustainability weightings, or shop-floor constraints such as tool unavailability and energy caps. Large language models (LLMs) promise flexible, instruction-driven reasoning for tasks but they routinely hallucinate numeric values and provide no provenance. We present Augmented Retrieval Knowledge Network Enhanced Search & Synthesis (ARKNESS), the end-to-end framework that fuses zero-shot Knowledge Graph (KG) construction with retrieval-augmented generation to deliver verifiable, numerically exact answers for CNC process planning. ARKNESS (1) automatically distills heterogeneous machining documents, G-code annotations, and vendor datasheets into augmented triple, multi-relational graphs without manual labeling, and (2) couples any on-prem LLM with a retriever that injects the minimal, evidence-linked subgraph needed to answer a query. Benchmarked on 155 industry-curated questions spanning tool sizing and feed-speed optimization, a lightweight 3B-parameter Llama-3 augmented by ARKNESS matches GPT-4o accuracy while achieving a +25 percentage point gain in multiple-choice accuracy, +22.4 pp in F1, and 8.1x ROUGE-L on open-ended responses.

[Arxiv](https://arxiv.org/abs/2506.13026)