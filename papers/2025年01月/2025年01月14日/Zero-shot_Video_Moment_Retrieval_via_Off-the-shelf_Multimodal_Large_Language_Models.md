# 零-shot 视频片段检索：基于现成多模态大型语言模型

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了如何利用冻结的多模态大模型（MLLMs）和大型语言模型（LLaMA-3）来实现无需微调的零-shot视频片段检索（VMR）方案。该方法通过纠正和重述查询、生成候选跨度以及筛选最佳跨度等步骤，显著提升了VMR的性能。这些工作直接应用了大型语言模型和多模态大模型来解决实际问题，因此应归类为“LLM应用”。` `视频检索`

> Zero-shot Video Moment Retrieval via Off-the-shelf Multimodal Large Language Models

# 摘要

> 视频片段检索（VMR）旨在预测视频中与语言查询语义匹配的时间段。现有基于多模态大模型（MLLMs）的VMR方法过度依赖昂贵的高质量数据集和耗时的微调。尽管近期研究引入了零-shot设置以避免微调，但它们忽视了查询中的语言偏差，导致定位错误。为解决这些问题，本文提出了Moment-GPT，一种无需微调的零-shot VMR方案，利用冻结的MLLMs实现。具体而言，我们首先使用LLaMA-3纠正并重述查询，以减少语言偏差；接着设计了一个与MiniGPT-v2结合的跨度生成器，自适应生成候选跨度；最后，借助VideoChatGPT和跨度评分器，利用MLLMs的视频理解能力筛选最佳跨度。实验表明，该方法在QVHighlights、ActivityNet-Captions和Charades-STA等多个公开数据集上显著优于现有基于MLLMs和零-shot的模型。

> The target of video moment retrieval (VMR) is predicting temporal spans within a video that semantically match a given linguistic query. Existing VMR methods based on multimodal large language models (MLLMs) overly rely on expensive high-quality datasets and time-consuming fine-tuning. Although some recent studies introduce a zero-shot setting to avoid fine-tuning, they overlook inherent language bias in the query, leading to erroneous localization. To tackle the aforementioned challenges, this paper proposes Moment-GPT, a tuning-free pipeline for zero-shot VMR utilizing frozen MLLMs. Specifically, we first employ LLaMA-3 to correct and rephrase the query to mitigate language bias. Subsequently, we design a span generator combined with MiniGPT-v2 to produce candidate spans adaptively. Finally, to leverage the video comprehension capabilities of MLLMs, we apply VideoChatGPT and span scorer to select the most appropriate spans. Our proposed method substantially outperforms the state-ofthe-art MLLM-based and zero-shot models on several public datasets, including QVHighlights, ActivityNet-Captions, and Charades-STA.

[Arxiv](https://arxiv.org/abs/2501.07972)