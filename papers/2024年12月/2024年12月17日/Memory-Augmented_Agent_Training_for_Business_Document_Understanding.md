# 用于商业文档理解的内存增强代理训练

发布时间：2024年12月17日

`LLM应用` `企业业务`

> Memory-Augmented Agent Training for Business Document Understanding

# 摘要

> 传统企业在处理业务文档时遭遇重大挑战，像从发票中提取运输参考这类任务，尽管在物流运作中至关重要，却大多仍靠人工完成。虽然大型语言模型带来了自动化的可能，但直接应用于专业业务领域，效果往往不尽人意。我们推出了 Matrix（通过推理和迭代探索进行内存增强的代理训练）这一全新范式，能让 LLM 代理通过经验驱动的内存优化和迭代学习逐步积累领域专长。为验证此方法，我们与全球最大的物流公司之一合作，创建了通用业务语言格式的发票文档数据集，重点开展运输参考提取任务。实验显示，Matrix 比单个 LLM 的表现高出 30.3%，比普通 LLM 代理高出 35.2%。我们进一步分析优化系统的指标，发现代理系统所需的 API 调用更少，成本更低，平均能分析更长的文档。我们的方法通过在文档处理任务中进行系统的内存增强，为将通用 LLM 转化为专业业务工具开辟了新途径。

> Traditional enterprises face significant challenges in processing business documents, where tasks like extracting transport references from invoices remain largely manual despite their crucial role in logistics operations. While Large Language Models offer potential automation, their direct application to specialized business domains often yields unsatisfactory results. We introduce Matrix (Memory-Augmented agent Training through Reasoning and Iterative eXploration), a novel paradigm that enables LLM agents to progressively build domain expertise through experience-driven memory refinement and iterative learning. To validate this approach, we collaborate with one of the world's largest logistics companies to create a dataset of Universal Business Language format invoice documents, focusing on the task of transport reference extraction. Experiments demonstrate that Matrix outperforms prompting a single LLM by 30.3%, vanilla LLM agent by 35.2%. We further analyze the metrics of the optimized systems and observe that the agent system requires less API calls, fewer costs and can analyze longer documents on average. Our methods establish a new approach to transform general-purpose LLMs into specialized business tools through systematic memory enhancement in document processing tasks.

[Arxiv](https://arxiv.org/abs/2412.15274)