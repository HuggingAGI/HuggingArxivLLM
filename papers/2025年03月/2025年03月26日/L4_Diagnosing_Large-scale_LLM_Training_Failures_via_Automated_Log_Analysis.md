# L4：利用自动化日志分析诊断大规模 LLM 训练中的失败问题

发布时间：2025年03月26日

`LLM应用` `人工智能`

> L4: Diagnosing Large-scale LLM Training Failures via Automated Log Analysis

# 摘要

> 随着大型语言模型（LLMs）在各类应用中展现出其能力，训练定制化LLMs已成为现代企业的必选项。然而，由于LLMs训练的复杂性，需要巨大的计算资源和漫长的训练时间，训练过程中难免会出现失败。这些失败导致了大量资源和时间的浪费，凸显了对有效的故障诊断方法的迫切需求，以降低LLMs训练的成本。

在本文中，我们首次对2023年5月至2024年4月期间在我们的生产平台Platform-X上出现的428次LLMs训练失败案例进行了实证研究。研究发现，硬件和用户错误是主要的故障根源，而当前的诊断流程高度依赖于训练日志。遗憾的是，现有的基于日志的诊断方法在处理LLMs训练日志方面表现不佳。考虑到LLMs训练的独特性，我们识别出了三种独特的LLMs训练日志模式：跨任务、空间和时间模式。随后，我们介绍了我们的基于日志的大规模LLMs训练故障诊断框架L4，该框架能够从海量训练日志中自动提取故障指示信息（即日志事件、节点、阶段和迭代），从而减少人工努力并促进故障恢复。在真实世界数据集上的实验结果表明，L4在识别故障指示日志和定位故障节点方面优于现有方法。此外，L4已在Platform-X中得到应用，并证明了其在实现准确和高效故障诊断方面的有效性。

> As Large Language Models (LLMs) show their capabilities across various applications, training customized LLMs has become essential for modern enterprises. However, due to the complexity of LLM training, which requires massive computational resources and extensive training time, failures are inevitable during the training process. These failures result in considerable waste of resource and time, highlighting the critical need for effective and efficient failure diagnosis to reduce the cost of LLM training.
  In this paper, we present the first empirical study on the failure reports of 428 LLM training failures in our production Platform-X between May 2023 and April 2024. Our study reveals that hardware and user faults are the predominant root causes, and current diagnosis processes rely heavily on training logs. Unfortunately, existing log-based diagnostic methods fall short in handling LLM training logs. Considering the unique features of LLM training, we identify three distinct patterns of LLM training logs: cross-job, spatial, and temporal patterns. We then introduce our Log-based Large-scale LLM training failure diagnosis framework, L4, which can automatically extract failure-indicating information (i.e., log events, nodes, stages, and iterations) from extensive training logs, thereby reducing manual effort and facilitating failure recovery. Experimental results on real-world datasets show that L4 outperforms existing approaches in identifying failure-indicating logs and localizing faulty nodes. Furthermore, L4 has been applied in Platform-X and demonstrated its effectiveness in enabling accurate and efficient failure diagnosis.

[Arxiv](https://arxiv.org/abs/2503.20263)