# Ensemble Debiasing Across Class and Sample Levels for Fairer Prompting Accuracy
集成去偏方法在类别和样本层面的应用，以实现更公平的提示准确性。

发布时间：2025年03月07日

`LLM应用` `文本分类` `生物医学`

> Ensemble Debiasing Across Class and Sample Levels for Fairer Prompting Accuracy

# 摘要

> 语言模型在文本分类任务中作为强大的少量样本学习者，虽然在整体准确率上表现良好，但其结果却存在严重的类别准确率不平衡问题。我们坚信，整体准确率的提升不应依赖于强化优势类别，而应着眼于提升弱势类别。为解决这一不平衡问题，我们提出了一种基于事后非线性整数规划的去偏方法，该方法通过集成权重修正和成员修正，实现了在类别和样本层面灵活调整类别概率，从而直接从输出端提升大语言模型的性能。在Llama-2-13B模型上对七个文本分类基准进行的评估表明，我们的方法不仅达到了最先进的整体准确率提升，还实现了类别准确率的均衡。由此产生的概率修正方案证明，样本级别的修正对于提升弱势类别至关重要。此外，由于有效修正了弱势类别，我们的方法也为Llama-2-70B带来了显著的性能提升，尤其是在生物医学领域任务中，充分展示了其在小规模和大规模模型变体上的有效性。

> Language models are strong few-shot learners and achieve good overall accuracy in text classification tasks, masking the fact that their results suffer from great class accuracy imbalance. We believe that the pursuit of overall accuracy should not come from enriching the strong classes, but from raising up the weak ones. To address the imbalance, we propose a post-hoc nonlinear integer programming based debiasing method that ensembles weight correction and membership correction to enable flexible rectifications of class probabilities at both class and sample levels, enhancing the performance of LLMs directly from their outputs. Evaluations with Llama-2-13B on seven text classification benchmarks show that our approach achieves state-of-the-art overall accuracy gains with balanced class accuracies. The resulted probability correction scheme demonstrates that sample-level corrections are necessary to elevate weak classes. In addition, due to effectively correcting weak classes, our method also brings significant performance gains to Llama-2-70B, especially on a biomedical domain task, demonstrating its effectiveness across both small and large model variants.

[Arxiv](https://arxiv.org/abs/2503.05157)