# # 标题
在ArchEHR-QA 2025中，heiDS实现了从固定k到查询依赖k的转变，助力检索增强生成任务。

发布时间：2025年06月24日

`RAG

摘要中提到的heiDS方法是基于检索增强生成（RAG）框架设计的，重点在于改进RAG框架的检索策略和归属方法，因此归类为RAG。` `问答系统`

> heiDS at ArchEHR-QA 2025: From Fixed-k to Query-dependent-k for Retrieval Augmented Generation

# 摘要

> 本文介绍了我们团队的 heiDS 方法，用于参与 ArchEHR-QA 2025 共享任务。我们设计了一个基于检索增强生成（RAG）框架的流水线，旨在根据患者的电子健康记录（EHRs）生成基于临床证据的回答，以回答特定于患者的问题。我们探索了 RAG 框架的各个组件，重点关注排名列表截断（RLT）检索策略和归属方法。与固定 top-k RLT 检索策略不同，我们采用了基于查询的 k 检索策略，其中包括现有的 surprise 和 autocut 方法，以及我们在本文中提出的两种新方法 autocut* 和 elbow。实验结果表明，我们的策略在生成事实性和相关性较高的答案方面优于固定-$k$ 策略。

> This paper presents the approach of our team called heiDS for the ArchEHR-QA 2025 shared task. A pipeline using a retrieval augmented generation (RAG) framework is designed to generate answers that are attributed to clinical evidence from the electronic health records (EHRs) of patients in response to patient-specific questions. We explored various components of a RAG framework, focusing on ranked list truncation (RLT) retrieval strategies and attribution approaches. Instead of using a fixed top-k RLT retrieval strategy, we employ a query-dependent-k retrieval strategy, including the existing surprise and autocut methods and two new methods proposed in this work, autocut* and elbow. The experimental results show the benefits of our strategy in producing factual and relevant answers when compared to a fixed-$k$.

[Arxiv](https://arxiv.org/abs/2506.19512)