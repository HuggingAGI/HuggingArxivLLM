# # 时间倒流：一个新颖的跨模态视频-文本检索基准，强调时间性

发布时间：2024年12月26日

`其他

理由：这篇论文主要讨论的是跨模态检索任务，特别是视频-文本检索，并提出了一个新的数据集RTime。虽然论文中提到了使用GPT-4生成字幕，但这并不是论文的核心内容。论文的重点在于数据集的设计和基准测试，属于多模态信息检索领域，而不是直接涉及LLM、Agent或RAG的应用或理论。因此，将其分类为“其他”更为合适。` `多媒体` `信息检索`

> Reversed in Time: A Novel Temporal-Emphasized Benchmark for Cross-Modal Video-Text Retrieval

# 摘要

> # 跨模态（如图像-文本、视频-文本）检索是信息检索和多模态视觉-语言理解领域的重要任务。时间理解使得视频-文本检索比图像-文本检索更具挑战性。然而，现有视频-文本基准测试在全面评估模型能力，尤其是时间理解方面存在不足，导致大规模图像-文本预训练模型已能与视频-文本预训练模型在零-shot性能上媲美。本文提出RTime，一个强调时间性的视频-文本检索数据集。我们首先获取具有显著时间性的动作或事件视频，并通过反转视频生成更难的负样本。随后，我们招募标注者评估视频的显著性和可逆性，并为合格视频编写字幕。进一步，我们利用GPT-4基于人工字幕生成更多字幕。RTime数据集目前包含21k个视频，每个视频有10个字幕，总计约122小时。基于RTime，我们设计了三个检索基准任务：RTime-Origin、RTime-Hard和RTime-Binary。我们还在模型训练中强化了更难负样本的使用，并对多种视频-文本模型进行了基准测试。大量实验证明，RTime为视频-文本检索带来了新的更高挑战。我们发布了RTime数据集ootnote{url{https://github.com/qyr0403/Reversed-in-Time}}，以推动视频-文本检索和多模态理解研究的进一步发展。

> Cross-modal (e.g. image-text, video-text) retrieval is an important task in information retrieval and multimodal vision-language understanding field. Temporal understanding makes video-text retrieval more challenging than image-text retrieval. However, we find that the widely used video-text benchmarks have shortcomings in comprehensively assessing abilities of models, especially in temporal understanding, causing large-scale image-text pre-trained models can already achieve comparable zero-shot performance with video-text pre-trained models. In this paper, we introduce RTime, a novel temporal-emphasized video-text retrieval dataset. We first obtain videos of actions or events with significant temporality, and then reverse these videos to create harder negative samples. We then recruit annotators to judge the significance and reversibility of candidate videos, and write captions for qualified videos. We further adopt GPT-4 to extend more captions based on human-written captions. Our RTime dataset currently consists of 21k videos with 10 captions per video, totalling about 122 hours. Based on RTime, we propose three retrieval benchmark tasks: RTime-Origin, RTime-Hard, and RTime-Binary. We further enhance the use of harder-negatives in model training, and benchmark a variety of video-text models on RTime. Extensive experiment analysis proves that RTime indeed poses new and higher challenges to video-text retrieval. We release our RTime dataset\footnote{\url{https://github.com/qyr0403/Reversed-in-Time}} to further advance video-text retrieval and multimodal understanding research.

[Arxiv](https://arxiv.org/abs/2412.19178)