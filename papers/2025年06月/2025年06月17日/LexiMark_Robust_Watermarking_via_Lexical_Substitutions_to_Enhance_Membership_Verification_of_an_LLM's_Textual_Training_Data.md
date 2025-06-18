# LexiMark：通过词汇替换实现的鲁棒水印技术，提升大型语言模型 (LLM) 文本训练数据的成员身份验证能力。

发布时间：2025年06月17日

`LLM应用` `数据安全` `数据处理`

> LexiMark: Robust Watermarking via Lexical Substitutions to Enhance Membership Verification of an LLM's Textual Training Data

# 摘要

> 大型语言模型（LLMs）可能在未经数据所有者同意的情况下进行训练或微调。验证特定LLM是否经过特定数据实例或数据集的训练极具挑战性。数据集水印技术通过在训练数据中嵌入可识别的修改来检测未经授权的使用。然而，现有方法往往缺乏隐蔽性，使其相对容易被检测和移除。为了解决这一问题，我们提出了LexiMark，一种专为文本和文档设计的新型水印技术。LexiMark通过替换精心选择的高熵词汇来嵌入同义词替换，旨在增强LLM对水印文本的记忆能力，同时保持文本的语义完整性。因此，水印难以被检测，无缝融入文本中，没有任何可见标记，并且由于其微妙且语境恰当的替换，能够抵御自动和手动检测。我们使用近期研究的基准数据集以及七种开源模型进行了评估，包括LLaMA-1 7B、LLaMA-3 8B、Mistral 7B、Pythia 6.9B，以及来自Pythia系列的三个较小变体（160M、410M和1B）。我们的评估涵盖了多种训练设置，包括持续预训练和微调场景。结果显示，与现有方法相比，我们的方法在AUROC分数方面有了显著提升，凸显了我们在可靠验证未经授权的水印数据是否用于LLM训练方面的有效性。

> Large language models (LLMs) can be trained or fine-tuned on data obtained without the owner's consent. Verifying whether a specific LLM was trained on particular data instances or an entire dataset is extremely challenging. Dataset watermarking addresses this by embedding identifiable modifications in training data to detect unauthorized use. However, existing methods often lack stealth, making them relatively easy to detect and remove. In light of these limitations, we propose LexiMark, a novel watermarking technique designed for text and documents, which embeds synonym substitutions for carefully selected high-entropy words. Our method aims to enhance an LLM's memorization capabilities on the watermarked text without altering the semantic integrity of the text. As a result, the watermark is difficult to detect, blending seamlessly into the text with no visible markers, and is resistant to removal due to its subtle, contextually appropriate substitutions that evade automated and manual detection. We evaluated our method using baseline datasets from recent studies and seven open-source models: LLaMA-1 7B, LLaMA-3 8B, Mistral 7B, Pythia 6.9B, as well as three smaller variants from the Pythia family (160M, 410M, and 1B). Our evaluation spans multiple training settings, including continued pretraining and fine-tuning scenarios. The results demonstrate significant improvements in AUROC scores compared to existing methods, underscoring our method's effectiveness in reliably verifying whether unauthorized watermarked data was used in LLM training.

[Arxiv](https://arxiv.org/abs/2506.14474)