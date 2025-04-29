# 驾驭巨无霸：高效 LLM 推理服务综述

发布时间：2025年04月28日

`LLM应用

摘要讨论了大型语言模型（LLMs）在实际应用中的优化和部署挑战，特别是在推理服务方面。它涵盖了模型部署、请求调度、存储管理等实例级方法，以及GPU集群部署、负载均衡等集群级策略，这些都是应用层面的优化和实际部署问题。因此，这篇论文属于LLM应用类别。` `生成式AI` `云计算`

> Taming the Titans: A Survey of Efficient LLM Inference Serving

# 摘要

> 生成式AI中的大型语言模型（LLMs）已发展成为复杂且多用途的工具，在多个领域和应用中得到广泛应用。然而，这些模型由于参数数量庞大带来的巨大内存占用，加上注意力机制的高计算需求，使得实现低延迟和高吞吐量的LLM推理服务面临巨大挑战。得益于突破性研究的推动，近期在该领域取得了显著进展。本文对这些方法进行了全面综述，涵盖基本的实例级方法、深入的集群级策略、新兴的场景方向和其他一些零散但重要的领域。在实例级别，我们回顾了模型部署、请求调度、解码长度预测、存储管理和拆分范式。在集群级别，我们探讨了GPU集群部署、多实例负载均衡和云服务解决方案。针对新兴场景，我们围绕特定任务、模块和辅助方法组织讨论。为了确保全面概述，我们还强调了几个利基但关键的领域。最后，我们概述了进一步推进LLM推理服务领域的潜在研究方向。

> Large Language Models (LLMs) for Generative AI have achieved remarkable progress, evolving into sophisticated and versatile tools widely adopted across various domains and applications. However, the substantial memory overhead caused by their vast number of parameters, combined with the high computational demands of the attention mechanism, poses significant challenges in achieving low latency and high throughput for LLM inference services. Recent advancements, driven by groundbreaking research, have significantly accelerated progress in this field. This paper provides a comprehensive survey of these methods, covering fundamental instance-level approaches, in-depth cluster-level strategies, emerging scenario directions, and other miscellaneous but important areas. At the instance level, we review model placement, request scheduling, decoding length prediction, storage management, and the disaggregation paradigm. At the cluster level, we explore GPU cluster deployment, multi-instance load balancing, and cloud service solutions. For emerging scenarios, we organize the discussion around specific tasks, modules, and auxiliary methods. To ensure a holistic overview, we also highlight several niche yet critical areas. Finally, we outline potential research directions to further advance the field of LLM inference serving.

[Arxiv](https://arxiv.org/abs/2504.19720)