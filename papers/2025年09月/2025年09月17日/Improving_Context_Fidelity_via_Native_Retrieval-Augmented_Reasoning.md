# 通过原生检索增强推理提升上下文保真度

发布时间：2025年09月17日

`RAG` `基础理论`

> Improving Context Fidelity via Native Retrieval-Augmented Reasoning

# 摘要

> 大型语言模型（LLMs）常受困于上下文保真度问题——基于给定信息回答问题时，答案往往前后矛盾。现有方法要么依赖昂贵的监督微调在回答后生成证据，要么训练模型进行网络搜索，却未必能提升给定上下文的利用率。为此，我们提出CARE——一种新颖的原生检索增强推理框架，它能让LLMs借助自身检索能力，在推理过程中显式整合上下文证据。该方法仅需少量标记证据数据，却能通过在推理链中策略性检索上下文标记，大幅提升检索精度与答案生成效果。在多个真实世界及反事实问答基准上的大量实验证实，我们的方法显著优于监督微调、传统检索增强生成方法及外部检索方案。这项研究为提升LLMs在知识密集型任务中的准确性、可靠性与效率奠定了重要基础，是该领域的一项根本性突破。

> Large language models (LLMs) often struggle with context fidelity, producing inconsistent answers when responding to questions based on provided information. Existing approaches either rely on expensive supervised fine-tuning to generate evidence post-answer or train models to perform web searches without necessarily improving utilization of the given context. We propose CARE, a novel native retrieval-augmented reasoning framework that teaches LLMs to explicitly integrate in-context evidence within their reasoning process with the model's own retrieval capabilities. Our method requires limited labeled evidence data while significantly enhancing both retrieval accuracy and answer generation performance through strategically retrieved in-context tokens in the reasoning chain. Extensive experiments on multiple real-world and counterfactual QA benchmarks demonstrate that our approach substantially outperforms supervised fine-tuning, traditional retrieval-augmented generation methods, and external retrieval solutions. This work represents a fundamental advancement in making LLMs more accurate, reliable, and efficient for knowledge-intensive tasks.

[Arxiv](https://arxiv.org/abs/2509.13683)