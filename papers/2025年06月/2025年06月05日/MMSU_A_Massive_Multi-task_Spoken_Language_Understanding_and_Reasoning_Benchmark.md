# MMSU: 大规模多任务语音理解和推理基准测试

发布时间：2025年06月05日

`LLM应用` `语音处理` `语音交互`

> MMSU: A Massive Multi-task Spoken Language Understanding and Reasoning Benchmark

# 摘要

> 语音不仅承载着语言本身，还蕴含着丰富的声学信息，远超出文字表达的范畴。在实际的语音理解场景中，有效解析语音往往需要结合语义内容、情感色彩、语速、音调等副语言特征，以及韵律、语调、节奏等音系特征。尽管当前的多模态语音大语言模型（SpeechLLMs）在处理音频信息方面表现出色，但它们在自然语音中的精细感知与复杂推理能力仍有待深入探索。为此，我们推出了MMSU——一个专注于语音理解和推理的全面基准测试。MMSU包含了经过精心筛选的47项任务中的5,000个音频-问题-答案三元组。为了确保基准测试的科学性，我们系统性地整合了语音学、韵律学、修辞学、句法学、语义学和副语言学等多维度的语言现象。通过对14个先进SpeechLLMs的严格评估，我们发现现有模型在语音理解方面仍有显著提升空间，同时也为未来的研究优化指明了方向。MMSU不仅为语音理解能力的全面评估设立了新标准，更为打造更智能的语音交互系统提供了宝贵的研究视角。MMSU基准测试现已开放，访问地址为https://huggingface.co/datasets/ddwang2000/MMSU，评估代码可从https://github.com/dingdongwang/MMSU_Bench获取。

> Speech inherently contains rich acoustic information that extends far beyond the textual language. In real-world spoken language understanding, effective interpretation often requires integrating semantic meaning (e.g., content), paralinguistic features (e.g., emotions, speed, pitch) and phonological characteristics (e.g., prosody, intonation, rhythm), which are embedded in speech. While recent multimodal Speech Large Language Models (SpeechLLMs) have demonstrated remarkable capabilities in processing audio information, their ability to perform fine-grained perception and complex reasoning in natural speech remains largely unexplored. To address this gap, we introduce MMSU, a comprehensive benchmark designed specifically for understanding and reasoning in spoken language. MMSU comprises 5,000 meticulously curated audio-question-answer triplets across 47 distinct tasks. To ground our benchmark in linguistic theory, we systematically incorporate a wide range of linguistic phenomena, including phonetics, prosody, rhetoric, syntactics, semantics, and paralinguistics. Through a rigorous evaluation of 14 advanced SpeechLLMs, we identify substantial room for improvement in existing models, highlighting meaningful directions for future optimization. MMSU establishes a new standard for comprehensive assessment of spoken language understanding, providing valuable insights for developing more sophisticated human-AI speech interaction systems. MMSU benchmark is available at https://huggingface.co/datasets/ddwang2000/MMSU. Evaluation Code is available at https://github.com/dingdongwang/MMSU_Bench.

[Arxiv](https://arxiv.org/abs/2506.04779)