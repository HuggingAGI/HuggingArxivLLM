# 迈向负责任的联邦大型语言模型：借助安全过滤器与宪法式AI

发布时间：2025年02月23日

`LLM应用` `联邦学习` `负责任AI`

> Toward Responsible Federated Large Language Models: Leveraging a Safety Filter and Constitutional AI

# 摘要

> 近期研究越来越多地关注利用联邦学习（federated learning）训练大型语言模型（LLMs），即所谓的FedLLM。然而，旨在确保生成安全回应的负责任AI（RAI），在FedLLM背景下仍处于探索初期。在FedLLM中，用于训练的客户端数据可能包含有害内容，导致生成有害回应的不安全LLMs。将这些不安全的LLMs聚合到全局模型并分发给客户端，可能导致不安全LLMs的广泛部署。为了解决这一问题，我们将两种知名的RAI方法融入FedLLM：安全过滤器和宪法AI。实验结果表明，这些方法显著提升了LLMs的安全性，在评估安全性能的AdvBench基准上实现了超过20%的性能提升。

> Recent research has increasingly focused on training large language models (LLMs) using federated learning, known as FedLLM. However, responsible AI (RAI), which aims to ensure safe responses, remains underexplored in the context of FedLLM. In FedLLM, client data used for training may contain harmful content, leading to unsafe LLMs that generate harmful responses. Aggregating such unsafe LLMs into the global model and distributing them to clients may result in the widespread deployment of unsafe LLMs. To address this issue, we incorporate two well-known RAI methods into FedLLM: the safety filter and constitutional AI. Our experiments demonstrate that these methods significantly enhance the safety of the LLM, achieving over a 20% improvement on AdvBench, a benchmark for evaluating safety performance.

[Arxiv](https://arxiv.org/abs/2502.16691)