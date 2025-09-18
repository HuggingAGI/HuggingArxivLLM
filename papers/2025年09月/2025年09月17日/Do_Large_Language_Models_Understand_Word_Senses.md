# 大型语言模型能否理解词义？

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Do Large Language Models Understand Word Senses?

# 摘要

> 理解语境中的词义是大型语言模型（LLMs）的核心能力。尽管已有大量评估研究，但LLMs是否真正掌握词义的证据仍有待深入探索。本文通过两方面评估填补这一空白：一是测试指令微调LLMs的词义消歧（WSD）能力，并与该任务的顶尖专用系统对比；二是考察两款表现最佳的开源与闭源LLMs在三种生成场景下的词义理解能力，包括定义生成、自由解释和示例生成。值得关注的是，在WSD任务中，GPT-4o和DeepSeek-V3等主流模型性能堪比专用WSD系统，且在不同领域和难度级别上表现出更强的稳健性。生成任务结果显示，LLMs解释语境词义的准确率可达98%，其中自由解释任务表现最佳，与它们的生成能力高度契合。

> Understanding the meaning of words in context is a fundamental capability for Large Language Models (LLMs). Despite extensive evaluation efforts, the extent to which LLMs show evidence that they truly grasp word senses remains underexplored. In this paper, we address this gap by evaluating both i) the Word Sense Disambiguation (WSD) capabilities of instruction-tuned LLMs, comparing their performance to state-of-the-art systems specifically designed for the task, and ii) the ability of two top-performing open- and closed-source LLMs to understand word senses in three generative settings: definition generation, free-form explanation, and example generation. Notably, we find that, in the WSD task, leading models such as GPT-4o and DeepSeek-V3 achieve performance on par with specialized WSD systems, while also demonstrating greater robustness across domains and levels of difficulty. In the generation tasks, results reveal that LLMs can explain the meaning of words in context up to 98\% accuracy, with the highest performance observed in the free-form explanation task, which best aligns with their generative capabilities.

[Arxiv](https://arxiv.org/abs/2509.13905)