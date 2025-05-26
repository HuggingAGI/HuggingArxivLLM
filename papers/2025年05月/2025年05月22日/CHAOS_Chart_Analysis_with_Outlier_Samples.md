# CHAOS：基于离群样本的图表分析

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在处理异常图表时的表现，并通过基准测试评估其鲁棒性。这属于LLM的实际应用和评估，因此归类为LLM应用。` `数据分析` `数据可视化`

> CHAOS: Chart Analysis with Outlier Samples

# 摘要

> 图表在数据分析和可视化中扮演着关键角色，但现实世界中的图表常具有挑战性或噪声特征。即使是多模态大型语言模型（MLLMs），面对“异常图表”也难以应对。本研究引入了CHAO S（CHart Analysis with Outlier Samples），这是一个鲁棒性基准测试，旨在系统性评估MLLMs在图表扰动情况下的性能。CHAO S包含五种文本扰动类型和十种视觉扰动类型，每种类型设有三种难度级别（简单、中等、困难），这一设定灵感来源于人类评估研究结果。该基准测试包含了13个最先进的MLLMs，根据训练范围和数据，分为三组（通用型、文档型和图表专用型模型）。全面分析涉及ChartQA和Chart-to-Text两个下游任务。通过广泛实验和案例研究，我们揭示了模型在图表扰动下的关键鲁棒性见解，并致力于为未来在图表理解领域的研究提供指导。数据和代码公开可用：http://huggingface.co/datasets/omoured/CHAOS.

> Charts play a critical role in data analysis and visualization, yet real-world applications often present charts with challenging or noisy features. However, "outlier charts" pose a substantial challenge even for Multimodal Large Language Models (MLLMs), which can struggle to interpret perturbed charts. In this work, we introduce CHAOS (CHart Analysis with Outlier Samples), a robustness benchmark to systematically evaluate MLLMs against chart perturbations. CHAOS encompasses five types of textual and ten types of visual perturbations, each presented at three levels of severity (easy, mid, hard) inspired by the study result of human evaluation. The benchmark includes 13 state-of-the-art MLLMs divided into three groups (i.e., general-, document-, and chart-specific models) according to the training scope and data. Comprehensive analysis involves two downstream tasks (ChartQA and Chart-to-Text). Extensive experiments and case studies highlight critical insights into robustness of models across chart perturbations, aiming to guide future research in chart understanding domain. Data and code are publicly available at: http://huggingface.co/datasets/omoured/CHAOS.

[Arxiv](https://arxiv.org/abs/2505.17235)