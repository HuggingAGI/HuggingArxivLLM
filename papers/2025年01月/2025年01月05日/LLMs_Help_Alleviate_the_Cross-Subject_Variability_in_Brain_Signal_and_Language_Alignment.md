# LLMs 助力减轻脑信号与语言对齐中的跨主体差异。

发布时间：2025年01月05日

`LLM应用

**理由**：这篇论文主要探讨了利用大型语言模型（LLMs）作为去噪工具，从EEG信号中提取与受试者无关的语义信息。虽然研究涉及EEG信号和脑机接口（BCI），但其核心在于LLMs的应用，即利用LLMs来处理和分析EEG信号，从而提升模型的泛化能力。因此，这篇论文应归类为LLM应用。` `脑机接口` `神经科学`

> LLMs Help Alleviate the Cross-Subject Variability in Brain Signal and Language Alignment

# 摘要

> 从EEG信号中解码人类活动一直是研究热点。尽管近年来越来越多的研究从单一受试者转向跨受试者分析，但鲜有研究探索模型对未见过的受试者EEG信号进行零-shot预测的能力。本研究旨在探讨深度学习方法能否捕捉EEG信号中与受试者无关的语义信息。这些发现对BCI至关重要，因为它们不仅展示了模型对受试者特定时间偏差的鲁棒性，还显著提升了下游任务的泛化能力。我们利用LLMs作为去噪工具，从嘈杂的EEG信号中提取与受试者无关的语义特征。实验结果，尤其是消融研究，凸显了LLMs在解码与受试者无关的语义信息中的关键作用。我们希望这些发现能推动BCI研究，助力学术界和工业界将EEG信号应用于更广泛的领域。

> Decoding human activity from EEG signals has long been a popular research topic. While recent studies have increasingly shifted focus from single-subject to cross-subject analysis, few have explored the model's ability to perform zero-shot predictions on EEG signals from previously unseen subjects. This research aims to investigate whether deep learning methods can capture subject-independent semantic information inherent in human EEG signals. Such insights are crucial for Brain-Computer Interfaces (BCI) because, on one hand, they demonstrate the model's robustness against subject-specific temporal biases, and on the other, they significantly enhance the generalizability of downstream tasks. We employ Large Language Models (LLMs) as denoising agents to extract subject-independent semantic features from noisy EEG signals. Experimental results, including ablation studies, highlight the pivotal role of LLMs in decoding subject-independent semantic information from noisy EEG data. We hope our findings will contribute to advancing BCI research and assist both academia and industry in applying EEG signals to a broader range of applications.

[Arxiv](https://arxiv.org/abs/2501.02621)