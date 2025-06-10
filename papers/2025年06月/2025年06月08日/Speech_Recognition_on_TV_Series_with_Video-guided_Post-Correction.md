# # 基于视频引导后校正的电视剧语音识别

发布时间：2025年06月08日

`LLM应用` `语音识别` `视频处理`

> Speech Recognition on TV Series with Video-guided Post-Correction

# 摘要

> 深度学习推动下，自动语音识别 (ASR) 在对话式 AI、媒体转录和辅助技术领域取得了突破性进展。然而，面对电视剧等复杂场景，ASR 系统仍面临重叠语音、领域术语及长距离上下文依赖等挑战，严重影响了转录质量。现有方法未能充分利用视频中的时空和上下文信息来优化 ASR 输出。为此，我们提出了一种创新的多模态后校正框架，通过视频中的上下文信息来优化 ASR 转录。该框架分为 ASR 生成和视频后校正两个阶段：第一阶段生成初始转录，第二阶段则通过基于视频的上下文信息提取和上下文感知校正技术来修正错误。我们采用 Video-Large 多模态模型 (VLMM) 通过定制提示提取关键上下文信息，并结合大型语言模型 (LLM) 进一步优化 ASR 输出。在电视剧 ASR 的多模态基准测试中，我们的方法通过视频上下文显著提升了复杂场景下的转录准确性，展现了其在提升 ASR 性能方面的有效性。

> Automatic Speech Recognition (ASR) has achieved remarkable success with deep learning, driving advancements in conversational artificial intelligence, media transcription, and assistive technologies. However, ASR systems still struggle in complex environments such as TV series, where overlapping speech, domain-specific terminology, and long-range contextual dependencies pose significant challenges to transcription accuracy. Existing multimodal approaches fail to correct ASR outputs with the rich temporal and contextual information available in video. To address this limitation, we propose a novel multimodal post-correction framework that refines ASR transcriptions by leveraging contextual cues extracted from video. Our framework consists of two stages: ASR Generation and Video-based Post-Correction, where the first stage produces the initial transcript and the second stage corrects errors using Video-based Contextual Information Extraction and Context-aware ASR Correction. We employ the Video-Large Multimodal Model (VLMM) to extract key contextual information using tailored prompts, which is then integrated with a Large Language Model (LLM) to refine the ASR output. We evaluate our method on a multimodal benchmark for TV series ASR and demonstrate its effectiveness in improving ASR performance by leveraging video-based context to enhance transcription accuracy in complex multimedia environments.

[Arxiv](https://arxiv.org/abs/2506.07323)