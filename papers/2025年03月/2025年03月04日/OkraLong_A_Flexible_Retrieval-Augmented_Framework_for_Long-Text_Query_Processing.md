# OkraLong：一个灵活的检索增强框架，专为处理长文本查询而设计。

发布时间：2025年03月04日

`LLM应用` `财务分析`

> OkraLong: A Flexible Retrieval-Augmented Framework for Long-Text Query Processing

# 摘要

> 大型语言模型（LLMs）在处理长文本查询时面临诸多挑战，尤其在企业文档分析和财务报告理解等场景中表现明显。传统解决方案采用长上下文处理或检索增强生成（RAG），但往往面临高昂的输入成本或信息不全的问题。近期进展虽然采用了上下文压缩和动态检索循环，但仍然难以避免关键细节的损失或迭代成本的增加。为了解决这些难题，我们提出了OkraLong，一个全新的灵活优化处理流程的框架。与以往的静态或粗粒度自适应策略不同，OkraLong通过分析器、组织器和执行器这三个协同工作的组件实现了细粒度编排。分析器负责表征任务状态，指导组织器动态调度工作流程；执行器则负责具体执行并生成最终答案。实验结果表明，OkraLong不仅显著提升了回答的准确性，还在多种数据集上实现了成本效益的优化。

> Large Language Models (LLMs) encounter challenges in efficiently processing long-text queries, as seen in applications like enterprise document analysis and financial report comprehension. While conventional solutions employ long-context processing or Retrieval-Augmented Generation (RAG), they suffer from prohibitive input expenses or incomplete information. Recent advancements adopt context compression and dynamic retrieval loops, but still sacrifice critical details or incur iterative costs.To address these limitations, we propose OkraLong, a novel framework that flexibly optimizes the entire processing workflow. Unlike prior static or coarse-grained adaptive strategies, OkraLong adopts fine-grained orchestration through three synergistic components: analyzer, organizer and executor. The analyzer characterizes the task states, which guide the organizer in dynamically scheduling the workflow. The executor carries out the execution and generates the final answer. Experimental results demonstrate that OkraLong not only enhances answer accuracy but also achieves cost-effectiveness across a variety of datasets.

[Arxiv](https://arxiv.org/abs/2503.02603)