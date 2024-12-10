# [CLS] 令牌涵盖了无训练高效 MLLMs 所需的全部内容

发布时间：2024年12月08日

`LLM应用` `计算机视觉` `多模态语言模型`

> [CLS] Token Tells Everything Needed for Training-free Efficient MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）近来在众多视觉语言任务中表现抢眼，在计算机视觉领域备受瞩目。然而，因其高昂的计算成本和内存需求，其有效部署面临重大挑战。鉴于视觉模态中信息的冗余性，近期研究探索了在 MLLMs 中压缩视觉标记以实现无训练提效的方法。尽管成效显著，但诸如 Fast 等现有方法将视觉标记与提示文本标记之间的注意力视作重要性指标，却忽略了与响应文本的相关性，进而导致感知偏差。本文指出，在 MLLMs 中，视觉编码器里的[CLS]标记天然知晓哪些视觉标记对 MLLMs 至关重要。基于此，我们推出一种简便且高效的无训练视觉标记压缩法，名为 VTC-CLS。首先，它借助[CLS]标记对视觉标记的注意力得分来作为修剪视觉标记的重要性指标。另外，我们还尝试将[CLS]标记从不同层得出的重要性得分加以集成，从而更全面地捕捉关键视觉信息。大量实验表明，与基线方法相比，我们的 VTC-CLS 在各类任务中均达到了顶尖水平。它还以无训练的方式大幅降低了计算成本，彰显出其有效性和优越性。代码和模型可在 url{https://github.com/THU-MIG/VTC-CLS}获取。

> Multimodal Large Language Models (MLLMs) have recently demonstrated strong performance across a wide range of vision-language tasks, garnering significant attention in the computer vision. However, their efficient deployment remains a substantial challenge due to high computational costs and memory requirements. Recognizing the redundancy of information within the vision modality, recent studies have explored methods for compressing visual tokens in MLLMs to enhance efficiency in a training-free manner. Despite their effectiveness, existing methods like Fast rely on the attention between visual tokens and prompt text tokens as the importance indicator, overlooking the relevance to response text and thus introducing perception bias. In this paper, we demonstrate that in MLLMs, the [CLS] token in the visual encoder inherently knows which visual tokens are important for MLLMs. Building on this prior, we introduce a simple yet effective method for train-free visual token compression, called VTC-CLS. Firstly, it leverages the attention score of the [CLS] token on visual tokens as an importance indicator for pruning visual tokens. Besides, we also explore ensembling the importance scores derived by the [CLS] token from different layers to capture the key visual information more comprehensively. Extensive experiments demonstrate that our VTC-CLS achieves the state-of-the-art performance across various tasks compared with baseline methods. It also brings notably less computational costs in a training-free manner, highlighting its effectiveness and superiority. Code and models are available at \url{https://github.com/THU-MIG/VTC-CLS}.

[Arxiv](https://arxiv.org/abs/2412.05819)