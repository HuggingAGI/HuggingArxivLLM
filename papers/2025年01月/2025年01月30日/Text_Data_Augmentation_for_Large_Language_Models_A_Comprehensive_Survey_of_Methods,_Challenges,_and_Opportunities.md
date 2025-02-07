# 大型语言模型的文本数据增强：方法、挑战与机遇全览

发布时间：2025年01月30日

`LLM应用

**理由**：这篇论文主要讨论了大型语言模型（LLMs）在数据增强中的应用，特别是如何通过提示模板和检索技术来提升LLMs的生成能力。论文还探讨了数据增强技术的分类、后处理方法以及评估指标，这些都是LLM在实际应用中的具体使用场景。因此，这篇论文应归类为LLM应用。` `数据增强`

> Text Data Augmentation for Large Language Models: A Comprehensive Survey of Methods, Challenges, and Opportunities

# 摘要

> 预训练语言模型的规模和复杂性不断提升，在许多应用中展现了卓越性能，但通常需要大量训练数据才能充分训练。训练集不足可能导致模型过拟合，难以应对复杂任务。基于广泛语料库训练的大型语言模型（LLMs）具备强大的文本生成能力，不仅提升了数据的质量和数量，还在数据增强中扮演了关键角色。特别是在个性化任务中，独特的提示模板被用来引导LLMs生成所需内容。近期，基于检索的技术通过引入外部知识，进一步提升了LLMs在数据增强中的表达能力，使其能够生成更贴近真实的数据。本文深入探讨了LLMs中的数据增强技术，将其分为简单增强、基于提示的增强、基于检索的增强和混合增强四类。我们总结了数据增强中的后处理方法，这些方法在优化增强数据和过滤不忠实内容方面发挥了重要作用。此外，我们还介绍了常见任务和评估指标。最后，本文探讨了当前面临的挑战和未来的机遇，这些将为数据增强带来更多改进空间。

> The increasing size and complexity of pre-trained language models have demonstrated superior performance in many applications, but they usually require large training datasets to be adequately trained. Insufficient training sets could unexpectedly make the model overfit and fail to cope with complex tasks. Large language models (LLMs) trained on extensive corpora have prominent text generation capabilities, which improve the quality and quantity of data and play a crucial role in data augmentation. Specifically, distinctive prompt templates are given in personalised tasks to guide LLMs in generating the required content. Recent promising retrieval-based techniques further improve the expressive performance of LLMs in data augmentation by introducing external knowledge to enable them to produce more grounded-truth data. This survey provides an in-depth analysis of data augmentation in LLMs, classifying the techniques into Simple Augmentation, Prompt-based Augmentation, Retrieval-based Augmentation and Hybrid Augmentation. We summarise the post-processing approaches in data augmentation, which contributes significantly to refining the augmented data and enabling the model to filter out unfaithful content. Then, we provide the common tasks and evaluation metrics. Finally, we introduce existing challenges and future opportunities that could bring further improvement to data augmentation.

[Arxiv](https://arxiv.org/abs/2501.18845)