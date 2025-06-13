# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月12日

`LLM应用` `大型语言模型` `安全监控系统`

> Detecting High-Stakes Interactions with Activation Probes

# 摘要

> 监控大型语言模型（LLMs）的安全性至关重要。本文聚焦于检测“高风险”互动的激活探针——即文本暗示互动可能引发严重危害的情况——这一监控领域的重要但未充分探索的目标。我们评估了在合成数据上训练的多种探针架构，发现它们在处理多样化、分布外的真实世界数据时表现出了强大的泛化能力。探针的性能与经过提示或微调的中型LLM监控器相当，同时在计算资源上节省了六个数量级。实验结果还凸显了构建资源感知型分层监控系统的潜力，其中探针作为高效的一级过滤器，标记出需要进一步昂贵分析的案例。我们发布了新型合成数据集和代码库，以促进进一步研究。

> Monitoring is an important aspect of safely deploying Large Language Models (LLMs). This paper examines activation probes for detecting "high-stakes" interactions -- where the text indicates that the interaction might lead to significant harm -- as a critical, yet underexplored, target for such monitoring. We evaluate several probe architectures trained on synthetic data, and find them to exhibit robust generalization to diverse, out-of-distribution, real-world data. Probes' performance is comparable to that of prompted or finetuned medium-sized LLM monitors, while offering computational savings of six orders-of-magnitude. Our experiments also highlight the potential of building resource-aware hierarchical monitoring systems, where probes serve as an efficient initial filter and flag cases for more expensive downstream analysis. We release our novel synthetic dataset and codebase to encourage further study.

[Arxiv](https://arxiv.org/abs/2506.10805)