# 数据高效语言模型之路：从儿童学习中汲取灵感

发布时间：2025年03月06日

`LLM理论

理由：这篇论文探讨了语言模型的训练方法，特别是数据选择、词汇量缩放和课程学习策略，属于对模型本身的理论和方法研究。` `语言模型`

> Towards Data-Efficient Language Models: A Child-Inspired Approach to Language Learning

# 摘要

> 在这项研究中，我们介绍了在 BabyLM 挑战中采用的独特方法。该方法灵感源自儿童学习语言的方式，使用了比传统大型语言模型 (LLMs) 少得多的数据来训练语言模型 (LMs)。尽管儿童接触到的语料远少于 LLM，但他们仍能展现出惊人的语言理解和生成能力。为此，我们构建了一个基于精选数据集的模型，该数据集包含 1000 万个单词，主要来自儿童导向的转录文本。经过筛选，2024 年 BabyLM 挑战的初始 1000 万词数据集缩减至 850 万词。随后，我们补充了一个随机选取的 TVR 数据集子集，包含 150 万词的电视对话内容，使模型像儿童一样通过媒体接触语言。此外，我们将词汇量精简至 32,000 个令牌，与语言习得早期阶段儿童的有限词汇量相匹配。通过采用课程学习策略，我们在某些基准测试中达到了基线模型的水平，而在其他测试中则超越了基线。值得注意的是，加入常见的 LLM 训练数据集（如 MADLAD-400）反而会降低性能。这些发现凸显了数据集选择、词汇量缩放和课程学习在构建更高效、更贴近人类学习过程的语言模型中的关键作用。

> In this work, we explain our approach employed in the BabyLM Challenge, which uses various methods of training language models (LMs) with significantly less data compared to traditional large language models (LLMs) and are inspired by how human children learn. While a human child is exposed to far less linguistic input than an LLM, they still achieve remarkable language understanding and generation abilities. To this end, we develop a model trained on a curated dataset consisting of 10 million words, primarily sourced from child-directed transcripts. The 2024 BabyLM Challenge initial dataset of 10M words is filtered to 8.5M. Next, it is supplemented with a randomly selected subset of TVR dataset consisting of 1.5M words of television dialogues. The latter dataset ensures that similar to children, the model is also exposed to language through media. Furthermore, we reduce the vocabulary size to 32,000 tokens, aligning it with the limited vocabulary of children in the early stages of language acquisition. We use curriculum learning and is able to match the baseline on certain benchmarks while surpassing the baseline on others. Additionally, incorporating common LLM training datasets, such as MADLAD-400, degrades performance. These findings underscore the importance of dataset selection, vocabulary scaling, and curriculum learning in creating more data-efficient language models that better mimic human learning processes.

[Arxiv](https://arxiv.org/abs/2503.04611)