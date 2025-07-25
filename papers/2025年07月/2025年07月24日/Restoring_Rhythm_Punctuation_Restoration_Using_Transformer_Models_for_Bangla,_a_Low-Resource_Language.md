# 为孟加拉语重拾节奏：基于Transformer模型的标点恢复研究

发布时间：2025年07月24日

`LLM应用` `语音识别`

> Restoring Rhythm: Punctuation Restoration Using Transformer Models for Bangla, a Low-Resource Language

# 摘要

> 标点符号恢复能够显著提升文本可读性，并在自动语音识别（ASR）的后处理任务中发挥关键作用，特别是在孟加拉语等低资源语言中。本研究聚焦于基于Transformer的XLM-RoBERTa-large模型，探索其在无标点孟加拉语文本中自动恢复标点的应用。研究重点在于预测句号、逗号、问号和感叹号四种标点符号，并覆盖多种文本领域。为应对标注资源匮乏的挑战，我们构建了一个大型多样化训练语料库，并引入了数据增强技术。经过alpha = 0.20%的增强因子训练的最佳模型，在新闻测试集上取得了97.1%的准确率，在参考集和ASR测试集上分别达到了91.2%和90.2%的准确率。实验结果表明，该模型在参考文本和ASR转录文本上展现出强大的泛化能力，证明了其在真实场景中处理噪声数据的有效性。这项研究为孟加拉语的标点恢复任务奠定了坚实的基础，并提供了公开可用的数据集和代码，以支持未来在低资源NLP领域的研究工作。

> Punctuation restoration enhances the readability of text and is critical for post-processing tasks in Automatic Speech Recognition (ASR), especially for low-resource languages like Bangla. In this study, we explore the application of transformer-based models, specifically XLM-RoBERTa-large, to automatically restore punctuation in unpunctuated Bangla text. We focus on predicting four punctuation marks: period, comma, question mark, and exclamation mark across diverse text domains. To address the scarcity of annotated resources, we constructed a large, varied training corpus and applied data augmentation techniques. Our best-performing model, trained with an augmentation factor of alpha = 0.20%, achieves an accuracy of 97.1% on the News test set, 91.2% on the Reference set, and 90.2% on the ASR set.
  Results show strong generalization to reference and ASR transcripts, demonstrating the model's effectiveness in real-world, noisy scenarios. This work establishes a strong baseline for Bangla punctuation restoration and contributes publicly available datasets and code to support future research in low-resource NLP.

[Arxiv](https://arxiv.org/abs/2507.18448)