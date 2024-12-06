# PoTable：如同人类分析师般在基于表的推理中进行标准编程

发布时间：2024年12月05日

`LLM应用` `表格推理` `人工智能`

> PoTable: Programming Standardly on Table-based Reasoning Like a Human Analyst

# 摘要

> 基于表格的推理备受关注，尤其是与大型语言模型（LLM）的融合，这彻底变革了常规推理模式。众多基于 LLM 的研究引入了符号工具（如数据库、Python）作为助手，以增强人类在结构化表格理解和复杂算术运算方面的能力。然而，这些研究在运用符号工具模拟人类认知行为时仍有待完善，因为它们存在非标准逻辑拆分和操作池受限的问题。在本研究中，我们提出了 PoTable 这一新颖的基于表格的推理方法，它模拟人类表格分析师，将 Python 解释器作为实时执行器，并搭配基于 LLM 的操作规划器和代码生成器。具体而言，PoTable 遵循类人的逻辑阶段拆分，将操作池拓展至无任何约束的开放世界空间。通过在各个不同阶段进行规划和执行，PoTable 规范地完成了整个推理过程，生成了出色的推理结果以及高度准确、逐步注释且完全可执行的程序。由此，PoTable 的有效性和可解释性得以充分彰显。在两个骨干网上针对来自两个公共基准的三个评估数据集开展的大量实验，展现了我们方法的卓越性能。特别是，基于 GPT 的 PoTable 在所有评估数据集上的绝对准确率比第二名高出 4%以上。

> Table-based reasoning has garnered substantial research interest, particularly in its integration with Large Language Model (LLM) which has revolutionized the general reasoning paradigm. Numerous LLM-based studies introduce symbolic tools (e.g., databases, Python) as assistants to extend human-like abilities in structured table understanding and complex arithmetic computations. However, these studies can be improved better in simulating human cognitive behavior when using symbolic tools, as they still suffer from limitations of non-standard logical splits and constrained operation pools. In this study, we propose PoTable as a novel table-based reasoning method that simulates a human tabular analyst, which integrates a Python interpreter as the real-time executor accompanied by an LLM-based operation planner and code generator. Specifically, PoTable follows a human-like logical stage split and extends the operation pool into an open-world space without any constraints. Through planning and executing in each distinct stage, PoTable standardly completes the entire reasoning process and produces superior reasoning results along with highly accurate, steply commented and completely executable programs. Accordingly, the effectiveness and explainability of PoTable are fully demonstrated. Extensive experiments over three evaluation datasets from two public benchmarks on two backbones show the outstanding performance of our approach. In particular, GPT-based PoTable achieves over 4% higher absolute accuracy than runner-ups on all evaluation datasets.

[Arxiv](https://arxiv.org/abs/2412.04272)