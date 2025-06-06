# LESS：基于大型语言模型的增强型半监督学习语音基础模型

发布时间：2025年06月04日

`LLM应用` `语音处理`

> LESS: Large Language Model Enhanced Semi-Supervised Learning for Speech Foundational Models

# 摘要

> 我们提出了 LESS（大型语言模型增强的半监督学习框架），该框架利用 LLM 对从真实数据中生成的伪标签进行优化。在 LESS 中，无监督数据的 ASR 或 AST 生成的伪标签文本经由 LLM 优化，并通过数据过滤策略增强，以提升 LLM 知识迁移效率。实验结果显示，在普通话 ASR 和西班牙语到英语 AST 任务中，LESS 在 Wenet Speech 测试集上实现了 3.77% 的绝对 WER 降低，同时在 Callhome 和 Fisher 测试集上分别获得 34.0 和 64.7 的 BLEU 分数。这些结果证明了 LESS 在不同语言、任务和领域的广泛应用能力。通过使用不同 LLM 和提示配置的消融实验，我们为 LLM 知识在语音处理中的应用提供了新的视角。

> We introduce LESS (Large Language Model Enhanced Semi-supervised Learning), a versatile framework that leverages Large Language Models (LLMs) to correct pseudo labels generated from in-the-wild data. Within the LESS framework, pseudo-labeled text from Automatic Speech Recognition (ASR) or Automatic Speech Translation (AST) of the unsupervised data is refined by an LLM, and augmented by a data filtering strategy to optimize LLM knowledge transfer efficiency. Experiments on both Mandarin ASR and Spanish-to-English AST tasks show that LESS achieves a notable absolute WER reduction of 3.77% on the Wenet Speech test set, as well as BLEU scores of 34.0 and 64.7 on Callhome and Fisher test sets respectively. These results validate the adaptability of LESS across different languages, tasks, and domains. Ablation studies conducted with various LLMs and prompt configurations provide novel insights into leveraging LLM-derived knowledge for speech processing applications.

[Arxiv](https://arxiv.org/abs/2506.04586)