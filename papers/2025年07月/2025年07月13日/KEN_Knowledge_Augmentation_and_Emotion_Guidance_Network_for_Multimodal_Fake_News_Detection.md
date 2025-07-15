# KEN：知识增强与情感引导网络，应用于多模态假新闻检测

发布时间：2025年07月13日

`LLM应用` `社交媒体` `信息检测`

> KEN: Knowledge Augmentation and Emotion Guidance Network for Multimodal Fake News Detection

# 摘要

> 近年来，社交媒体上虚假信息的泛滥使得多模态虚假新闻的检测成为研究热点。然而，现有研究在图像语义理解方面存在不足，且模型在文本信息有限的情况下难以准确判断新闻真实性。此外，对不同类型情感化新闻采取一刀切的方法也导致了性能下降。因此，我们提出了知识增强与情感引导网络（KEN）。一方面，我们利用大型视觉语言模型的强大语义理解能力，通过生成图像描述全面解析图像内容，并借助检索证据打破文本信息孤岛。另一方面，我们通过平衡学习捕捉不同类型情感化新闻的差异，实现情感与真实性之间的精准建模。实验结果表明，我们的 KEN 在真实数据集上表现优异。

> In recent years, the rampant spread of misinformation on social media has made accurate detection of multimodal fake news a critical research focus. However, previous research has not adequately understood the semantics of images, and models struggle to discern news authenticity with limited textual information. Meanwhile, treating all emotional types of news uniformly without tailored approaches further leads to performance degradation. Therefore, we propose a novel Knowledge Augmentation and Emotion Guidance Network (KEN). On the one hand, we effectively leverage LVLM's powerful semantic understanding and extensive world knowledge. For images, the generated captions provide a comprehensive understanding of image content and scenes, while for text, the retrieved evidence helps break the information silos caused by the closed and limited text and context. On the other hand, we consider inter-class differences between different emotional types of news through balanced learning, achieving fine-grained modeling of the relationship between emotional types and authenticity. Extensive experiments on two real-world datasets demonstrate the superiority of our KEN.

[Arxiv](https://arxiv.org/abs/2507.09647)