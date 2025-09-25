# 面向ASR的检索增强生成式上下文发现

发布时间：2025年09月23日

`RAG` `基础理论`

> Retrieval Augmented Generation based context discovery for ASR

# 摘要

> 本研究探索将检索增强生成作为上下文感知自动语音识别（ASR）系统中自动发现上下文的高效策略，旨在提升罕见或词汇外术语场景下的转录准确性。然而，如何自动识别合适的上下文仍是一个亟待解决的难题。为此，本研究提出一种基于嵌入的高效检索方法，用于ASR系统的自动上下文发现。为验证该方法的有效性，研究还评估了两种基于大型语言模型（LLMs）的替代方案：（1）通过提示生成基于LLM的上下文；（2）利用LLMs对识别后的转录文本进行校正。在TED-LIUMv3、Earnings21和SPGISpeech数据集上的实验显示，与无上下文设置相比，所提方法可将词错误率（WER）降低17%（百分比差异），而理想上下文的WER降幅最高达24.1%。

> This work investigates retrieval augmented generation as an efficient strategy for automatic context discovery in context-aware Automatic Speech Recognition (ASR) system, in order to improve transcription accuracy in the presence of rare or out-of-vocabulary terms. However, identifying the right context automatically remains an open challenge. This work proposes an efficient embedding-based retrieval approach for automatic context discovery in ASR. To contextualize its effectiveness, two alternatives based on large language models (LLMs) are also evaluated: (1) large language model (LLM)-based context generation via prompting, and (2) post-recognition transcript correction using LLMs. Experiments on the TED-LIUMv3, Earnings21 and SPGISpeech demonstrate that the proposed approach reduces WER by up to 17% (percentage difference) relative to using no-context, while the oracle context results in a reduction of up to 24.1%.

[Arxiv](https://arxiv.org/abs/2509.19567)