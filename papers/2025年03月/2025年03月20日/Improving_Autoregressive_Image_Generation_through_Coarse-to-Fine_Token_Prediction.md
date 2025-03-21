# # 利用粗到细的标记预测提升自回归图像生成效果

发布时间：2025年03月20日

`其他` `图像生成` `计算机视觉`

> Improving Autoregressive Image Generation through Coarse-to-Fine Token Prediction

# 摘要

> 自回归模型在图像生成领域取得了显著成功，这得益于其将语言建模中的序列预测技术进行了巧妙应用。然而，将这些方法应用于图像生成时，需要通过向量量化方法（如VQ-VAE）对连续的像素数据进行离散化处理。尽管近期研究通过使用更大的代码本来缓解VQ-VAE的量化误差问题，但这也相应增加了词汇表的规模，使得自回归建模变得更加复杂。本文的目标是探索一种既能充分利用大代码本的优势，又不增加自回归建模难度的方法。通过深入研究，我们发现具有相似码本表示的标记会对最终生成的图像产生相似的影响，这表明大代码本中存在显著的冗余。基于这一发现，我们提出了一种从粗到细（CTF）的标记预测方法，通过为相似的标记分配相同的粗略标签来实现。我们的框架包含两个阶段：（1）一个自回归模型，用于依次预测序列中每个标记的粗略标签；（2）一个辅助模型，根据所有标记的粗略标签同时预测它们的精细标签。在ImageNet上的实验结果表明，与基线方法相比，我们的方法具有显著的优越性，平均提高了59个Inception Score点。值得注意的是，尽管增加了一个推理步骤，但我们的方法在采样速度上仍然更快。

> Autoregressive models have shown remarkable success in image generation by adapting sequential prediction techniques from language modeling. However, applying these approaches to images requires discretizing continuous pixel data through vector quantization methods like VQ-VAE. To alleviate the quantization errors that existed in VQ-VAE, recent works tend to use larger codebooks. However, this will accordingly expand vocabulary size, complicating the autoregressive modeling task. This paper aims to find a way to enjoy the benefits of large codebooks without making autoregressive modeling more difficult. Through empirical investigation, we discover that tokens with similar codeword representations produce similar effects on the final generated image, revealing significant redundancy in large codebooks. Based on this insight, we propose to predict tokens from coarse to fine (CTF), realized by assigning the same coarse label for similar tokens. Our framework consists of two stages: (1) an autoregressive model that sequentially predicts coarse labels for each token in the sequence, and (2) an auxiliary model that simultaneously predicts fine-grained labels for all tokens conditioned on their coarse labels. Experiments on ImageNet demonstrate our method's superior performance, achieving an average improvement of 59 points in Inception Score compared to baselines. Notably, despite adding an inference step, our approach achieves faster sampling speeds.

[Arxiv](https://arxiv.org/abs/2503.16194)