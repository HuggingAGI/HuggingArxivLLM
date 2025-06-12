# VersaVid-R1: 多功能视频理解与推理模型，涵盖问答到字幕生成等多种任务

发布时间：2025年06月09日

`LLM应用` `视频处理`

> VersaVid-R1: A Versatile Video Understanding and Reasoning Model from Question Answering to Captioning Tasks

# 摘要

> 多模态大型语言模型近期取得了显著进展，成功将“先思考后回应”范式扩展至图像推理领域。然而，视频推理仍是一片未充分开发的前沿，主要受限于高质量推理数据的稀缺和有效训练方法的匮乏。为填补这一空白，我们推出了DarkEventInfer和MixVidQA两个全新数据集，旨在激发模型在视频理解与推理方面的高级能力。DarkEventInfer通过展示带有遮蔽事件片段的视频，要求模型依据视频上下文线索推断被遮挡内容。MixVidQA则呈现由两段不同片段交织而成的视频序列，挑战模型在忽略另一片段的同时，专注于其中一段并进行推理。借助这些精心筛选的训练样本，结合由多样奖励函数引导的强化学习，我们开发出了VersaVid-R1——首个在“先思考后回应”范式下兼具多选题解答、开放性问题回答以及视频描述生成能力的多功能视频理解与推理模型。实验结果表明，VersaVid-R1在涵盖视频通用理解、认知推理及描述生成等广泛基准测试中，显著超越现有模型表现。

> Recent advancements in multimodal large language models have successfully extended the Reason-Then-Respond paradigm to image-based reasoning, yet video-based reasoning remains an underdeveloped frontier, primarily due to the scarcity of high-quality reasoning-oriented data and effective training methodologies. To bridge this gap, we introduce DarkEventInfer and MixVidQA, two novel datasets specifically designed to stimulate the model's advanced video understanding and reasoning abilities. DarkEventinfer presents videos with masked event segments, requiring models to infer the obscured content based on contextual video cues. MixVidQA, on the other hand, presents interleaved video sequences composed of two distinct clips, challenging models to isolate and reason about one while disregarding the other. Leveraging these carefully curated training samples together with reinforcement learning guided by diverse reward functions, we develop VersaVid-R1, the first versatile video understanding and reasoning model under the Reason-Then-Respond paradigm capable of handling multiple-choice and open-ended question answering, as well as video captioning tasks. Extensive experiments demonstrate that VersaVid-R1 significantly outperforms existing models across a broad spectrum of benchmarks, covering video general understanding, cognitive reasoning, and captioning tasks.

[Arxiv](https://arxiv.org/abs/2506.09079)