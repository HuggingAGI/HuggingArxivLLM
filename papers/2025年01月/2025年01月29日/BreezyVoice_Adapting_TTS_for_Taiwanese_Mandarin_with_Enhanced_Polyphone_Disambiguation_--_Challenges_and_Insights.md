# BreezyVoice: 为台湾普通话优化的TTS，提升多音字消歧能力——挑战与洞见

发布时间：2025年01月29日

`LLM应用

**理由**：这篇论文主要介绍了BreezyVoice，一个基于大型语言模型（LLM）的文本转语音（TTS）系统，专门针对台湾普通话进行了优化。论文中提到的技术，如LLM、OT-CFM模型等，都是LLM在实际应用中的具体实现，因此将其分类为LLM应用。` `语音合成`

> BreezyVoice: Adapting TTS for Taiwanese Mandarin with Enhanced Polyphone Disambiguation -- Challenges and Insights

# 摘要

> 我们推出了BreezyVoice，这是一款专为台湾普通话量身定制的文本转语音（TTS）系统，特别强化了语音控制能力，以应对该语言中多音字消歧的独特难题。在CosyVoice的基础上，我们引入了$S^{3}$分词器、大型语言模型（LLM）、最优传输条件流匹配模型（OT-CFM）以及字形到音素预测模型，旨在生成高度逼真、接近人类语音的合成语音。评估结果显示，BreezyVoice在常规及代码转换场景下均展现出卓越性能，充分证明了其在生成高保真语音方面的强大实力。同时，我们还攻克了长尾说话者建模和多音字消歧的泛化难题，显著提升了系统性能，并为神经编解码TTS系统的运作机制提供了深刻洞见。

> We present BreezyVoice, a Text-to-Speech (TTS) system specifically adapted for Taiwanese Mandarin, highlighting phonetic control abilities to address the unique challenges of polyphone disambiguation in the language. Building upon CosyVoice, we incorporate a $S^{3}$ tokenizer, a large language model (LLM), an optimal-transport conditional flow matching model (OT-CFM), and a grapheme to phoneme prediction model, to generate realistic speech that closely mimics human utterances. Our evaluation demonstrates BreezyVoice's superior performance in both general and code-switching contexts, highlighting its robustness and effectiveness in generating high-fidelity speech. Additionally, we address the challenges of generalizability in modeling long-tail speakers and polyphone disambiguation. Our approach significantly enhances performance and offers valuable insights into the workings of neural codec TTS systems.

[Arxiv](https://arxiv.org/abs/2501.17790)