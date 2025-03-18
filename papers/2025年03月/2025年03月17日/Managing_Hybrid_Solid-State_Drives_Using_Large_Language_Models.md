# # 使用大型语言模型管理混合固态硬盘

发布时间：2025年03月17日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在优化混合固态硬盘（Hybrid SSDs）设计中的应用潜力。虽然主要讨论的是存储设备的设计和优化，但其核心在于利用LLMs来解决复杂的设计问题，属于LLM在特定领域的应用。因此，分类为LLM应用。` `计算机系统优化`

> Managing Hybrid Solid-State Drives Using Large Language Models

# 摘要

> 混合固态硬盘（Hybrid Solid-State Drives, SSDs）通过集成多种闪存单元（如单层单元 SLC 和多层单元 MLC）并实现它们之间的相互转换，旨在在提供高性能的同时满足大容量存储需求。然而，与传统 SSD 相比，混合 SSD 的设计空间更为庞大，涉及更多设计因素（如闪存转换时机和数据迁移等），这大大增加了优化难度。为了解决这一难题，大型语言模型（LLMs）展现出了巨大潜力，因其在处理复杂、高维参数空间探索方面的能力尤为突出，能够通过强大的模式识别和优化能力提供有效解决方案。尽管已有研究开始探索 LLMs 在计算机系统优化中的应用，但目前尚未有研究专注于利用 LLMs 来优化 SSD。

> Hybrid Solid-State Drives (SSDs), which integrate several types of flash cells (e.g., single-level cell (SLC) and multiple-level cell (MLC)) in a single drive and enable them to convert between each other, are designed to deliver both high performance and high storage capacity. However, compared to traditional SSDs, hybrid SSDs also introduce a much larger design space, resulting in higher optimization complexity due to more design factors involved, including flash conversion timing and data migration between different flash cells, etc. To address these challenges, large language models (LLMs) could be a promising technique, as they excel in handling complex, high-dimensional parameter space exploration by leveraging their advanced capability to identify patterns and optimize solutions. Recent works have started exploring the use of LLMs to optimize computer systems. However, to the best of our knowledge, no study has focused on optimizing SSDs with the assistance of LLMs.
  In this work, we explore the potential of LLMs in understanding and efficiently managing hybrid SSD design space. Specifically, two important questions are exploited and analyzed: 1) Can LLMs offer optimization potential for Hybrid SSD management? 2) How to leverage LLMs for the performance and efficiency of hybrid SSD optimization? Based on the observations of exploration, we propose a comprehensive auto-tuning framework for hybrid SSDs, integrating LLMs to recommend customized configurations using calibration prompts derived from hardware, system, and workload information. Experimental results reveal a 62.35% improvement in throughput and a 57.99% decrease in write amplification compared to the default hybrid SSD configurations achieved with the incorporation of LLMs.

[Arxiv](https://arxiv.org/abs/2503.13105)