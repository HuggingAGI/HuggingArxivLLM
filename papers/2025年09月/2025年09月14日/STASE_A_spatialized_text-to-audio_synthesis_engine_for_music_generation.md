# STASE：面向音乐生成的空间化文本转音频合成引擎

发布时间：2025年09月14日

`Agent` `媒体与娱乐`

> STASE: A spatialized text-to-audio synthesis engine for music generation

# 摘要

> 尽管许多文本转音频系统能生成单声道或固定立体声输出，但生成具备用户自定义空间属性的音频仍是一大难点。现有基于深度学习的空间化方法往往依赖潜在空间操作，这可能限制对空间感知关键的心理声学参数的直接控制。为此，我们提出STASE系统，它将大型语言模型（LLM）作为智能体，用于从文本中解读空间线索。STASE的核心特点在于将语义解读与独立的物理空间渲染引擎解耦，从而实现可解释且用户可控的空间推理。LLM通过两条主要路径处理提示：（i）描述性提示，直接映射显式空间信息（例如“将主吉他置于方位角45°、距离10米处”）；（ii）抽象提示，通过检索增强生成（RAG）模块检索相关空间模板以指导渲染。本文详细阐述了STASE的工作流程，讨论了实现过程中的注意事项，并指出了当前生成式空间音频评估面临的挑战。

> While many text-to-audio systems produce monophonic or fixed-stereo outputs, generating audio with user-defined spatial properties remains a challenge. Existing deep learning-based spatialization methods often rely on latent-space manipulations, which can limit direct control over psychoacoustic parameters critical to spatial perception. To address this, we introduce STASE, a system that leverages a Large Language Model (LLM) as an agent to interpret spatial cues from text. A key feature of STASE is the decoupling of semantic interpretation from a separate, physics-based spatial rendering engine, which facilitates interpretable and user-controllable spatial reasoning. The LLM processes prompts through two main pathways: (i) Description Prompts, for direct mapping of explicit spatial information (e.g., "place the lead guitar at 45° azimuth, 10 m distance"), and (ii) Abstract Prompts, where a Retrieval-Augmented Generation (RAG) module retrieves relevant spatial templates to inform the rendering. This paper details the STASE workflow, discusses implementation considerations, and highlights current challenges in evaluating generative spatial audio.

[Arxiv](https://arxiv.org/abs/2509.11124)