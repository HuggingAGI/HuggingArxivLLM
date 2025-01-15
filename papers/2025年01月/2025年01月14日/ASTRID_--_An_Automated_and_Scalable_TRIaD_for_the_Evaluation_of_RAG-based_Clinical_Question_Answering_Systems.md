# ASTRID -- 一个自动化和可扩展的TRIaD，用于评估基于RAG的临床问答系统

发布时间：2025年01月14日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在临床问答系统中的应用，并提出了一个自动化评估框架ASTRID来评估基于RAG的临床QA系统。论文的核心内容围绕RAG系统的评估和改进，因此应归类为RAG。` `问答系统`

> ASTRID -- An Automated and Scalable TRIaD for the Evaluation of RAG-based Clinical Question Answering Systems

# 摘要

> # 摘要
大型语言模型（LLMs）在临床问答（QA）中展现了巨大潜力，检索增强生成（RAG）作为确保模型响应事实准确性的领先方法脱颖而出。然而，当前的自动化RAG指标在临床和对话式场景中表现欠佳。依赖临床人工评估不仅成本高昂且难以扩展，也不利于RAG系统的持续迭代开发。为此，我们推出了ASTRID——一种自动化和可扩展的TRIaD评估框架，用于评估基于RAG的临床QA系统。ASTRID包含三个核心指标：上下文相关性（CR）、拒绝准确性（RA）和对话忠实度（CF）。其中，CF是我们设计的新指标，旨在更好地衡量模型响应与知识库的忠实度，同时避免对对话元素的过度惩罚。为了验证这一框架，我们构建了一个包含200多个真实世界患者问题的数据集，这些问题来自白内障手术（全球手术量最大的手术）的术后随访，并补充了临床医生选择的紧急、临床和非临床领域外问题。实验表明，CF在对话式场景中比现有指标更能准确预测人类对忠实度的评分。此外，使用CF、RA和CR组成的三元组进行评估，其结果与临床医生对不适当、有害或无益响应的判断高度一致。最后，通过九种不同的LLM，我们证明了这三个指标与人类评估高度吻合，展现了它们在LLM驱动的自动化评估管道中的巨大潜力。我们还公开了实验的提示和数据集，为后续研究和开发提供了宝贵资源。

> Large Language Models (LLMs) have shown impressive potential in clinical question answering (QA), with Retrieval Augmented Generation (RAG) emerging as a leading approach for ensuring the factual accuracy of model responses. However, current automated RAG metrics perform poorly in clinical and conversational use cases. Using clinical human evaluations of responses is expensive, unscalable, and not conducive to the continuous iterative development of RAG systems. To address these challenges, we introduce ASTRID - an Automated and Scalable TRIaD for evaluating clinical QA systems leveraging RAG - consisting of three metrics: Context Relevance (CR), Refusal Accuracy (RA), and Conversational Faithfulness (CF). Our novel evaluation metric, CF, is designed to better capture the faithfulness of a model's response to the knowledge base without penalising conversational elements. To validate our triad, we curate a dataset of over 200 real-world patient questions posed to an LLM-based QA agent during surgical follow-up for cataract surgery - the highest volume operation in the world - augmented with clinician-selected questions for emergency, clinical, and non-clinical out-of-domain scenarios. We demonstrate that CF can predict human ratings of faithfulness better than existing definitions for conversational use cases. Furthermore, we show that evaluation using our triad consisting of CF, RA, and CR exhibits alignment with clinician assessment for inappropriate, harmful, or unhelpful responses. Finally, using nine different LLMs, we demonstrate that the three metrics can closely agree with human evaluations, highlighting the potential of these metrics for use in LLM-driven automated evaluation pipelines. We also publish the prompts and datasets for these experiments, providing valuable resources for further research and development.

[Arxiv](https://arxiv.org/abs/2501.08208)