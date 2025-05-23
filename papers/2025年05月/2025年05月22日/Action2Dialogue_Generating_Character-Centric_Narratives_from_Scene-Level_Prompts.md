# Action2Dialogue：构建基于场景级提示的以角色为中心的故事叙述

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型生成角色台词，并将其应用于视频生成，属于LLM的实际应用。` `视频生成`

> Action2Dialogue: Generating Character-Centric Narratives from Scene-Level Prompts

# 摘要

> 基于场景的视频生成领域近期取得了突破性进展，能够从结构化的提示生成连贯的视觉叙事。然而，叙事中的一个关键维度——以角色为中心的对话和语言表达——仍未得到充分探索。本文中，我们提出了一种模块化管道，将动作级别的提示转化为视觉和听觉上都有依据的叙述性对话，通过自然的声音和角色表情丰富视觉叙事。我们的方法每场景接受一对提示作为输入，其中第一个定义了场景设置，第二个指定了角色的行为。在故事生成模型如Text2Story生成相应的视觉场景的同时，我们专注于从这些提示和场景图像中生成具有表现力的角色台词。我们使用一个预训练的视觉语言编码器从代表帧中提取高层次的语义特征，捕捉显著的视觉上下文。该特征随后与结构化提示结合，并用于引导大型语言模型生成自然且角色一致的对话。为了确保场景之间的上下文一致性，我们引入了一个递归叙事库，使每次对话生成都基于之前场景积累的对话历史。这种方法使角色能够根据整个故事中不断演变的目标和互动来表达。最后，我们将每个台词渲染为具有表现力且角色一致的语音，从而生成完整的配音视频叙述。我们的框架无需额外训练，并且适用于多种故事场景，从奇幻冒险到日常生活片段。


> Recent advances in scene-based video generation have enabled systems to synthesize coherent visual narratives from structured prompts. However, a crucial dimension of storytelling -- character-driven dialogue and speech -- remains underexplored. In this paper, we present a modular pipeline that transforms action-level prompts into visually and auditorily grounded narrative dialogue, enriching visual storytelling with natural voice and character expression. Our method takes as input a pair of prompts per scene, where the first defines the setting and the second specifies a character's behavior. While a story generation model such as Text2Story generates the corresponding visual scene, we focus on generating expressive character utterances from these prompts and the scene image. We apply a pretrained vision-language encoder to extract a high-level semantic feature from the representative frame, capturing salient visual context. This feature is then combined with the structured prompts and used to guide a large language model in synthesizing natural, character-consistent dialogue. To ensure contextual consistency across scenes, we introduce a Recursive Narrative Bank that conditions each dialogue generation on the accumulated dialogue history from prior scenes. This approach enables characters to speak in ways that reflect their evolving goals and interactions throughout a story. Finally, we render each utterance as expressive, character-consistent speech, resulting in fully-voiced video narratives. Our framework requires no additional training and demonstrates applicability across a variety of story settings, from fantasy adventures to slice-of-life episodes.

[Arxiv](https://arxiv.org/abs/2505.16819)