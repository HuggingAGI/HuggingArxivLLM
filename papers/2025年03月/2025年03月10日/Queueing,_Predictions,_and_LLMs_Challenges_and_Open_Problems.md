# 排队、预测与LLMs：挑战及开放性问题

发布时间：2025年03月10日

`LLM应用

理由：这篇论文探讨了在调度中使用预测技术，特别是大型语言模型（LLM）系统，关注LLM的推理过程及其在调度中的挑战和潜力。因此，它属于LLM应用类别。` `机器学习`

> Queueing, Predictions, and LLMs: Challenges and Open Problems

# 摘要

> 排队系统为机器学习预测的应用提供了丰富的机会，例如通过预测服务时间来优化系统性能。然而，如何有效利用预测结果来提升调度决策仍是一个开放性问题。近期研究表明，基于预测服务时间的排队系统能够有效减少任务在系统中的停留时间。我们回顾了这些研究，强调了预测的有效性，并提出了关于队列性能的开放问题。

接下来，我们将目光投向一个重要的实际案例：在调度中使用预测技术，特别是大型语言模型（LLM）系统。这类系统不仅带来了全新的调度挑战，还凸显了预测在提升性能方面的巨大潜力。我们特别关注LLM的推理过程。LLM系统中的推理请求（任务）具有高度复杂性：它们不仅具有可变的推理时间，还面临受键值（KV）存储内存限制的动态内存占用问题，同时多种抢占策略对性能的影响也各不相同。

我们介绍了LLM系统调度中关键方面的背景知识，并提出了由此产生的新模型和开放问题。我们认为，将排队理论中的见解和分析应用于LLM系统的调度，存在巨大的潜力。


> Queueing systems present many opportunities for applying machine-learning predictions, such as estimated service times, to improve system performance. This integration raises numerous open questions about how predictions can be effectively leveraged to improve scheduling decisions. Recent studies explore queues with predicted service times, typically aiming to minimize job time in the system. We review these works, highlight the effectiveness of predictions, and present open questions on queue performance. We then move to consider an important practical example of using predictions in scheduling, namely Large Language Model (LLM) systems, which presents novel scheduling challenges and highlights the potential for predictions to improve performance. In particular, we consider LLMs performing inference. Inference requests (jobs) in LLM systems are inherently complex; they have variable inference times, dynamic memory footprints that are constrained by key-value (KV) store memory limitations, and multiple possible preemption approaches that affect performance differently. We provide background on the important aspects of scheduling in LLM systems, and introduce new models and open problems that arise from them. We argue that there are significant opportunities for applying insights and analysis from queueing theory to scheduling in LLM systems.

[Arxiv](https://arxiv.org/abs/2503.07545)