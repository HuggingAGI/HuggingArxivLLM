# 通过插入不流畅来提升 LLM 生成话语的自然度

发布时间：2024年12月17日

`LLM应用` `语音合成` `对话代理`

> Enhancing Naturalness in LLM-Generated Utterances through Disfluency Insertion

# 摘要

> 不流畅是人类自然讲话的常见特征，然而在大型语言模型（LLMs）的输出里却往往不见其踪影。这一缺失会削弱合成语音的自然感，而这在构建旨在模仿人类行为的对话代理时是一项重要标准。我们展示了插入不流畅的方式能够弥补这一缺陷。所提出的方法包含（1）利用低秩适应（LoRA）对LLM进行微调，把各类不流畅融入LLM生成的话语中；（2）使用支持生成像不流畅这类语音现象的文本转语音模型来合成这些话语。我们通过两个指标——可理解性和感知的自发性来评估生成语音的质量。通过用户研究我们证明，插入不流畅显著提升了生成语音的感知自发性。不过，这种提升伴随着可理解性的略微下降。

> Disfluencies are a natural feature of spontaneous human speech but are typically absent from the outputs of Large Language Models (LLMs). This absence can diminish the perceived naturalness of synthesized speech, which is an important criteria when building conversational agents that aim to mimick human behaviours. We show how the insertion of disfluencies can alleviate this shortcoming. The proposed approach involves (1) fine-tuning an LLM with Low-Rank Adaptation (LoRA) to incorporate various types of disfluencies into LLM-generated utterances and (2) synthesizing those utterances using a text-to-speech model that supports the generation of speech phenomena such as disfluencies. We evaluated the quality of the generated speech across two metrics: intelligibility and perceived spontaneity. We demonstrate through a user study that the insertion of disfluencies significantly increase the perceived spontaneity of the generated speech. This increase came, however, along with a slight reduction in intelligibility.

[Arxiv](https://arxiv.org/abs/2412.12710)