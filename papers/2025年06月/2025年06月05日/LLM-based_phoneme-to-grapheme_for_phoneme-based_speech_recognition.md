# # 基于 LLM 的音素到字母转换方法，用于音素驱动的语音识别任务

发布时间：2025年06月05日

`LLM应用` `语音识别` `跨语言技术`

> LLM-based phoneme-to-grapheme for phoneme-based speech recognition

# 摘要

> 在自动语音识别领域，基于音素的多语言预训练和跨语言微调因数据效率高、效果优异而备受关注。然而，传统的基于WFST的解码方法存在流程复杂且无法充分利用LLMs的局限性。为此，我们提出了基于LLM的音素到音符（LLM-P2G）解码方案，该方案由语音到音素（S2P）和音素到音符（P2G）两部分组成。针对级联过程中可能的信息丢失问题，我们创新性地提出了两种策略：带噪声音素的数据增强（DANP）和随机化Top-$K$边缘化（TKM）训练与解码。实验结果表明，LLM-P2G在波兰语和德语的跨语言ASR任务中表现优异，分别实现了相对WER降低3.6%和6.9%的显著提升。

> In automatic speech recognition (ASR), phoneme-based multilingual pre-training and crosslingual fine-tuning is attractive for its high data efficiency and competitive results compared to subword-based models. However, Weighted Finite State Transducer (WFST) based decoding is limited by its complex pipeline and inability to leverage large language models (LLMs). Therefore, we propose LLM-based phoneme-to-grapheme (LLM-P2G) decoding for phoneme-based ASR, consisting of speech-to-phoneme (S2P) and phoneme-to-grapheme (P2G). A challenge is that there seems to have information loss in cascading S2P and P2G. To address this challenge, we propose two training strategies: data augmentation with noisy phonemes (DANP), and randomized top-$K$ marginalized (TKM) training and decoding. Our experimental results show that LLM-P2G outperforms WFST-based systems in crosslingual ASR for Polish and German, by relative WER reductions of 3.6% and 6.9% respectively.

[Arxiv](https://arxiv.org/abs/2506.04711)