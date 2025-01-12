# 利用半监督学习和LLMs优化爱沙尼亚电视字幕

发布时间：2025年01月09日

`LLM应用

理由：该论文描述了如何利用Whisper模型和LLM（大型语言模型）进行字幕生成和优化，属于LLM在实际应用中的使用场景，因此分类为LLM应用。`

> Optimizing Estonian TV Subtitles with Semi-supervised Learning and LLMs

# 摘要

> 本文介绍了一种为爱沙尼亚电视内容生成高质量同语言字幕的方法。我们基于人工生成的字幕微调了Whisper模型，并通过迭代伪标签和LLM后编辑进行优化。实验表明，使用未标注数据集的伪标签显著提升了字幕质量。测试时应用LLM编辑能提高准确性，但训练时使用则无额外收益。该方法有望实现接近人类标准的字幕质量，并可扩展至实时应用。

> This paper presents an approach for generating high-quality, same-language subtitles for Estonian TV content. We fine-tune the Whisper model on human-generated Estonian subtitles and enhance it with iterative pseudo-labeling and large language model (LLM) based post-editing. Our experiments demonstrate notable subtitle quality improvement through pseudo-labeling with an unlabeled dataset. We find that applying LLM-based editing at test time enhances subtitle accuracy, while its use during training does not yield further gains. This approach holds promise for creating subtitle quality close to human standard and could be extended to real-time applications.

[Arxiv](https://arxiv.org/abs/2501.05234)