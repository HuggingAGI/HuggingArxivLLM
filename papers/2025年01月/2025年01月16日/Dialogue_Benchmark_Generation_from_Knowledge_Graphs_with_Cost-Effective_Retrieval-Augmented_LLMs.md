# 基于知识图谱的对话基准生成：利用高效检索增强型LLMs

发布时间：2025年01月16日

`RAG

理由：这篇论文提出了一个名为Chatty-Gen的多阶段检索增强生成平台，利用知识图谱（KGs）自动生成特定领域的高质量对话基准。该方法结合了检索增强生成（RAG）技术，通过多阶段生成和自动验证来提高对话生成的质量和效率。因此，这篇论文主要属于RAG（Retrieval-Augmented Generation）领域。` `对话系统` `知识图谱`

> Dialogue Benchmark Generation from Knowledge Graphs with Cost-Effective Retrieval-Augmented LLMs

# 摘要

> # 摘要
对话基准在训练和评估领域特定对话的聊天机器人中扮演着关键角色。知识图谱（KGs）如DBLP、DBpedia和YAGO，提供了跨领域的语义丰富且结构化的数据。传统上，对话基准依赖于手动从文档中创建，忽视了KGs在自动化这一过程中的潜力。虽然一些问答基准通过KGs的预处理自动生成，但它们并不支持对话生成。本文提出Chatty-Gen，一个创新的多阶段检索增强生成平台，利用KGs自动生成针对特定领域的高质量对话基准。Chatty-Gen将生成过程分解为多个可控阶段，并通过断言规则实现阶段间的自动验证。该方法不仅有效控制中间结果，避免因幻觉导致的耗时重启，还减少了对高成本、高性能商业LLMs的依赖。Chatty-Gen采用高效的查询检索，无需预先处理整个KG，即可根据对话上下文找到代表性子图。我们在多个真实且大型的KGs上的实验表明，Chatty-Gen显著优于现有系统，并在不同能力的LLMs（如GPT-4o、Gemini 1.5、Llama 3和Mistral）上保持了模型和系统性能的一致性。

> Dialogue benchmarks are crucial in training and evaluating chatbots engaging in domain-specific conversations. Knowledge graphs (KGs) represent semantically rich and well-organized data spanning various domains, such as DBLP, DBpedia, and YAGO. Traditionally, dialogue benchmarks have been manually created from documents, neglecting the potential of KGs in automating this process. Some question-answering benchmarks are automatically generated using extensive preprocessing from KGs, but they do not support dialogue generation. This paper introduces Chatty-Gen, a novel multi-stage retrieval-augmented generation platform for automatically generating high-quality dialogue benchmarks tailored to a specific domain using a KG. Chatty-Gen decomposes the generation process into manageable stages and uses assertion rules for automatic validation between stages. Our approach enables control over intermediate results to prevent time-consuming restarts due to hallucinations. It also reduces reliance on costly and more powerful commercial LLMs. Chatty-Gen eliminates upfront processing of the entire KG using efficient query-based retrieval to find representative subgraphs based on the dialogue context. Our experiments with several real and large KGs demonstrate that Chatty-Gen significantly outperforms state-of-the-art systems and ensures consistent model and system performance across multiple LLMs of diverse capabilities, such as GPT-4o, Gemini 1.5, Llama 3, and Mistral.

[Arxiv](https://arxiv.org/abs/2501.09928)