# GradualDiff-Fed: 针对大型语言模型的联邦学习专用框架

发布时间：2025年06月23日

`LLM理论` `隐私保护`

> GradualDiff-Fed: A Federated Learning Specialized Framework for Large Language Model

# 摘要

> 大型语言模型（LLMs）的普及催生了对专业领域模型微调的迫切需求，例如医学科学领域。虽然联邦学习（FL）提供了一种去中心化且保护隐私的协作微调方法，但其在性能和高效管理大型模型规模方面面临挑战。本文介绍GradualDiff-Fed，这是一个专为LLMs设计的FL框架，旨在解决高参数规模的挑战。GradualDiff-Fed通过仅传输模型权重的差异而非整个模型，显著降低了通信成本，提升了可扩展性和通信效率，使分布式客户端上的LLM微调更加可行。实验表明，GradualDiff-Fed在性能上可与集中式训练相媲美，同时大幅降低了通信开销，展现了其在保护隐私环境下高效微调大型模型的潜力。

> The rapid proliferation of large language models (LLMs) has created an unprecedented demand for fine-tuning models for specialized domains, such as medical science. While federated learning (FL) offers a decentralized and privacy-preserving approach to collaboratively fine-tune LLMs without sharing raw data, it presents significant challenges, particularly in performance and managing large model sizes efficiently. In this paper, we introduce GradualDiff-Fed, an FL framework designed explicitly for LLMs, and their challenge of handling the high parameter size. GradualDiff-Fed reduces communication costs by transmitting only the difference of model weights rather than the entire model during training rounds. Such an approach significantly improves scalability and communication efficiency, making it more feasible to fine-tune LLMs across distributed clients without compromising performance. Our evaluation demonstrates that GradualDiff-Fed achieves performance on par with centralized training while drastically reducing communication overhead. These results highlight the potential of GradualDiff-Fed as an efficient solution for fine-tuning large models from distributed data in privacy-preserving settings without comprising performance.

[Arxiv](https://arxiv.org/abs/2506.19164)