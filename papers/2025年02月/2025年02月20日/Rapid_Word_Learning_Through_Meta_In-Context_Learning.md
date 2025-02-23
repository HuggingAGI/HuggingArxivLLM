# # 快速掌握词汇：元上下文学习的力量

发布时间：2025年02月20日

`LLM理论` `教育技术`

> Rapid Word Learning Through Meta In-Context Learning

# 摘要

> 人类能够从少量实例中快速掌握新词，并在新语境中灵活运用。然而，当前语言模型在少样本单词学习方面的潜力尚未被充分挖掘。本文提出了一种创新方法——元训练用于上下文单词学习（Minnow）。该方法通过给定几个上下文示例，训练语言模型生成新词的使用场景，并以特殊占位符标记新词。通过在大量新词上反复训练，模型能够发展出通用的单词学习能力。研究发现，使用Minnow从零开始训练模型，使其在基于人类规模的儿童导向语言数据上实现强大的少样本单词学习能力，其表现可与在大规模数据上预训练的大型语言模型（LLM）相媲美。进一步通过判别和生成评估，我们发现使用Minnow对预训练的LLM进行微调，可以显著提升模型在基于一到几个上下文示例的情况下区分新词、识别新词的句法类别以及生成合理的新用法和定义的能力。这些发现不仅凸显了Minnow的数据效率，也展现了其在提升语言模型单词学习任务性能方面的巨大潜力。

> Humans can quickly learn a new word from a few illustrative examples, and then systematically and flexibly use it in novel contexts. Yet the abilities of current language models for few-shot word learning, and methods for improving these abilities, are underexplored. In this study, we introduce a novel method, Meta-training for IN-context learNing Of Words (Minnow). This method trains language models to generate new examples of a word's usage given a few in-context examples, using a special placeholder token to represent the new word. This training is repeated on many new words to develop a general word-learning ability. We find that training models from scratch with Minnow on human-scale child-directed language enables strong few-shot word learning, comparable to a large language model (LLM) pre-trained on orders of magnitude more data. Furthermore, through discriminative and generative evaluations, we demonstrate that finetuning pre-trained LLMs with Minnow improves their ability to discriminate between new words, identify syntactic categories of new words, and generate reasonable new usages and definitions for new words, based on one or a few in-context examples. These findings highlight the data efficiency of Minnow and its potential to improve language model performance in word learning tasks.

[Arxiv](https://arxiv.org/abs/2502.14791)