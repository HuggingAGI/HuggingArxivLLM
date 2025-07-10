# 不确定性对逐层推理动力学的影响

发布时间：2025年07月09日

`LLM理论` `人工智能` `可解释性`

> On the Effect of Uncertainty on Layer-wise Inference Dynamics

# 摘要

> 大型语言模型如何在内部表示和处理预测，对于检测不确定性并防止幻觉至关重要。尽管已有研究表明模型在隐藏状态下编码不确定性，但这种现象如何影响它们处理隐藏状态的方式仍鲜为人知。在本研究中，我们发现确定性和不确定性输出的输出标记概率在各层之间的动态变化基本一致，表明不确定性似乎并不影响推理过程。具体而言，我们采用Tuned Lens（Logit Lens的一种变体），分析了11个数据集和5个模型最终预测标记的层间概率轨迹。将错误预测视为具有更高知识不确定性的实例，我们的结果表明，确定性和不确定性的预测在类似层中均观察到置信度的突然增加，轨迹高度一致。我们通过展示更成熟的模型可能学习以不同方式处理不确定性的证据来平衡这一发现。我们的研究结果挑战了在推理过程中利用简单方法检测不确定性的可行性。更广泛地说，我们的工作展示了如何利用可解释性方法来探讨不确定性如何影响推理过程。

> Understanding how large language models (LLMs) internally represent and process their predictions is central to detecting uncertainty and preventing hallucinations. While several studies have shown that models encode uncertainty in their hidden states, it is underexplored how this affects the way they process such hidden states. In this work, we demonstrate that the dynamics of output token probabilities across layers for certain and uncertain outputs are largely aligned, revealing that uncertainty does not seem to affect inference dynamics. Specifically, we use the Tuned Lens, a variant of the Logit Lens, to analyze the layer-wise probability trajectories of final prediction tokens across 11 datasets and 5 models. Using incorrect predictions as those with higher epistemic uncertainty, our results show aligned trajectories for certain and uncertain predictions that both observe abrupt increases in confidence at similar layers. We balance this finding by showing evidence that more competent models may learn to process uncertainty differently. Our findings challenge the feasibility of leveraging simplistic methods for detecting uncertainty at inference. More broadly, our work demonstrates how interpretability methods may be used to investigate the way uncertainty affects inference.

[Arxiv](https://arxiv.org/abs/2507.06722)