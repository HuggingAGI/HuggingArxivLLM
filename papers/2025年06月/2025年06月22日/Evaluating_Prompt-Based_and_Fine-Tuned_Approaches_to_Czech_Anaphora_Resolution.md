# 对比研究：基于提示与微调方法在捷克语代词消解中的应用

发布时间：2025年06月22日

`LLM应用` `文本分析`

> Evaluating Prompt-Based and Fine-Tuned Approaches to Czech Anaphora Resolution

# 摘要

> 代词消解在自然语言理解中发挥着重要作用，尤其在捷克语等形态丰富的语言中表现突出。本文对两种现代代词消解方法在捷克语文本上的性能进行了对比研究：基于大型语言模型（LLMs）的提示工程和微调紧凑生成模型。我们基于布拉格依存树库构建了一个数据集，使用多种提示模板评估了Mistral Large 2和Llama 3等指令微调的LLMs。我们还将它们与专门针对捷克语代词消解任务微调的mT5和Mistral模型进行了对比。实验结果表明，提示工程方法在少样本学习中表现良好，最高可达74.5%的准确率。然而，微调模型，特别是mT5-large，表现更为优异，准确率高达88%，同时计算资源需求更低。我们从代词类型、先行词距离和语料来源等多个维度分析了各方法的性能表现，揭示了每种方法的关键优势和权衡取舍。

> Anaphora resolution plays a critical role in natural language understanding, especially in morphologically rich languages like Czech. This paper presents a comparative evaluation of two modern approaches to anaphora resolution on Czech text: prompt engineering with large language models (LLMs) and fine-tuning compact generative models. Using a dataset derived from the Prague Dependency Treebank, we evaluate several instruction-tuned LLMs, including Mistral Large 2 and Llama 3, using a series of prompt templates. We compare them against fine-tuned variants of the mT5 and Mistral models that we trained specifically for Czech anaphora resolution. Our experiments demonstrate that while prompting yields promising few-shot results (up to 74.5% accuracy), the fine-tuned models, particularly mT5-large, outperform them significantly, achieving up to 88% accuracy while requiring fewer computational resources. We analyze performance across different anaphora types, antecedent distances, and source corpora, highlighting key strengths and trade-offs of each approach.

[Arxiv](https://arxiv.org/abs/2506.18091)