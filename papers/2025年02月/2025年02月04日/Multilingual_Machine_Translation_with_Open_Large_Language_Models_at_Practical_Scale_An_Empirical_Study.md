# 开放大型语言模型在实际规模下的多语言机器翻译实证研究

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要研究了开源大型语言模型（LLMs）在多语言机器翻译任务中的表现，并提出了改进策略。这属于LLM在实际任务中的应用，因此分类为LLM应用。` `机器翻译` `多语言处理`

> Multilingual Machine Translation with Open Large Language Models at Practical Scale: An Empirical Study

# 摘要

> 大型语言模型（LLMs）在多语言能力上不断进步，即便是小规模的开源模型也展现出显著的性能提升。本文系统研究了参数少于100亿的开源LLMs在多语言机器翻译（MT）任务中的表现。通过对六个热门LLMs的全面评估，我们发现Gemma2-9B等模型具备出色的多语言翻译能力。为进一步提升MT性能，我们在持续预训练阶段引入了Parallel-First Monolingual-Second（PFMS）数据混合策略，并推出了GemmaX2-28，一个在28种语言中表现卓越的9B模型。具体而言，GemmaX2-28不仅持续超越TowerInstruct和XALMA等SOTA模型，还在与Google Translate和GPT-4-turbo的较量中展现出强劲竞争力。

> Large language models (LLMs) have shown continuously improving multilingual capabilities, and even small-scale open-source models have demonstrated rapid performance enhancement. In this paper, we systematically explore the abilities of open LLMs with less than ten billion parameters to handle multilingual machine translation (MT) tasks. We conduct comprehensive evaluations on six popular LLMs and find that models like Gemma2-9B exhibit impressive multilingual translation capabilities. We then introduce the Parallel-First Monolingual-Second (PFMS) data mixing strategy in the continual pretraining stage to further enhance the MT performance and present GemmaX2-28, a 9B model achieving top-tier multilingual translation performance across 28 languages. Specifically, GemmaX2-28 consistently outperforms the state-of-the-art (SOTA) models such as TowerInstruct and XALMA and achieves competitive performance with Google Translate and GPT-4-turbo.

[Arxiv](https://arxiv.org/abs/2502.02481)