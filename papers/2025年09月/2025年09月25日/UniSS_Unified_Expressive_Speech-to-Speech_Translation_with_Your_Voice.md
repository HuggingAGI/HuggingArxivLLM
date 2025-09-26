# UniSS：用你的声音实现统一且富有表现力的语音转语音翻译

发布时间：2025年09月25日

`LLM应用` `媒体与娱乐`

> UniSS: Unified Expressive Speech-to-Speech Translation with Your Voice

# 摘要

> 表达性语音到语音翻译（S2ST）的终极目标是准确翻译语音内容，同时保留说话人身份与情感风格。然而，该领域的进展却因三大关键挑战而严重受阻：具备表达性风格的成对语音数据稀缺、多阶段处理流水线复杂，以及大型语言模型（LLMs）的翻译能力迁移受限。为此，本研究提出全新单阶段表达性S2ST框架UniSS，以应对上述挑战。该框架通过精心设计的语音语义与风格建模方法，实现了与现有文本基LLM框架的无缝集成，进而构建出统一的文本-语音语言模型。为将翻译能力从文本迁移至语音，我们创新性地提出跨模态思维链提示过程，可逐步对齐音频语义与文本，并确保解码结果的风格保真。此外，我们构建并发布了大规模高质量表达性S2ST数据集UniST，涵盖44.8千小时数据。实验结果显示，UniSS在翻译保真度和语音质量上显著超越现有方法，同时完美保持语音、情感与时长的一致性。本研究为下一代表达性S2ST系统的构建奠定了更简洁高效的新范式。音频样本详见https://cmots.github.io/uniss-demo。

> The ultimate goal of expressive speech-to-speech translation (S2ST) is to accurately translate spoken content while preserving the speaker identity and emotional style. However, progress in this field is largely hindered by three key challenges: the scarcity of paired speech data that retains expressive styles, the complexity of multi-stage processing pipelines, and the limited transfer of translation capabilities from large language models (LLMs). In this work, we address these challenges by introducing UniSS, a novel single-stage framework for expressive S2ST. Our approach features carefully designed speech semantic and style modeling, enabling seamless integration with existing text-based LLM frameworks to develop a unified text-speech language model. To transfer translation capabilities from text to speech, we propose a cross-modal chain-of-thought prompting process that progressively aligns audio semantics with text and ensures style preservation in the decoded results. Furthermore, we construct and release a large-scale, high-quality expressive S2ST dataset, UniST, comprising 44.8k hours of data. Experimental results show that UniSS significantly outperforms previous methods in translation fidelity and speech quality while preserving voice, emotion, and duration consistency. Our work establishes a simpler and more effective paradigm for building the next generation of expressive S2ST systems. Audio samples are available at https://cmots.github.io/uniss-demo.

[Arxiv](https://arxiv.org/abs/2509.21144)