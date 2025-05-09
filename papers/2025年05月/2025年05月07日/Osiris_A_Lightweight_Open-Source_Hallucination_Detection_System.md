# Osiris：一款轻量级开源幻觉检测系统

发布时间：2025年05月07日

`RAG` `问答系统`

> Osiris: A Lightweight Open-Source Hallucination Detection System

# 摘要

> 检索增强生成（RAG）系统因其能够利用可信来源让大型语言模型（LLMs）生成更具事实依据的响应，而受到了广泛应用。然而，幻觉现象——即LLMs在生成响应时对所提供上下文的不忠实表现——常常阻碍这些系统在生产环境中部署。当前的幻觉检测方法通常依赖于人工评估或使用闭源模型来审查RAG系统输出中的幻觉。无论是人工评估员还是闭源模型，都因成本高昂和推理速度缓慢而面临扩展性问题。在本研究中，我们引入了一个经过扰动处理的多跳问答数据集，其中包含了诱发的幻觉。通过在我们的数据集上进行监督微调，我们实现了相较于GPT-4o在RAGTruth幻觉检测基准上更高的召回率，并在精确度和准确率方面提供了具有竞争力的表现，同时仅使用了其一小部分参数。代码已发布在我们的仓库中。

> Retrieval-Augmented Generation (RAG) systems have gained widespread adoption by application builders because they leverage sources of truth to enable Large Language Models (LLMs) to generate more factually sound responses. However, hallucinations, instances of LLM responses that are unfaithful to the provided context, often prevent these systems from being deployed in production environments. Current hallucination detection methods typically involve human evaluation or the use of closed-source models to review RAG system outputs for hallucinations. Both human evaluators and closed-source models suffer from scaling issues due to their high costs and slow inference speeds. In this work, we introduce a perturbed multi-hop QA dataset with induced hallucinations. Via supervised fine-tuning on our dataset, we achieve better recall with a 7B model than GPT-4o on the RAGTruth hallucination detection benchmark and offer competitive performance on precision and accuracy, all while using a fraction of the parameters. Code is released at our repository.

[Arxiv](https://arxiv.org/abs/2505.04844)