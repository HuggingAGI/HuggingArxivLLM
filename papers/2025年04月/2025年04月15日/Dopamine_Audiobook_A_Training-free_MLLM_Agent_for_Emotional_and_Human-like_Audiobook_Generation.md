# 多巴胺有声读物：无需训练的多语言生成模型，用于情感化和人性化的有声读物生成

发布时间：2025年04月15日

`LLM应用` `音频生成` `内容生成`

> Dopamine Audiobook: A Training-free MLLM Agent for Emotional and Human-like Audiobook Generation

# 摘要

> 有声读物生成技术致力于创造生动且富有情感的音频作品，但在传达复杂情感、实现类人特质以及与人类偏好保持一致的评估方面仍面临诸多挑战。现有的文本到语音（TTS）方法往往局限于特定场景，难以应对情感转换，并且缺乏与人类偏好一致的自动评估基准，通常依赖于不匹配的自动化指标或昂贵的人工评估。为了解决这些问题，我们提出了Dopamine Audiobook——一个基于多模态大型语言模型（MLLM）作为AI代理的新一代无训练统一系统，专注于情感化和类人类有声读物的生成与评估。具体而言，我们设计了一个基于流程的情感增强框架，将复杂的情感语音合成分解为可控的子任务。同时，我们开发了一种自适应模型选择模块，能够动态地从现有的最先进的（SOTA）TTS方法中选择最适合当前场景的方法。我们进一步通过副语言增强和单词及语句级别的 prosody 检索来提升情感表达力。在评估方面，我们提出了一种基于GPT的新型评估框架，集成了自我批判、换位思考以及心理 MagicEmo 提示，以确保评估既符合人类偏好又具有自我一致性。实验结果表明，我们的方法在各种指标下生成的长语音在情感表达方面优于现有的 SOTA TTS 模型。更重要的是，我们的评估框架在与人类偏好保持一致性和跨音频任务的迁移性方面表现更优。包含音频样本的项目网站可访问 https://dopamine-audiobook.github.io 查看。

> Audiobook generation, which creates vivid and emotion-rich audio works, faces challenges in conveying complex emotions, achieving human-like qualities, and aligning evaluations with human preferences. Existing text-to-speech (TTS) methods are often limited to specific scenarios, struggle with emotional transitions, and lack automatic human-aligned evaluation benchmarks, instead relying on either misaligned automated metrics or costly human assessments. To address these issues, we propose Dopamine Audiobook, a new unified training-free system leveraging a multimodal large language model (MLLM) as an AI agent for emotional and human-like audiobook generation and evaluation. Specifically, we first design a flow-based emotion-enhanced framework that decomposes complex emotional speech synthesis into controllable sub-tasks. Then, we propose an adaptive model selection module that dynamically selects the most suitable TTS methods from a set of existing state-of-the-art (SOTA) TTS methods for diverse scenarios. We further enhance emotional expressiveness through paralinguistic augmentation and prosody retrieval at word and utterance levels. For evaluation, we propose a novel GPT-based evaluation framework incorporating self-critique, perspective-taking, and psychological MagicEmo prompts to ensure human-aligned and self-aligned assessments. Experiments show that our method generates long speech with superior emotional expression to SOTA TTS models in various metrics. Importantly, our evaluation framework demonstrates better alignment with human preferences and transferability across audio tasks. Project website with audio samples can be found at https://dopamine-audiobook.github.io.

[Arxiv](https://arxiv.org/abs/2504.11002)