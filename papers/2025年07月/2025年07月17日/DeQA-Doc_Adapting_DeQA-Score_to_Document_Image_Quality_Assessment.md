# DeQA-Doc：文档图像质量评估的DeQA-Score适配方案

发布时间：2025年07月17日

`LLM应用

摘要中提到的研究是将多模态大语言模型（MLLMs）应用于文档质量评估，属于应用层面的研究。具体来说，研究者利用MLLM的视觉语言能力和软标签策略，提出了一个名为DeQA-Doc的框架，用于文档质量的连续评分。这表明研究的重点在于如何应用MLLM来解决实际问题，而不是探讨MLLM的理论或机制。因此，这篇论文应归类为LLM应用。` `文档处理` `OCR`

> DeQA-Doc: Adapting DeQA-Score to Document Image Quality Assessment

# 摘要

> 文档质量评估在文档数字化、OCR和档案管理等领域发挥着重要作用。然而，现有方法常因难以提供准确可靠的品质评分而受限于实际应用。随着多模态大语言模型（MLLMs）的快速发展，基于MLLM的质量评估方法在图像领域取得了突破。本研究将这一成功经验引入文档领域，基于先进图像质量评分器DeQA-Score，提出了一套文档质量评估方案。我们推出了DeQA-Doc框架，该框架通过MLLM的视觉语言能力和软标签策略实现文档质量的连续评分。为适配文档图像特点，我们采用两种互补方案构建不含方差信息的软标签，并放宽分辨率限制以支持大尺寸文档图像处理。此外，我们引入集成方法进一步提升评估性能。大量实验结果表明，DeQA-Doc显著超越现有基线方法，在各类退化场景下均能提供准确且具普适性的文档质量评估。代码和模型权重已开源，访问地址为https://github.com/Junjie-Gao19/DeQA-Doc。

> Document quality assessment is critical for a wide range of applications including document digitization, OCR, and archival. However, existing approaches often struggle to provide accurate and robust quality scores, limiting their applicability in practical scenarios. With the rapid progress in Multi-modal Large Language Models (MLLMs), recent MLLM-based methods have achieved remarkable performance in image quality assessment. In this work, we extend this success to the document domain by adapting DeQA-Score, a state-of-the-art MLLM-based image quality scorer, for document quality assessment. We propose DeQA-Doc, a framework that leverages the visual language capabilities of MLLMs and a soft label strategy to regress continuous document quality scores. To adapt DeQA-Score to DeQA-Doc, we adopt two complementary solutions to construct soft labels without the variance information. Also, we relax the resolution constrains to support the large resolution of document images. Finally, we introduce ensemble methods to further enhance the performance. Extensive experiments demonstrate that DeQA-Doc significantly outperforms existing baselines, offering accurate and generalizable document quality assessment across diverse degradation types. Codes and model weights are available in https://github.com/Junjie-Gao19/DeQA-Doc.

[Arxiv](https://arxiv.org/abs/2507.12796)