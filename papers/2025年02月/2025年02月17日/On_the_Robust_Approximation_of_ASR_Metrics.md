# # 关于 ASR 评估指标的鲁棒近似研究
最近大型语言模型 (LLMs) 的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于 LLMs 自动化工作流编排过程实现了。

发布时间：2025年02月17日

`其他` `语音识别` `模型评估`

> On the Robust Approximation of ASR Metrics

# 摘要

> 语音基础模型的突破性进展主要得益于模型规模和数据的扩展，使其能够执行包括语音识别在内的多种任务。传统ASR模型使用词错误率（WER）和字符错误率（CER）等指标进行评估，这些指标依赖于真实标签。然而，由于来自不同领域和测试条件的标注数据有限，这些模型在标准基准之外的真实泛化能力尚不明确。此外，标注数据既耗时又昂贵。为了解决这一问题，我们提出了一种无需标签的新型方法，用于近似ASR性能指标。我们的方法利用统一空间中的多模态嵌入来表示语音和转录，并结合高质量代理模型计算代理指标。这些特征用于训练回归模型，以预测关键ASR指标，如WER和CER。我们在涵盖标准和真实测试条件的14个数据集上实验了40多种模型。实验结果表明，我们的方法在所有实验配置下将指标近似值控制在个位数绝对差异内，比最新基线高出50%以上。

> Recent advances in speech foundation models are largely driven by scaling both model size and data, enabling them to perform a wide range of tasks, including speech recognition. Traditionally, ASR models are evaluated using metrics like Word Error Rate (WER) and Character Error Rate (CER), which depend on ground truth labels. As a result of limited labeled data from diverse domains and testing conditions, the true generalization capabilities of these models beyond standard benchmarks remain unclear. Moreover, labeling data is both costly and time-consuming. To address this, we propose a novel label-free approach for approximating ASR performance metrics, eliminating the need for ground truth labels. Our method utilizes multimodal embeddings in a unified space for speech and transcription representations, combined with a high-quality proxy model to compute proxy metrics. These features are used to train a regression model to predict key ASR metrics like Word Error Rate (WER) and Character Error Rate (CER). We experiment with over 40 models across 14 datasets representing both standard and in-the-wild testing conditions. Our results show that we approximate the metrics within a single-digit absolute difference across all experimental configurations, outperforming the most recent baseline by more than 50\%.

[Arxiv](https://arxiv.org/abs/2502.12408)