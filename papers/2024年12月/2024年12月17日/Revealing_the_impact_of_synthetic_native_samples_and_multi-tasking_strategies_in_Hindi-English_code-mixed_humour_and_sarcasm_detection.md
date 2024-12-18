# 揭示合成本地样本和多任务策略在印地语 - 英语代码混合的幽默与讽刺检测中的作用

发布时间：2024年12月17日

`LLM应用` `代码混合`

> Revealing the impact of synthetic native samples and multi-tasking strategies in Hindi-English code-mixed humour and sarcasm detection

# 摘要

> 在本文中，我们讲述了运用多种策略来优化代码混合的幽默与讽刺检测的实验情况。我们针对印地语 - 英语代码混合这一场景开展了所有实验，因为我们在这方面具备语言专长。我们尝试了三种方法，分别是（i）本地样本混合，（ii）多任务学习（MTL），以及（iii）提示超大多语言语言模型（VMLMs）。在本地样本混合中，我们在代码混合训练集中添加了单语任务样本。在 MTL 学习里，我们依靠语义相关任务（我们案例中的仇恨检测）的本地和代码混合样本。最后，在第三种方法中，我们通过少样本上下文提示来评估 VMLMs 的效果。我们获得的一些有趣发现有：（i）添加本地样本提升了幽默（F1 分数提高至 6.76％）和讽刺（F1 分数提高至 8.64％）的检测效果，（ii）在 MTL 框架中训练 MLMs 增强了幽默（F1 分数提高至 10.67％）和讽刺（F1 分数增加至 12.35％）的检测性能，（iii）提示 VMLMs 不如其他方法出色。最后，我们的消融研究和错误分析找出了模型尚需改进的情况。我们提供了代码以确保可重复性。

> In this paper, we reported our experiments with various strategies to improve code-mixed humour and sarcasm detection. We did all of our experiments for Hindi-English code-mixed scenario, as we have the linguistic expertise for the same. We experimented with three approaches, namely (i) native sample mixing, (ii) multi-task learning (MTL), and (iii) prompting very large multilingual language models (VMLMs). In native sample mixing, we added monolingual task samples in code-mixed training sets. In MTL learning, we relied on native and code-mixed samples of a semantically related task (hate detection in our case). Finally, in our third approach, we evaluated the efficacy of VMLMs via few-shot context prompting. Some interesting findings we got are (i) adding native samples improved humor (raising the F1-score up to 6.76%) and sarcasm (raising the F1-score up to 8.64%) detection, (ii) training MLMs in an MTL framework boosted performance for both humour (raising the F1-score up to 10.67%) and sarcasm (increment up to 12.35% in F1-score) detection, and (iii) prompting VMLMs couldn't outperform the other approaches. Finally, our ablation studies and error analysis discovered the cases where our model is yet to improve. We provided our code for reproducibility.

[Arxiv](https://arxiv.org/abs/2412.12761)