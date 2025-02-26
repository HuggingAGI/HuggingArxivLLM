# 构建睡眠分析基础模型：基于多模态混合自监督学习框架的探索

发布时间：2025年02月18日

`其他` `睡眠医学` `生物医学工程`

> Toward Foundational Model for Sleep Analysis Using a Multimodal Hybrid Self-Supervised Learning Framework

# 摘要

> # 摘要  
睡眠对维持人类健康和生活质量至关重要。分析睡眠期间的生理信号对于评估睡眠质量和诊断睡眠障碍至关重要。然而，临床医生的 manual diagnoses 耗时且主观性强。尽管深度学习的进步增强了自动化，但这些方法仍严重依赖大规模标注数据集。本研究引入了 SynthSleepNet，这是一种用于分析多导睡眠图 (PSG) 数据的多模态混合自监督学习框架。SynthSleepNet 有效结合了 masked prediction 和 contrastive learning，以充分利用脑电图 (EEG)、眼电图 (EOG)、肌电图 (EMG) 和心电图 (ECG) 等多模态数据的互补特征。这种方法使模型能够学习 PSG 数据的高表达表示。此外，基于 Mamba 开发了时间上下文模块，以高效捕获信号中的上下文信息。在睡眠分期分类、睡眠呼吸暂停检测和低通气检测这三项下游任务中，SynthSleepNet 的表现优于现有方法，准确率分别为 89.89%、99.75% 和 89.60%。在标签有限的半监督学习环境中，模型在相同任务中的准确率分别为 87.98%、99.37% 和 77.52%。这些结果凸显了该模型作为全面分析 PSG 数据基础工具的潜力。与其它方法相比，SynthSleepNet 在多项下游任务中表现出全面的优越性，有望为睡眠障碍监测和诊断系统树立新标准。


> Sleep is essential for maintaining human health and quality of life. Analyzing physiological signals during sleep is critical in assessing sleep quality and diagnosing sleep disorders. However, manual diagnoses by clinicians are time-intensive and subjective. Despite advances in deep learning that have enhanced automation, these approaches remain heavily dependent on large-scale labeled datasets. This study introduces SynthSleepNet, a multimodal hybrid self-supervised learning framework designed for analyzing polysomnography (PSG) data. SynthSleepNet effectively integrates masked prediction and contrastive learning to leverage complementary features across multiple modalities, including electroencephalogram (EEG), electrooculography (EOG), electromyography (EMG), and electrocardiogram (ECG). This approach enables the model to learn highly expressive representations of PSG data. Furthermore, a temporal context module based on Mamba was developed to efficiently capture contextual information across signals. SynthSleepNet achieved superior performance compared to state-of-the-art methods across three downstream tasks: sleep-stage classification, apnea detection, and hypopnea detection, with accuracies of 89.89%, 99.75%, and 89.60%, respectively. The model demonstrated robust performance in a semi-supervised learning environment with limited labels, achieving accuracies of 87.98%, 99.37%, and 77.52% in the same tasks. These results underscore the potential of the model as a foundational tool for the comprehensive analysis of PSG data. SynthSleepNet demonstrates comprehensively superior performance across multiple downstream tasks compared to other methodologies, making it expected to set a new standard for sleep disorder monitoring and diagnostic systems.

[Arxiv](https://arxiv.org/abs/2502.17481)