# Canary-1B-v2 & Parakeet-TDT-0.6B-v3：面向多语言ASR与AST的高效高性能模型

发布时间：2025年09月17日

`其他` `媒体与娱乐`

> Canary-1B-v2 & Parakeet-TDT-0.6B-v3: Efficient and High-Performance Models for Multilingual ASR and AST

# 摘要

> 本报告介绍了Canary-1B-v2——一款用于自动语音识别（ASR）与语音到文本翻译（AST）的快速且稳健的多语言模型。该模型采用FastConformer编码器与Transformer解码器架构，支持25种语言（主要为欧洲语言）。其训练数据总量达170万小时，涵盖Granary和NeMo ASR Set 3.0等数据集，并加入非语音音频以减少ASR与AST任务中的幻觉现象。我们详细阐述了模型的两阶段预训练与微调过程（含动态数据平衡），以及基于nGPT编码器的实验。结果显示，nGPT在海量数据下扩展性优异，而FastConformer经微调后性能更突出。在时间戳生成上，Canary-1B-v2结合NeMo强制对齐器（NFA）与辅助CTC模型，为ASR和AST提供可靠的片段级时间标记。评估结果表明，该模型在英语ASR任务上性能超越Whisper-large-v3，同时速度提升10倍；在多语言ASR和AST任务中，与Seamless-M4T-v2-large及基于LLM的系统等更大模型相比，也展现出极具竞争力的表现。此外，我们还发布了Parakeet-TDT-0.6B-v3（v2的升级版），仅需6亿参数即可支持上述25种语言的多语言ASR。

> This report introduces Canary-1B-v2, a fast, robust multilingual model for Automatic Speech Recognition (ASR) and Speech-to-Text Translation (AST). Built with a FastConformer encoder and Transformer decoder, it supports 25 languages primarily European. The model was trained on 1.7M hours of total data samples, including Granary and NeMo ASR Set 3.0, with non-speech audio added to reduce hallucinations for ASR and AST. We describe its two-stage pre-training and fine-tuning process with dynamic data balancing, as well as experiments with an nGPT encoder. Results show nGPT scales well with massive data, while FastConformer excels after fine-tuning. For timestamps, Canary-1B-v2 uses the NeMo Forced Aligner (NFA) with an auxiliary CTC model, providing reliable segment-level timestamps for ASR and AST. Evaluations show Canary-1B-v2 outperforms Whisper-large-v3 on English ASR while being 10x faster, and delivers competitive multilingual ASR and AST performance against larger models like Seamless-M4T-v2-large and LLM-based systems. We also release Parakeet-TDT-0.6B-v3, a successor to v2, offering multilingual ASR across the same 25 languages with just 600M parameters.

[Arxiv](https://arxiv.org/abs/2509.14128)