# 基于未标记语音的音频大语言模型自我改进

发布时间：2025年07月27日

`LLM应用` `语音处理`

> Self-Improvement for Audio Large Language Model using Unlabeled Speech

# 摘要

> 音频大语言模型（audio LLMs）正以迅猛之势发展，在各类语音任务中展现出卓越的泛化能力。然而，由于语音信号的固有复杂性，这些模型在特定目标领域中难免会出现性能瓶颈。针对这一挑战，我们专注于在无需标注数据的前提下提升音频LLMs在目标领域的能力。为此，我们提出了一种名为SI-SDA的自我改进方法，该方法通过挖掘大型模型解码中的信息来评估生成伪标签的质量，并基于强化学习优化实现领域适应。实验结果表明，我们的方法在多个公开的自动语音识别（ASR）、语音问答（SQA）和语音到文本翻译（S2TT）数据集上，显著提升了音频LLMs的性能，其在词错误率（WER）和BLEU评分上均超越了现有基线方法。此外，我们的方法表现出高效的数据利用能力，充分展现了其在实际应用中的潜力。

> Recent audio LLMs have emerged rapidly, demonstrating strong generalization across various speech tasks. However, given the inherent complexity of speech signals, these models inevitably suffer from performance degradation in specific target domains. To address this, we focus on enhancing audio LLMs in target domains without any labeled data. We propose a self-improvement method called SI-SDA, leveraging the information embedded in large-model decoding to evaluate the quality of generated pseudo labels and then perform domain adaptation based on reinforcement learning optimization. Experimental results show that our method consistently and significantly improves audio LLM performance, outperforming existing baselines in WER and BLEU across multiple public datasets of automatic speech recognition (ASR), spoken question-answering (SQA), and speech-to-text translation (S2TT). Furthermore, our approach exhibits high data efficiency, underscoring its potential for real-world deployment.

[Arxiv](https://arxiv.org/abs/2507.20169)