# # 标题
一器通百语：多语言分词器开启语言涌现可塑性新时代

发布时间：2025年06月12日

`LLM理论` `跨语言处理`

> One Tokenizer To Rule Them All: Emergent Language Plasticity via Multilingual Tokenizers

# 摘要

> # 摘要  
同时为多种语言预训练大规模多语言大型语言模型（LLMs）面临多重挑战，包括模型容量限制、高质量数据稀缺以及计算资源限制。此外，分词器的语言覆盖不足使得单纯通过后训练阶段难以弥合新语言的差距。  
在这项研究中，我们探索了在训练早期采用哪些相对经济的干预措施能够提升模型的“语言可塑性”，即模型在后训练阶段对新语言的适应能力。我们专注于分词器设计，提出采用一个通用分词器，该分词器支持比主要预训练语言更多的语言，从而在扩展语言覆盖范围后实现更高效的适应。  
通过在不同语言组和不同训练策略上的系统性实验，我们发现通用分词器显著提升了语言适应能力，与仅针对预训练语言的分词器相比，胜率提升了高达20.2%。此外，通用分词器还对分词器和预训练过程中完全未见过的语言表现出更好的可塑性，胜率提升了5%。我们通过最小的性能妥协，成功实现了对扩展语言集合的适应，同时保持了预训练中包含的大多数语言的性能。

> Pretraining massively multilingual Large Language Models (LLMs) for many languages at once is challenging due to limited model capacity, scarce high-quality data, and compute constraints. Moreover, the lack of language coverage of the tokenizer makes it harder to address the gap for new languages purely at the post-training stage. In this work, we study what relatively cheap interventions early on in training improve "language plasticity", or adaptation capabilities of the model post-training to new languages. We focus on tokenizer design and propose using a universal tokenizer that is trained for more languages than the primary pretraining languages to enable efficient adaptation in expanding language coverage after pretraining. Our systematic experiments across diverse groups of languages and different training strategies show that a universal tokenizer enables significantly higher language adaptation, with up to 20.2% increase in win rates compared to tokenizers specific to pretraining languages. Furthermore, a universal tokenizer also leads to better plasticity towards languages that are completely unseen in the tokenizer and pretraining, by up to 5% win rate gain. We achieve this adaptation to an expanded set of languages with minimal compromise in performance on the majority of languages included in pretraining.

[Arxiv](https://arxiv.org/abs/2506.10766)