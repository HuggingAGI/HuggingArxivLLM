# FIND：基于细粒度信息密度的自适应检索增强生成方法，助力疾病诊断

发布时间：2025年02月20日

`RAG`

> FIND: Fine-grained Information Density Guided Adaptive Retrieval-Augmented Generation for Disease Diagnosis

# 摘要

> 检索增强的大语言模型（LLMs）通过整合外部知识，在临床诊断等医学领域展现了卓越性能。然而，现有的RAG方法在评估任务难度和制定检索决策方面存在不足，难以满足临床对效率与准确性的平衡要求。为此，我们提出了FIND（	extbf{F}ine-grained 	extbf{In}formation 	extbf{D}ensity Guided Adaptive RAG），一个专为提升疾病诊断场景下RAG可靠性而设计的创新框架。FIND通过细粒度自适应控制模块，根据输入信息密度判断是否需要检索。优化检索流程并引入知识过滤模块后，FIND使检索结果更贴合临床需求。实验结果表明，在三个中文电子病历数据集上，FIND显著超越了多种基线方法，充分证明了其在临床诊断任务中的有效性。

> Retrieval-Augmented Large Language Models (LLMs), which integrate external knowledge into LLMs, have shown remarkable performance in various medical domains, including clinical diagnosis. However, existing RAG methods struggle to effectively assess task difficulty to make retrieval decisions, thereby failing to meet the clinical requirements for balancing efficiency and accuracy. So in this paper, we propose FIND (\textbf{F}ine-grained \textbf{In}formation \textbf{D}ensity Guided Adaptive RAG), a novel framework that improves the reliability of RAG in disease diagnosis scenarios. FIND incorporates a fine-grained adaptive control module to determine whether retrieval is necessary based on the information density of the input. By optimizing the retrieval process and implementing a knowledge filtering module, FIND ensures that the retrieval is better suited to clinical scenarios. Experiments on three Chinese electronic medical record datasets demonstrate that FIND significantly outperforms various baseline methods, highlighting its effectiveness in clinical diagnosis tasks.

[Arxiv](https://arxiv.org/abs/2502.14614)