# SARGes：基于意图链的语义对齐可靠手势生成

发布时间：2025年03月25日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于手势生成，具体是通过解析语音内容来生成语义手势标签，从而指导共同演讲手势的合成。这属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `人机交互` `计算机图形学`

> SARGes: Semantically Aligned Reliable Gesture Generation via Intent Chain

# 摘要

> 通过与语音同步的手势合成技术，共同演讲手势生成显著提升了人机交互的沉浸感。然而，如何生成具有语义意义的手势仍然是一个亟待解决的难题。我们提出了一种名为SARGes的新颖框架，该框架借助大型语言模型（LLMs）解析语音内容，并生成可靠的语义手势标签，从而指导有意义的共同演讲手势的合成。首先，我们构建了一个全面的共同演讲手势行为学图谱，并开发了一种基于LLMs的意图链推理机制。该机制能够根据行为学图谱标准，系统地解析和分解手势语义，将其转化为结构化的推理步骤，从而有效引导LLMs生成上下文感知的手势标签。随后，我们构建了一个意图链标注的文本到手势标签数据集，并训练了一个轻量级的手势标签生成模型。该模型能够指导生成可信且语义连贯的共同演讲手势。实验结果表明，SARGes在高语义对齐的手势标注上达到了50.2%的准确率，并且单次推理效率高达0.4秒。所提出的方法为语义手势合成提供了一条清晰的意图推理路径。

> Co-speech gesture generation enhances human-computer interaction realism through speech-synchronized gesture synthesis. However, generating semantically meaningful gestures remains a challenging problem. We propose SARGes, a novel framework that leverages large language models (LLMs) to parse speech content and generate reliable semantic gesture labels, which subsequently guide the synthesis of meaningful co-speech gestures.First, we constructed a comprehensive co-speech gesture ethogram and developed an LLM-based intent chain reasoning mechanism that systematically parses and decomposes gesture semantics into structured inference steps following ethogram criteria, effectively guiding LLMs to generate context-aware gesture labels. Subsequently, we constructed an intent chain-annotated text-to-gesture label dataset and trained a lightweight gesture label generation model, which then guides the generation of credible and semantically coherent co-speech gestures. Experimental results demonstrate that SARGes achieves highly semantically-aligned gesture labeling (50.2% accuracy) with efficient single-pass inference (0.4 seconds). The proposed method provides an interpretable intent reasoning pathway for semantic gesture synthesis.

[Arxiv](https://arxiv.org/abs/2503.20202)