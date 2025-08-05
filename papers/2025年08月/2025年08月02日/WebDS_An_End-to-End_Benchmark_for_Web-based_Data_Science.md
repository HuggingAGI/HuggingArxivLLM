# WebDS：面向Web数据科学的端到端评测基准

发布时间：2025年08月02日

`Agent

这篇论文主要探讨智能体在复杂数据科学任务中的表现，特别是评估它们在多跳网络交互中的能力，因此属于Agent类别。` `数据科学`

> WebDS: An End-to-End Benchmark for Web-based Data Science

# 摘要

> 现实世界中的大量数据科学任务复杂且需要多跳网络交互：从互联网获取数据，整合来自不同地点的多模态实时数据，并生成汇总分析。现有的网络基准测试通常关注简单的交互，例如表单提交或电子商务交易，而忽视了基于网络数据科学所需的多样化工具使用能力。相反，传统的数据科学基准测试通常集中在静态、受文本限制的数据集上，无法评估涵盖数据获取、清洗、分析和见解生成的端到端工作流。为应对这一挑战，我们推出了首个端到端基于网络的数据科学基准测试——WebDS。它包含来自29个不同网站的870个基于网络的数据科学任务，从结构化的政府数据门户到非结构化的新闻媒体，挑战智能体执行复杂的多步骤操作，需要使用工具和异构数据格式，更好地反映现代数据分析的现实。对当前SOTA LLM智能体的评估显示，在完成这些任务方面存在显著性能差距。例如，在Web Voyager上完成80%任务的Browser Use，在WebDS中仅成功完成15%的任务，我们的分析表明这是由于WebDS任务执行中智能体表现出的新失败模式，如信息接地差、重复行为和走捷径。通过提供一个更强大和现实的测试环境，WebDS为开发实用的LLM数据科学奠定了基础，推动了显著的进步。


> A large portion of real-world data science tasks are complex and require multi-hop web-based interactions: finding appropriate data available on the internet, synthesizing real-time data of various modalities from different locations, and producing summarized analyses. Existing web benchmarks often focus on simplistic interactions, such as form submissions or e-commerce transactions, and often do not require diverse tool-using capabilities required for web based data science. Conversely, traditional data science benchmarks typically concentrate on static, often textually bound datasets and do not assess end-to-end workflows that encompass data acquisition, cleaning, analysis, and insight generation. In response, we introduce WebDS, the first end-to-end web-based data science benchmark. It comprises 870 web-based data science tasks across 29 diverse websites from structured government data portals to unstructured news media, challenging agents to perform complex, multi-step operations requiring the use of tools and heterogeneous data formats that better reflect the realities of modern data analytics. Evaluations of current SOTA LLM agents indicate significant performance gaps in accomplishing these tasks. For instance, Browser Use, which accomplishes 80% of tasks on Web Voyager, successfully completes only 15% of tasks in WebDS, which our analysis suggests is due to new failure modes like poor information grounding, repetitive behavior and shortcut-taking that agents performing WebDS' tasks display. By providing a more robust and realistic testing ground, WebDS sets the stage for significant advances in the development of practically useful LLM-based data science.

[Arxiv](https://arxiv.org/abs/2508.01222)