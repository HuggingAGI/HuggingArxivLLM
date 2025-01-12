# Search-o1: 智能体搜索增强的大型推理模型

发布时间：2025年01月09日

`RAG

理由：这篇论文提出了一个名为Search-o1的框架，通过代理检索增强生成（RAG）机制和文档内推理模块来增强大型推理模型（LRMs）。RAG机制是论文的核心内容，旨在通过动态检索外部知识来增强模型的推理能力。因此，这篇论文应归类为RAG。` `人工智能` `推理系统`

> Search-o1: Agentic Search-Enhanced Large Reasoning Models

# 摘要

> # 摘要
OpenAI-o1 等大型推理模型（LRMs）通过大规模强化学习展现了强大的逐步推理能力。然而，其推理过程常因知识不足而陷入不确定性和潜在错误。为此，我们提出了 	extbf{Search-o1} 框架，通过代理检索增强生成（RAG）机制和文档内推理模块来增强 LRMs。Search-o1 将代理搜索工作流融入推理过程，使 LRMs 在遇到不确定知识点时能动态检索外部知识。此外，针对检索文档的冗长性，我们设计了独立的文档内推理模块，在将信息注入推理链前进行深度分析，减少噪声并保持推理连贯性。在科学、数学、编码等复杂推理任务及六个开放域 QA 基准测试中，Search-o1 表现优异。这一方法提升了 LRMs 在复杂推理任务中的可信度和适用性，为构建更可靠、多功能的智能系统奠定了基础。代码已开源：url{https://github.com/sunnynexus/Search-o1}。

> Large reasoning models (LRMs) like OpenAI-o1 have demonstrated impressive long stepwise reasoning capabilities through large-scale reinforcement learning. However, their extended reasoning processes often suffer from knowledge insufficiency, leading to frequent uncertainties and potential errors. To address this limitation, we introduce \textbf{Search-o1}, a framework that enhances LRMs with an agentic retrieval-augmented generation (RAG) mechanism and a Reason-in-Documents module for refining retrieved documents. Search-o1 integrates an agentic search workflow into the reasoning process, enabling dynamic retrieval of external knowledge when LRMs encounter uncertain knowledge points. Additionally, due to the verbose nature of retrieved documents, we design a separate Reason-in-Documents module to deeply analyze the retrieved information before injecting it into the reasoning chain, minimizing noise and preserving coherent reasoning flow. Extensive experiments on complex reasoning tasks in science, mathematics, and coding, as well as six open-domain QA benchmarks, demonstrate the strong performance of Search-o1. This approach enhances the trustworthiness and applicability of LRMs in complex reasoning tasks, paving the way for more reliable and versatile intelligent systems. The code is available at \url{https://github.com/sunnynexus/Search-o1}.

[Arxiv](https://arxiv.org/abs/2501.05366)