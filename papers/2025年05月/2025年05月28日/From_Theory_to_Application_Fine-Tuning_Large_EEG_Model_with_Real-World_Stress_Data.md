# 从理论到应用：基于真实世界压力数据微调 EEG 模型

发布时间：2025年05月28日

`LLM应用` `脑科学` `脑机接口`

> From Theory to Application: Fine-Tuning Large EEG Model with Real-World Stress Data

# 摘要

> 大型语言模型的突破性进展推动了各领域基础模型的发展。本研究通过在真实世界压力分类数据集上微调最先进的基础脑电模型LaBraM，评估了大型脑电模型（LEMs）的实际效果。与以往主要依赖受控临床环境数据的研究不同，我们的工作重点在于评估LEMs在真实环境中的适用性。

我们利用18名研究生课堂上的静息状态脑电数据，训练了一个能够区分正常和压力升高状态的二元分类器。实验结果表明，最佳微调模型在5秒窗口下实现了90.47%的平衡准确率，显著超越传统压力分类器在准确性和推理效率上的表现。

进一步的实验评估了微调LEMs在随机数据打乱和通道数减少情况下的鲁棒性。这些结果不仅证明了LEMs有效处理真实脑电数据的能力，更凸显了其通过从模型中心向数据中心设计转变，彻底革新脑机接口应用的潜力。

> Recent advancements in Large Language Models have inspired the development of foundation models across various domains. In this study, we evaluate the efficacy of Large EEG Models (LEMs) by fine-tuning LaBraM, a state-of-the-art foundation EEG model, on a real-world stress classification dataset collected in a graduate classroom. Unlike previous studies that primarily evaluate LEMs using data from controlled clinical settings, our work assesses their applicability to real-world environments. We train a binary classifier that distinguishes between normal and elevated stress states using resting-state EEG data recorded from 18 graduate students during a class session. The best-performing fine-tuned model achieves a balanced accuracy of 90.47% with a 5-second window, significantly outperforming traditional stress classifiers in both accuracy and inference efficiency. We further evaluate the robustness of the fine-tuned LEM under random data shuffling and reduced channel counts. These results demonstrate the capability of LEMs to effectively process real-world EEG data and highlight their potential to revolutionize brain-computer interface applications by shifting the focus from model-centric to data-centric design.

[Arxiv](https://arxiv.org/abs/2505.23042)