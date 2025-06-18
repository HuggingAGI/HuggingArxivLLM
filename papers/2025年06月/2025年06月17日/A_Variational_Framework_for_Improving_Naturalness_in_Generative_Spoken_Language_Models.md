# # 提升生成式口语模型自然度的变分框架
我们提出了一种新的变分框架，旨在提升生成式口语模型的自然度。该框架通过优化生成内容的流畅性和多样性，显著改善了模型输出的质量。

发布时间：2025年06月17日

`LLM应用` `语音处理` `语音生成`

> A Variational Framework for Improving Naturalness in Generative Spoken Language Models

# 摘要

> 大型语言模型在文本处理中的成功启发了其在语音建模中的应用。然而，由于语音的连续性和复杂性，通常需要对其进行离散化处理以实现自回归建模。从自监督模型中提取的语音令牌（即语义令牌）通常侧重于语音的语言方面，但忽略了韵律信息。因此，基于这些令牌训练的模型生成的语音自然度较低。现有方法尝试通过向语义令牌添加音调特征来解决这一问题。然而，仅靠音调无法完全表示副语言属性的范围，而且选择合适的特征需要谨慎的手动工程。为克服这一问题，我们提出了一种端到端的变分方法，该方法能够自动学习编码这些连续的语音属性，从而增强语义令牌。我们的方法消除了手动提取和选择副语言特征的需要。此外，它还能生成更符合人类评分者偏好的语音延续。代码、样本和模型可在 https://github.com/b04901014/vae-gslm 获取。

> The success of large language models in text processing has inspired their adaptation to speech modeling. However, since speech is continuous and complex, it is often discretized for autoregressive modeling. Speech tokens derived from self-supervised models (known as semantic tokens) typically focus on the linguistic aspects of speech but neglect prosodic information. As a result, models trained on these tokens can generate speech with reduced naturalness. Existing approaches try to fix this by adding pitch features to the semantic tokens. However, pitch alone cannot fully represent the range of paralinguistic attributes, and selecting the right features requires careful hand-engineering. To overcome this, we propose an end-to-end variational approach that automatically learns to encode these continuous speech attributes to enhance the semantic tokens. Our approach eliminates the need for manual extraction and selection of paralinguistic features. Moreover, it produces preferred speech continuations according to human raters. Code, samples and models are available at https://github.com/b04901014/vae-gslm.

[Arxiv](https://arxiv.org/abs/2506.14767)