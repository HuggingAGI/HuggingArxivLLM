# 多模态大型语言模型的口语讽刺理解评估

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Evaluating Multimodal Large Language Models on Spoken Sarcasm Understanding

# 摘要

> 在自然语言理解领域，讽刺检测一直是一项难题——这是由于讽刺意图往往依赖于跨越文本、语音和视觉的微妙跨模态线索。尽管以往研究多聚焦于文本或视觉-文本讽刺，然而视听-文本的综合讽刺理解尚未得到充分探索。本文系统评估了大型语言模型（LLMs）与多模态大型语言模型（MLLMs）在英文（MUStARD++）和中文（MCSD 1.0）数据集上的讽刺检测能力，涵盖零样本、少样本及LoRA微调三种设置。除直接分类外，我们还探索将模型作为特征编码器，借助协作门控融合模块对其表示进行整合。实验结果显示，基于音频的模型单模态表现最佳，而文本-音频与音频-视觉的组合性能优于单模态和三模态模型。此外，Qwen-Omni等多模态大型语言模型在零样本和微调场景下均展现出具有竞争力的性能。研究结果表明，多模态大型语言模型在跨语言视听-文本讽刺理解任务中具有巨大潜力。

> Sarcasm detection remains a challenge in natural language understanding, as sarcastic intent often relies on subtle cross-modal cues spanning text, speech, and vision. While prior work has primarily focused on textual or visual-textual sarcasm, comprehensive audio-visual-textual sarcasm understanding remains underexplored. In this paper, we systematically evaluate large language models (LLMs) and multimodal LLMs for sarcasm detection on English (MUStARD++) and Chinese (MCSD 1.0) in zero-shot, few-shot, and LoRA fine-tuning settings. In addition to direct classification, we explore models as feature encoders, integrating their representations through a collaborative gating fusion module. Experimental results show that audio-based models achieve the strongest unimodal performance, while text-audio and audio-vision combinations outperform unimodal and trimodal models. Furthermore, MLLMs such as Qwen-Omni show competitive zero-shot and fine-tuned performance. Our findings highlight the potential of MLLMs for cross-lingual, audio-visual-textual sarcasm understanding.

[Arxiv](https://arxiv.org/abs/2509.15476)