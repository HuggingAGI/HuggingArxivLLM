# 基于多模态大型语言模型，检测新加坡语境中具有社会偏见的攻击性图片文字

发布时间：2025年02月25日

`LLM应用

理由：这篇论文主要讨论了如何将视觉语言模型（VLM）应用于在线内容审核，特别是针对表情包的分类。研究者们使用了大型数据集微调VLM，并结合OCR和翻译技术构建了一个流水线，以提高审核的准确性和效率。这些工作属于LLM的实际应用，因此归类为LLM应用。` `内容审核` `视觉语言模型`

> Detecting Offensive Memes with Social Biases in Singapore Context Using Multimodal Large Language Models

# 摘要

> 传统在线内容审核系统难以有效分类现代多模态交流方式，例如表情包这种高度细微且信息密集的媒介。这一任务在新加坡这样文化多元的社会中尤为艰难，因为需要使用资源较少的语言，并且需要大量本地背景知识来解读在线内容。我们整理了一个包含11.2万个由GPT-4V标注的表情包的大型数据集，用于微调视觉语言模型（VLM），以在新加坡语境下分类冒犯性表情包。我们展示了在我们的数据集上微调的VLM的有效性，并提出了一种包含OCR、翻译和一个70亿参数的视觉语言模型的流水线。我们的解决方案在独立测试集上达到了80.62%的准确率和0.8192的AUROC，能够极大地帮助人类审核在线内容。数据集、代码和模型权重将在https://github.com/aliencaocao/vlm-for-memes-aisg开源。

> Traditional online content moderation systems struggle to classify modern multimodal means of communication, such as memes, a highly nuanced and information-dense medium. This task is especially hard in a culturally diverse society like Singapore, where low-resource languages are used and extensive knowledge on local context is needed to interpret online content. We curate a large collection of 112K memes labeled by GPT-4V for fine-tuning a VLM to classify offensive memes in Singapore context. We show the effectiveness of fine-tuned VLMs on our dataset, and propose a pipeline containing OCR, translation and a 7-billion parameter-class VLM. Our solutions reach 80.62% accuracy and 0.8192 AUROC on a held-out test set, and can greatly aid human in moderating online contents. The dataset, code, and model weights will be open-sourced at https://github.com/aliencaocao/vlm-for-memes-aisg.

[Arxiv](https://arxiv.org/abs/2502.18101)