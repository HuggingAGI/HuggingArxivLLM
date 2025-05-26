# CosyVoice 3：通过扩展与后训练实现真实场景语音生成

发布时间：2025年05月23日

`LLM应用` `语音合成` `语音技术`

> CosyVoice 3: Towards In-the-wild Speech Generation via Scaling-up and Post-training

# 摘要

> # CosyVoice 3：新一代多语言语音合成模型

在前期研究中，我们推出了 CosyVoice 2，一个结合大型语言模型 (LLM) 和分块感知流匹配 (FM) 模型的可扩展流式语音合成系统。它实现了低延迟双流式语音合成，语音质量可与人类相媲美。然而，CosyVoice 2在语言覆盖范围、领域多样性、数据量、文本格式和后训练技术方面仍存在局限性。

今天，我们很高兴推出全新升级的 CosyVoice 3。这一代模型专为野外环境下的零样本多语言语音合成而设计，在内容一致性、说话人相似性和韵律自然度方面较前代有了显著提升。以下是 CosyVoice 3 的四大核心亮点：

1. **创新语音分词器**：通过监督多任务训练（包括自动语音识别、语音情感识别、语言识别、音频事件检测和说话人分析），显著提升了语音韵律的自然度。

2. **通用可微分奖励模型**：这一后训练技术不仅适用于 CosyVoice 3，还可赋能其他基于 LLM 的语音合成模型，进一步提升语音质量。

3. **海量数据集支持**：训练数据规模从1万小时大幅扩充至100万小时，覆盖9种语言和18种中文方言，涵盖丰富领域和文本格式。

4. **模型性能升级**：模型参数从0.5亿提升至1.5亿，更大的模型容量带来了多语言基准测试中的显著性能提升。

这些技术突破为野外语音合成领域树立了新的标杆。我们诚挚邀请您访问 https://funaudiollm.github.io/cosyvoice3，亲耳聆听 CosyVoice 3 的卓越表现！

> In our prior works, we introduced a scalable streaming speech synthesis model, CosyVoice 2, which integrates a large language model (LLM) and a chunk-aware flow matching (FM) model, and achieves low-latency bi-streaming speech synthesis and human-parity quality. Despite these advancements, CosyVoice 2 exhibits limitations in language coverage, domain diversity, data volume, text formats, and post-training techniques. In this paper, we present CosyVoice 3, an improved model designed for zero-shot multilingual speech synthesis in the wild, surpassing its predecessor in content consistency, speaker similarity, and prosody naturalness. Key features of CosyVoice 3 include: 1) A novel speech tokenizer to improve prosody naturalness, developed via supervised multi-task training, including automatic speech recognition, speech emotion recognition, language identification, audio event detection, and speaker analysis. 2) A new differentiable reward model for post-training applicable not only to CosyVoice 3 but also to other LLM-based speech synthesis models. 3) Dataset Size Scaling: Training data is expanded from ten thousand hours to one million hours, encompassing 9 languages and 18 Chinese dialects across various domains and text formats. 4) Model Size Scaling: Model parameters are increased from 0.5 billion to 1.5 billion, resulting in enhanced performance on our multilingual benchmark due to the larger model capacity. These advancements contribute significantly to the progress of speech synthesis in the wild. We encourage readers to listen to the demo at https://funaudiollm.github.io/cosyvoice3.

[Arxiv](https://arxiv.org/abs/2505.17589)