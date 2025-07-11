# 能量引导解码：缓解物体幻觉的方法

发布时间：2025年07月10日

`LLM应用` `视觉问答` `视觉语言模型`

> Energy-Guided Decoding for Object Hallucination Mitigation

# 摘要

> 在大型视觉语言模型 (LVLMs) 中缓解对象幻觉问题对于确保其安全应用至关重要。现有方法要么受限于特定的解码方式，要么需要对视觉输入进行复杂调整，要么依赖外部模型的知识。本研究首先揭示了视觉语言模型 (VLMs) 在三个视觉问答 (VQA) 数据集中存在显著的“是”比率失衡现象（即“是”答案在总问题数中的比例）。我们提出了一种基于能量的解码方法，该方法通过动态选择具有最小能量分数的层的隐藏状态，简单而有效地减少了“是”比率偏差，同时提升了在 POPE、MME 和 MMVP 三个基准测试上的性能。与贪心解码相比，该方法在三种常用 VLM 上对三个 VQA 数据集的平均准确率提高了 4.82%，平均“是”比率差距减少了 8.81%（如图 1 所示），表明该方法具有更低的偏差。

> Mitigating object hallucination in large vision-language models (LVLMs) is critical to their safe deployment. Existing methods either are restricted to specific decoding methods, or demand sophisticated modifications to visual inputs, or rely on knowledge from external models. In this work, we first reveal the phenomenon that VLMs exhibit significant imbalance in the ``Yes'' ratio ( \ie, the fraction of ``Yes'' answers among the total number of questions) across three different visual question answering (VQA) datasets. Furthermore, we propose an energy-based decoding method, which dynamically selects the hidden states from the layer with minimal energy score. It is simple yet effective in reducing the bias for the yes ratio while boosting performance across three benchmarks (POPE, MME, and MMVP). Our method consistently improves accuracy and F1 score on three VQA datasets across three commonly used VLMs over several baseline methods. The average accuracy improvement is 4.82% compared to greedy decoding. Moreover, the average yes-ratio gap reduction is 8.81%, meaning the proposed method is less biased as shown in Figure 1.

[Arxiv](https://arxiv.org/abs/2507.07731)