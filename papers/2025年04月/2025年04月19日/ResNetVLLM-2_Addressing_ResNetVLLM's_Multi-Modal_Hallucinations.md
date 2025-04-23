# ResNetVLLM-2：解决多模态幻觉问题

发布时间：2025年04月19日

`RAG` `视频处理` `视频分析`

> ResNetVLLM-2: Addressing ResNetVLLM's Multi-Modal Hallucinations

# 摘要

> 大型语言模型 (LLMs) 已经彻底改变了自然语言处理 (NLP) 任务，但它们面临着幻觉问题的困扰，会生成看似合理却事实错误的内容。这一问题也影响了视频语言模型 (VideoLLMs)，其中文本描述可能无法准确反映视觉内容，导致多模态幻觉的产生。在本文中，我们针对 ResNetVLLM 这一结合了 ResNet 视觉编码器与 LLM 的视频语言模型的幻觉问题进行研究。我们提出了一种两步协议：(1) 一种基于修改后的 Lynx 模型的忠实度检测策略，用于评估生成字幕与真实视频参考之间的语义对齐程度；(2) 一种基于检索增强生成 (RAG) 的幻觉缓解策略，使用在推理过程中动态构建的自定义知识库。我们的增强版模型 ResNetVLLM-2 通过与外部知识的交叉验证减少了多模态幻觉，提高了事实一致性。在 ActivityNet-QA 基准测试中的评估显示，准确率从 54.8% 显著提升至 65.3%，凸显了我们幻觉检测与缓解策略在提升视频语言模型可靠性方面的有效性。

> Large Language Models (LLMs) have transformed natural language processing (NLP) tasks, but they suffer from hallucination, generating plausible yet factually incorrect content. This issue extends to Video-Language Models (VideoLLMs), where textual descriptions may inaccurately represent visual content, resulting in multi-modal hallucinations. In this paper, we address hallucination in ResNetVLLM, a video-language model combining ResNet visual encoders with LLMs. We introduce a two-step protocol: (1) a faithfulness detection strategy that uses a modified Lynx model to assess semantic alignment between generated captions and ground-truth video references, and (2) a hallucination mitigation strategy using Retrieval-Augmented Generation (RAG) with an ad-hoc knowledge base dynamically constructed during inference. Our enhanced model, ResNetVLLM-2, reduces multi-modal hallucinations by cross-verifying generated content against external knowledge, improving factual consistency. Evaluation on the ActivityNet-QA benchmark demonstrates a substantial accuracy increase from 54.8% to 65.3%, highlighting the effectiveness of our hallucination detection and mitigation strategies in enhancing video-language model reliability.

[Arxiv](https://arxiv.org/abs/2504.14429)