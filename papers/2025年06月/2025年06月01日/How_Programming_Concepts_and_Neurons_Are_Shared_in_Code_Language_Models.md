# 编程概念与神经元在代码语言模型中是如何共存的

发布时间：2025年06月01日

`LLM理论` `编程语言`

> How Programming Concepts and Neurons Are Shared in Code Language Models

# 摘要

> 现有研究主要关注单语种环境下大型语言模型（LLMs）在编程语言（PLs）中的机制，而我们研究了LLMs概念空间中多种编程语言与英语之间的关系。通过在21种编程语言对上使用两个基于Llama的模型进行少量样本翻译任务，我们发现：概念空间更贴近英语（包括PL关键词），且在中间层的后半部分对英语标记赋予了较高概率。进一步分析11种编程语言和英语的神经元激活，发现特定语言的神经元主要集中在底层，而各PL独有的神经元则更可能出现在顶层。对于与多种PL高度对齐的PL，无法识别出特定于语言的神经元，这些PL通常具有更大的关键字集合，并且在翻译任务中更接近模型的概念空间，无论输入/输出PL如何。我们的研究揭示了LLMs内部表示PL的机制，并揭示了模型概念空间中的结构模式。代码已开源，地址为https://github.com/cisnlp/code-specific-neurons。

> Several studies have explored the mechanisms of large language models (LLMs) in coding tasks, but most have focused on programming languages (PLs) in a monolingual setting. In this paper, we investigate the relationship between multiple PLs and English in the concept space of LLMs. We perform a few-shot translation task on 21 PL pairs using two Llama-based models. By decoding the embeddings of intermediate layers during this task, we observe that the concept space is closer to English (including PL keywords) and assigns high probabilities to English tokens in the second half of the intermediate layers. We analyze neuron activations for 11 PLs and English, finding that while language-specific neurons are primarily concentrated in the bottom layers, those exclusive to each PL tend to appear in the top layers. For PLs that are highly aligned with multiple other PLs, identifying language-specific neurons is not feasible. These PLs also tend to have a larger keyword set than other PLs and are closer to the model's concept space regardless of the input/output PL in the translation task. Our findings provide insights into how LLMs internally represent PLs, revealing structural patterns in the model's concept space. Code is available at https://github.com/cisnlp/code-specific-neurons.

[Arxiv](https://arxiv.org/abs/2506.01074)