# # 语义枢杻让大型语言模型实现跨语言迁移

发布时间：2025年05月22日

`LLM理论` `跨语言`

> Semantic Pivots Enable Cross-Lingual Transfer in Large Language Models

# 摘要

> 大型语言模型（LLMs）在跨语言任务中表现卓越，但其能力来源仍是个未解之谜。为了深入理解这一现象，我们提出了一种词级跨语言翻译任务，旨在量化和解析LLMs的跨语言能力。通过追踪LLMs在词翻译任务中的中间层输出，我们揭示了其前向传播过程中两种独特的学习模式：共现行为和语义枢纽行为。研究表明，共现行为源于词语的使用频率，而语义枢纽行为则源自预训练数据中的特定语义模式。基于这一发现，我们构建了一个语义枢纽增强的预训练数据集，实验结果证实了该方法在提升LLMs跨语言能力方面的显著效果。这项研究不仅为理解LLMs的工作机制提供了新视角，更为优化其跨语言能力开辟了新路径。

> Large language models (LLMs) demonstrate remarkable ability in cross-lingual tasks. Understanding how LLMs acquire this ability is crucial for their interpretability. To quantify the cross-lingual ability of LLMs accurately, we propose a Word-Level Cross-Lingual Translation Task. To find how LLMs learn cross-lingual ability, we trace the outputs of LLMs' intermediate layers in the word translation task. We identify and distinguish two distinct behaviors in the forward pass of LLMs: co-occurrence behavior and semantic pivot behavior. We attribute LLMs' two distinct behaviors to the co-occurrence frequency of words and find the semantic pivot from the pre-training dataset. Finally, to apply our findings to improve the cross-lingual ability of LLMs, we reconstruct a semantic pivot-aware pre-training dataset using documents with a high proportion of semantic pivots. Our experiments validate the effectiveness of our approach in enhancing cross-lingual ability. Our research contributes insights into the interpretability of LLMs and offers a method for improving LLMs' cross-lingual ability.

[Arxiv](https://arxiv.org/abs/2505.16385)