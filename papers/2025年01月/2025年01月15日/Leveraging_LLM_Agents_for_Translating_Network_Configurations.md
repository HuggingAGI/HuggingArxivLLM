# 借助LLM代理实现网络配置翻译

发布时间：2025年01月15日

`Agent

理由：这篇论文描述了一种基于大型语言模型（LLM）代理的框架，用于网络配置翻译。论文中提到的“LLM代理”和“基于意图的检索增强生成（IRAG）模块”表明该研究涉及智能代理的应用，特别是利用LLM来执行特定任务（如配置翻译）。因此，这篇论文应归类为Agent。` `网络运维` `自动化`

> Leveraging LLM Agents for Translating Network Configurations

# 摘要

> 配置翻译是网络运维中的一项关键且频繁的任务。当网络设备损坏或过时时，管理员需要更换设备以维持服务连续性。由于更换设备可能来自不同厂商，配置翻译成为确保网络无缝运行的必要步骤。然而，手动翻译配置不仅费时费力，还容易出错。本文提出了一种基于意图的框架，利用大型语言模型（LLM）代理进行网络配置翻译。我们方法的核心是一个基于意图的检索增强生成（IRAG）模块，它能系统地将配置文件分割、提取意图并生成准确的翻译。此外，我们还设计了两阶段验证方法，确保翻译配置的语法和语义正确性。通过在真实网络配置上的实验，我们的方法在语法正确性上达到了97.74%，翻译准确性优于现有方法。

> Configuration translation is a critical and frequent task in network operations. When a network device is damaged or outdated, administrators need to replace it to maintain service continuity. The replacement devices may originate from different vendors, necessitating configuration translation to ensure seamless network operation. However, translating configurations manually is a labor-intensive and error-prone process. In this paper, we propose an intent-based framework for translating network configuration with Large Language Model (LLM) Agents. The core of our approach is an Intent-based Retrieval Augmented Generation (IRAG) module that systematically splits a configuration file into fragments, extracts intents, and generates accurate translations. We also design a two-stage verification method to validate the syntax and semantics correctness of the translated configurations. We implement and evaluate the proposed method on real-world network configurations. Experimental results show that our method achieves 97.74% syntax correctness, outperforming state-of-the-art methods in translation accuracy.

[Arxiv](https://arxiv.org/abs/2501.08760)