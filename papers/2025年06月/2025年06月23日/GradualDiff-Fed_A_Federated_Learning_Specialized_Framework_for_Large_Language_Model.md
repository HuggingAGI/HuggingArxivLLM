# GradualDiff-Fed：为大型语言模型量身定制的联邦学习框架

发布时间：2025年06月23日

`LLM应用` `医学科学` `隐私保护`

> GradualDiff-Fed: A Federated Learning Specialized Framework for Large Language Model

# 摘要

> 大型语言模型（LLMs）的迅速普及催生了对特定领域微调模型的高需求，特别是在医学科学等专业领域。联邦学习（FL）作为一种去中心化且保护隐私的技术，能够在不共享原始数据的情况下协作微调LLMs，但其在性能和高效管理大型模型规模方面面临诸多挑战。本文中，我们介绍了GradualDiff-Fed，这是一个专为LLMs设计的FL框架，旨在解决处理高参数规模的难题。GradualDiff-Fed通过在训练过程中仅传输模型权重的差异，而非整个模型，从而显著降低通信成本。这一创新方法大幅提升了可扩展性和通信效率，使得在分布式客户端上微调LLMs成为可能，同时保持了高性能。我们的评估结果显示，GradualDiff-Fed在性能上与集中式训练相当，同时大幅减少了通信开销。这些结果凸显了GradualDiff-Fed作为在保护隐私的环境下从分布式数据中高效微调大型模型的解决方案的潜力。


> The rapid proliferation of large language models (LLMs) has created an unprecedented demand for fine-tuning models for specialized domains, such as medical science. While federated learning (FL) offers a decentralized and privacy-preserving approach to collaboratively fine-tune LLMs without sharing raw data, it presents significant challenges, particularly in performance and managing large model sizes efficiently. In this paper, we introduce GradualDiff-Fed, an FL framework designed explicitly for LLMs, and their challenge of handling the high parameter size. GradualDiff-Fed reduces communication costs by transmitting only the difference of model weights rather than the entire model during training rounds. Such an approach significantly improves scalability and communication efficiency, making it more feasible to fine-tune LLMs across distributed clients without compromising performance. Our evaluation demonstrates that GradualDiff-Fed achieves performance on par with centralized training while drastically reducing communication overhead. These results highlight the potential of GradualDiff-Fed as an efficient solution for fine-tuning large models from distributed data in privacy-preserving settings without comprising performance.

[Arxiv](https://arxiv.org/abs/2506.19164)