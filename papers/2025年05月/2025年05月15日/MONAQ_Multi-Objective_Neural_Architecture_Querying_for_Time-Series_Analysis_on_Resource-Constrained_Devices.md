# MONAQ：面向资源受限设备的时间序列分析的多目标神经架构查询方法

发布时间：2025年05月15日

`LLM应用

摘要中提到论文利用大型语言模型（LLM）进行神经架构搜索（NAS），并将其重新定义为多目标神经架构查询任务，用于优化时序分析模型的部署。这属于LLM在特定任务中的应用，因此归类为LLM应用。` `物联网` `边缘计算`

> MONAQ: Multi-Objective Neural Architecture Querying for Time-Series Analysis on Resource-Constrained Devices

# 摘要

> 智能手机和IoT设备的普及推动了在资源受限硬件上实现高效时序分析的需求，这对于人体活动识别和空气质量预测等感知应用至关重要。尽管近期硬件感知的神经架构搜索（NAS）在为特定平台自动化架构发现方面取得了进展，但这些努力尚未聚焦于边缘部署的通用时序分析。我们提出MONAQ——一个创新框架，借助大型语言模型（LLM）的问题解决和推理能力，将NAS重新定义为多目标神经架构查询任务。MONAQ不仅支持多模态查询生成，能够处理时序输入和硬件约束，还通过基于LLM代理的多目标搜索，实现代码生成驱动的即用型模型部署。通过整合数值数据、时序图像和文本描述，MONAQ显著提升了LLM对时序数据的理解能力。实验结果表明，MONAQ发现的模型在十五个数据集上不仅超越了传统手工设计模型和NAS基线，还实现了更高的运行效率。

> The growing use of smartphones and IoT devices necessitates efficient time-series analysis on resource-constrained hardware, which is critical for sensing applications such as human activity recognition and air quality prediction. Recent efforts in hardware-aware neural architecture search (NAS) automate architecture discovery for specific platforms; however, none focus on general time-series analysis with edge deployment. Leveraging the problem-solving and reasoning capabilities of large language models (LLM), we propose MONAQ, a novel framework that reformulates NAS into Multi-Objective Neural Architecture Querying tasks. MONAQ is equipped with multimodal query generation for processing multimodal time-series inputs and hardware constraints, alongside an LLM agent-based multi-objective search to achieve deployment-ready models via code generation. By integrating numerical data, time-series images, and textual descriptions, MONAQ improves an LLM's understanding of time-series data. Experiments on fifteen datasets demonstrate that MONAQ-discovered models outperform both handcrafted models and NAS baselines while being more efficient.

[Arxiv](https://arxiv.org/abs/2505.10607)