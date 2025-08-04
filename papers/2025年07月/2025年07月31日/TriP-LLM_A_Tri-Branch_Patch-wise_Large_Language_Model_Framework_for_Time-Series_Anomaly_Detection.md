# # 摘要
TriP-LLM：三分支补丁式大型语言模型框架，专为时间序列异常检测设计。

发布时间：2025年07月31日

`LLM应用` `物联网` `智能制造`

> TriP-LLM: A Tri-Branch Patch-wise Large Language Model Framework for Time-Series Anomaly Detection

# 摘要

> 时间序列异常检测在众多应用领域中发挥着至关重要的作用。随着物联网（IoT）和智能制造的快速发展，时间序列数据的规模和维度急剧增长。这一趋势暴露了传统统计方法在处理高异质性和复杂性数据方面的局限性。受大型语言模型（LLMs）在语言和视觉领域多模态任务中取得的成功启发，我们提出了一种全新的无监督异常检测框架：三分支补丁式大型语言模型框架（TriP-LLM），专为时间序列异常检测设计。通过三分支设计——Patching、Selection和Global-to，TriP-LLM整合了局部和全局时间特征，将输入的时间序列编码为补丁式标记，随后由一个冻结的预训练LLM进行处理。轻量级的补丁式解码器用于重构输入，并从中推导出异常分数。我们采用PATE（一种无阈值的新型评估指标）在多个公开基准数据集上对TriP-LLM进行评估，并在统一的开源框架内完成所有比较，以确保公平性。实验结果表明，TriP-LLM在所有数据集上均显著优于现有最新方法，展现出强大的异常检测能力。此外，通过广泛的消融实验，我们验证了LLM对整体架构的重大贡献。与采用Channel Independence（CI）补丁处理的LLM-based方法相比，TriP-LLM实现了显著的内存消耗降低，使其更适用于GPU内存受限的环境。所有代码和模型检查点均可在https://github.com/YYZStart/TriP-LLM.git公开获取。

> Time-series anomaly detection plays a central role across a wide range of application domains. With the increasing proliferation of the Internet of Things (IoT) and smart manufacturing, time-series data has dramatically increased in both scale and dimensionality. This growth has exposed the limitations of traditional statistical methods in handling the high heterogeneity and complexity of such data. Inspired by the recent success of large language models (LLMs) in multimodal tasks across language and vision domains, we propose a novel unsupervised anomaly detection framework: A Tri-Branch Patch-wise Large Language Model Framework for Time-Series Anomaly Detection (TriP-LLM). TriP-LLM integrates local and global temporal features through a tri-branch design-Patching, Selection, and Global-to encode the input time series into patch-wise tokens, which are then processed by a frozen, pretrained LLM. A lightweight patch-wise decoder reconstructs the input, from which anomaly scores are derived. We evaluate TriP-LLM on several public benchmark datasets using PATE, a recently proposed threshold-free evaluation metric, and conduct all comparisons within a unified open-source framework to ensure fairness. Experimental results show that TriP-LLM consistently outperforms recent state-of-the-art methods across all datasets, demonstrating strong detection capabilities. Furthermore, through extensive ablation studies, we verify the substantial contribution of the LLM to the overall architecture. Compared to LLM-based approaches using Channel Independence (CI) patch processing, TriP-LLM achieves significantly lower memory consumption, making it more suitable for GPU memory-constrained environments. All code and model checkpoints are publicly available on https://github.com/YYZStart/TriP-LLM.git

[Arxiv](https://arxiv.org/abs/2508.00047)