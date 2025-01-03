# Amuse: 多模态灵感驱动的人机协作歌曲创作

发布时间：2024年12月25日

`LLM应用

理由：这篇论文描述了一个名为Amuse的歌曲创作助手，它利用多模态大型语言模型（LLMs）将多模态输入（如图像、文本或音频）转化为和弦建议，并通过单模态和弦模型进行筛选。这一过程展示了LLM在实际应用中的使用，特别是在音乐创作领域的应用。因此，这篇论文应被分类为“LLM应用”。` `创作工具`

> Amuse: Human-AI Collaborative Songwriting with Multimodal Inspirations

# 摘要

> # 摘要
歌曲创作常受多模态灵感驱动，如图像、叙事或现有音乐，但现有音乐AI系统未能支持创作者将这些多模态输入融入创作过程。我们推出Amuse，一款歌曲创作助手，能将多模态（图像、文本或音频）输入转化为和弦进行，无缝融入创作流程。Amuse的核心创新在于，即便缺乏多模态输入与和弦配对的数据集，也能生成与音乐关键词相关的连贯和弦。具体方法为：利用多模态大型语言模型（LLMs）将多模态输入转化为初步和弦建议，再通过单模态和弦模型进行筛选。用户研究表明，Amuse能有效将多模态灵感转化为连贯的音乐建议，提升创作者在歌曲创作中的自主性与创造力。

> Songwriting is often driven by multimodal inspirations, such as imagery, narratives, or existing music, yet songwriters remain unsupported by current music AI systems in incorporating these multimodal inputs into their creative processes. We introduce Amuse, a songwriting assistant that transforms multimodal (image, text, or audio) inputs into chord progressions that can be seamlessly incorporated into songwriters' creative processes. A key feature of Amuse is its novel method for generating coherent chords that are relevant to music keywords in the absence of datasets with paired examples of multimodal inputs and chords. Specifically, we propose a method that leverages multimodal large language models (LLMs) to convert multimodal inputs into noisy chord suggestions and uses a unimodal chord model to filter the suggestions. A user study with songwriters shows that Amuse effectively supports transforming multimodal ideas into coherent musical suggestions, enhancing users' agency and creativity throughout the songwriting process.

[Arxiv](https://arxiv.org/abs/2412.18940)