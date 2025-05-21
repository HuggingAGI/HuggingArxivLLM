# # PersonaTAB：基于全双工语音对话中的文本、语音和行为线索预测人格特质

发布时间：2025年05月20日

`LLM应用` `对话系统` `语音处理`

> PersonaTAB: Predicting Personality Traits using Textual, Acoustic, and Behavioral Cues in Fully-Duplex Speech Dialogs

# 摘要

> 尽管神经对话系统发展迅速，但个性感知对话代理的研究仍显不足，主要原因是现有语音数据集缺乏个性标注。为此，我们提出了一套预处理方案，将原始音频转化为包含时间戳、对话类型及情感标签的结构化对话数据集。通过自动语音识别（ASR）技术提取文本和时间信息后，我们进一步生成对话级别的详细标注。基于这些标注，我们开发了一套系统，借助大型语言模型实现个性特征的精准预测。在人工评估员的帮助下，我们不仅识别出对话中的关键特征，还为其分配了个性标签。实验结果表明，与现有方法相比，我们的系统在预测结果与人类判断的一致性上表现更优。

> Despite significant progress in neural spoken dialog systems, personality-aware conversation agents -- capable of adapting behavior based on personalities -- remain underexplored due to the absence of personality annotations in speech datasets. We propose a pipeline that preprocesses raw audio recordings to create a dialogue dataset annotated with timestamps, response types, and emotion/sentiment labels. We employ an automatic speech recognition (ASR) system to extract transcripts and timestamps, then generate conversation-level annotations. Leveraging these annotations, we design a system that employs large language models to predict conversational personality. Human evaluators were engaged to identify conversational characteristics and assign personality labels. Our analysis demonstrates that the proposed system achieves stronger alignment with human judgments compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2505.14356)