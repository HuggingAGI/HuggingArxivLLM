# HOIGen-1M：大规模人-物交互视频生成数据集

发布时间：2025年03月31日

`LLM应用

理由：这篇论文主要讨论了文本到视频生成技术，特别是人与物交互（HOI）场景的生成。论文提出了一种大规模数据集HOIGen-1M，并利用多模态大语言模型（MLLMs）进行视频整理和描述生成。这些工作属于将大语言模型应用于特定任务，因此归类为LLM应用。` `视频生成` `数据集`

> HOIGen-1M: A Large-scale Dataset for Human-Object Interaction Video Generation

# 摘要

> 文本到视频（T2V）生成在复杂场景的文本驱动生成上取得了长足的进步。但受限于缺乏大规模、标注准确的HOI（人与物交互）视频数据，现有T2V模型往往难以精确生成人与物的交互场景。为解决这一问题，我们推出了首个针对HOI生成的大规模数据集HOIGen-1M，包含来自多个来源的超过一百万条高质量视频。我们首先设计了一个高效的框架，利用强大的多模态大语言模型（MLLMs）自动整理HOI视频，并由人工标注员进一步清洗，确保视频的高质量。为了获得准确的文本描述，我们基于多模态专家混合（MoME）策略设计了一种新型视频描述方法，不仅生成了生动的描述，还消除了单一MLLM的幻觉问题。此外，由于缺乏对生成HOI视频的评估框架，我们提出了两个新指标，以由粗到细的方式全面评估生成视频的质量。大量实验表明，现有T2V模型难以生成高质量的HOI视频，而我们的HOIGen-1M数据集对于提升HOI视频生成具有重要意义。项目网页地址为https://liuqi-creat.github.io/HOIGen.github.io。

> Text-to-video (T2V) generation has made tremendous progress in generating complicated scenes based on texts. However, human-object interaction (HOI) often cannot be precisely generated by current T2V models due to the lack of large-scale videos with accurate captions for HOI. To address this issue, we introduce HOIGen-1M, the first largescale dataset for HOI Generation, consisting of over one million high-quality videos collected from diverse sources. In particular, to guarantee the high quality of videos, we first design an efficient framework to automatically curate HOI videos using the powerful multimodal large language models (MLLMs), and then the videos are further cleaned by human annotators. Moreover, to obtain accurate textual captions for HOI videos, we design a novel video description method based on a Mixture-of-Multimodal-Experts (MoME) strategy that not only generates expressive captions but also eliminates the hallucination by individual MLLM. Furthermore, due to the lack of an evaluation framework for generated HOI videos, we propose two new metrics to assess the quality of generated videos in a coarse-to-fine manner. Extensive experiments reveal that current T2V models struggle to generate high-quality HOI videos and confirm that our HOIGen-1M dataset is instrumental for improving HOI video generation. Project webpage is available at https://liuqi-creat.github.io/HOIGen.github.io.

[Arxiv](https://arxiv.org/abs/2503.23715)