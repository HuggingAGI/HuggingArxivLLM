# # StructSense：一个通用任务的智能体框架，用于结构化信息抽取，并实现人在回路中的评估与基准测试。

发布时间：2025年07月04日

`LLM应用

摘要讨论了大型语言模型（LLMs）在结构化信息抽取中的应用，并提出了一种新的框架StructSense，用于在特定领域和跨任务中提升性能。这属于将LLMs应用于具体任务，因此归类为LLM应用。` `科学研究` `结构化信息抽取`

> STRUCTSENSE: A Task-Agnostic Agentic Framework for Structured Information Extraction with Human-In-The-Loop Evaluation and Benchmarking

# 摘要

> 从非结构化文本中提取结构化信息的能力，对于加速科学研究和知识整合至关重要。大型语言模型（LLMs）在包括结构化信息抽取在内的多种自然语言处理任务中表现卓越。然而，面对需要专业知识和细致理解的特定领域情境，其效果往往受限。此外，现有基于LLMs的方法通常在跨任务和跨领域迁移方面表现不佳，限制了其扩展性和适应性。为了解决这些问题，我们推出了StructSense——一个基于LLMs的模块化、任务无关、开源的结构化信息抽取框架。通过将领域特定的符号知识编码到本体中，StructSense能够更有效地处理复杂的领域内容。它还通过自我评估的裁判形成反馈循环，实现迭代优化，并集成了人机协作机制，以确保质量和验证。我们证明，StructSense能够克服领域敏感性限制和跨任务通用性不足的问题，如其在多样化神经科学信息抽取任务中的应用所示。


> The ability to extract structured information from unstructured sources-such as free-text documents and scientific literature-is critical for accelerating scientific discovery and knowledge synthesis. Large Language Models (LLMs) have demonstrated remarkable capabilities in various natural language processing tasks, including structured information extraction. However, their effectiveness often diminishes in specialized, domain-specific contexts that require nuanced understanding and expert-level domain knowledge. In addition, existing LLM-based approaches frequently exhibit poor transferability across tasks and domains, limiting their scalability and adaptability. To address these challenges, we introduce StructSense, a modular, task-agnostic, open-source framework for structured information extraction built on LLMs. StructSense is guided by domain-specific symbolic knowledge encoded in ontologies, enabling it to navigate complex domain content more effectively. It further incorporates agentic capabilities through self-evaluative judges that form a feedback loop for iterative refinement, and includes human-in-the-loop mechanisms to ensure quality and validation. We demonstrate that StructSense can overcome both the limitations of domain sensitivity and the lack of cross-task generalizability, as shown through its application to diverse neuroscience information extraction tasks.

[Arxiv](https://arxiv.org/abs/2507.03674)