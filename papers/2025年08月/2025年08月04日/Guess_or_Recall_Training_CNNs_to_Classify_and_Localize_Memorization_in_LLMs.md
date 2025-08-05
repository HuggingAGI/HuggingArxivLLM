# 猜还是记？训练CNNs用于分类和定位LLMs中的记忆

发布时间：2025年08月04日

`LLM理论` `模型解释性`

> Guess or Recall? Training CNNs to Classify and Localize Memorization in LLMs

# 摘要

> 大型语言模型中的逐词记忆现象涉及多种不同的潜在机制。我们提出了一种新方法，用于分析现有分类法所描述的不同记忆形式。具体而言，我们在大型语言模型的注意力权重上训练卷积神经网络 (CNN)，并评估现有分类法与解码过程中涉及的注意力权重之间的对齐程度。

研究发现，现有分类法表现不佳，无法准确反映注意力块中的不同机制。为此，我们提出了一种新的分类法，旨在最大限度地与注意力权重对齐，包括三类：通过语言建模能力猜测的已记忆样本、由于训练集中高度重复而被回忆的已记忆样本，以及未记忆样本。我们的研究结果表明，少样本逐词记忆并不对应一种独特注意力机制。此外，我们发现大量可提取样本实际上是模型猜测的结果，因此应单独研究。最后，我们开发了一种定制的可视化可解释性技术，以定位每种记忆形式所涉及的注意力权重区域。

> Verbatim memorization in Large Language Models (LLMs) is a multifaceted phenomenon involving distinct underlying mechanisms. We introduce a novel method to analyze the different forms of memorization described by the existing taxonomy. Specifically, we train Convolutional Neural Networks (CNNs) on the attention weights of the LLM and evaluate the alignment between this taxonomy and the attention weights involved in decoding.
  We find that the existing taxonomy performs poorly and fails to reflect distinct mechanisms within the attention blocks. We propose a new taxonomy that maximizes alignment with the attention weights, consisting of three categories: memorized samples that are guessed using language modeling abilities, memorized samples that are recalled due to high duplication in the training set, and non-memorized samples. Our results reveal that few-shot verbatim memorization does not correspond to a distinct attention mechanism. We also show that a significant proportion of extractable samples are in fact guessed by the model and should therefore be studied separately. Finally, we develop a custom visual interpretability technique to localize the regions of the attention weights involved in each form of memorization.

[Arxiv](https://arxiv.org/abs/2508.02573)