# # 探索马其顿语开放型基础语言模型与语料库：一种低资源语言

发布时间：2025年06月11日

`LLM应用` `多语言技术`

> Towards Open Foundation Language Model and Corpus for Macedonian: A Low-Resource Language

# 摘要

> 全球技术应用的普及带来了对新型工具的迫切需求，以供普通用户使用。大型语言模型（LLMs）在这一点上提供了巨大机遇，但它们的能力在低资源语言中仍然受限，这限制了它们在使用这些语言的国家中的应用。我们开发了多种资源，以促进LLMs的采用，并支持马其顿语的研究进展。我们收集了迄今为止最大的马其顿语语料库，包含40GB的文本数据，总计35亿个单词。为了支持对话应用，我们收集了一个包含10.6万个实例的指令数据集，该数据集经过精心设计，具有文化相关性。在评估方面，我们构建了一个涵盖七个基准的马其顿语评估套件。最后，我们在整理好的数据集上训练了domestic-yak，这是一个拥有80亿参数的先进模型，并使用新构建的基准套件将其与八种基线模型进行了对比评估。我们的模型在80亿参数范围内所有基准上均优于现有模型，并且在性能上与规模大10倍的模型相当。此外，与母语者的定性分析表明，我们的模型比更大规模的模型更受欢迎，获得了更高的语法正确性和文化适宜性评分。所有数据集、代码和模型权重均已公开发布，为推进同样代表性不足语言的LLMs奠定了基础。这些资源可在github.com/LVSTCK获取源代码，在huggingface.co/LVSTCK获取预训练模型权重和数据。

> The increase in technological adoption worldwide comes with demands for novel tools to be used by the general population. Large Language Models (LLMs) provide a great opportunity in this respect, but their capabilities remain limited for low-resource languages, restricting applications in countries where such languages are spoken. We create several resources to facilitate the adoption of LLMs and to support research advancements for Macedonian. We collect the largest Macedonian corpus to date, consisting of 40GB of textual data and totaling 3.5B words. To support conversational applications, we collect a 106k-instance instruction dataset, carefully built to be culturally grounded. For evaluation, we construct a Macedonian evaluation suite covering seven benchmarks. Finally, we train domestic-yak, a state-of-the-art 8B-parameter model, on our curated datasets and evaluate it against eight baseline models using the newly constructed benchmark suite. Our model outperforms all existing models in the 8B parameter range across all benchmarks, and achieves performance comparable to models up to 10x larger. Furthermore, a qualitative analysis with native speakers reveals that our model is preferred over larger counterparts, receiving higher ratings for grammatical correctness and cultural appropriateness. All datasets, code, and model weights are openly released, setting a foundation for advancing LLMs in similarly underrepresented languages. These resources are publicly available at github.com/LVSTCK for source code, and at huggingface.co/LVSTCK for pretrained model weights and data.

[Arxiv](https://arxiv.org/abs/2506.09560)