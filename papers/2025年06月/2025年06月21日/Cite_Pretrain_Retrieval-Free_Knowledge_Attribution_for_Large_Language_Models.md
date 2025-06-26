# 大型语言模型的知识归因无需检索——Cite Pretrain

发布时间：2025年06月21日

`LLM理论

摘要讨论了如何改进语言模型的训练方法，使其能够可靠地将输出归因于预训练数据中的文档，而无需在测试时进行外部检索。这涉及模型的训练过程和机制，属于LLM理论的范畴。` `可信计算` `信息检索`

> Cite Pretrain: Retrieval-Free Knowledge Attribution for Large Language Models

# 摘要

> 可信的语言模型不仅要提供正确的答案，还要确保这些答案可以被验证。尽管语言模型有时会将其输出归因于预训练数据，但它们的引用往往因幻觉现象而不可靠。因此，当前系统在推理时通过查询外部检索器插入引用，这引入了延迟、对基础设施的依赖以及易受检索噪声影响的问题。我们探讨了是否可以通过修改训练过程，使LLMs能够可靠地将其输出归因于在（持续）预训练过程中见过的文档，而无需测试时的检索。

为此，我们发布了CitePretrainBench，这是一个基准测试，将真实语料库（维基百科、Common Crawl、arXiv）与新颖且未见过的文档混合，并对短格式（单一事实）和长格式（多事实）的引用任务进行评估。我们的方法采用两阶段流程：（1）持续预训练以将事实绑定到持久的文档标识符；（2）指令微调以激发引用行为。

我们发现，简单的被动索引，即将标识符附加到每个文档，有助于记忆原文本，但在处理改写或组合性事实时失败。相反，我们提出了主动索引，它通过在合成QA对上进行持续预训练，这些QA对（1）以多样化的组合形式重新表述每个事实，（2）要求双向的源到事实和事实到源生成，从而同时教导模型如何从引用来源生成内容，并将其自身答案归因于这些来源。

在Qwen2.5-7B和3B上的实验表明，主动索引在所有任务和模型上始终优于被动索引，引用精度提高了高达30.2%。我们的消融研究表明，随着我们扩展增强数据的量，性能持续提高，即使在原始标记数量的16倍时，仍呈现出明显的上升趋势。


> Trustworthy language models should provide both correct and verifiable answers. While language models can sometimes attribute their outputs to pretraining data, their citations are often unreliable due to hallucination. As a result, current systems insert citations by querying an external retriever at inference time, introducing latency, infrastructure dependence, and vulnerability to retrieval noise. We explore whether LLMs can be made to reliably attribute to the documents seen during (continual) pretraining--without test-time retrieval--by revising the training process. To evaluate this, we release CitePretrainBench, a benchmark that mixes real-world corpora (Wikipedia, Common Crawl, arXiv) with novel, unseen documents and probes both short-form (single fact) and long-form (multi-fact) citation tasks. Our approach follows a two-stage process: (1) continual pretraining to bind facts to persistent document identifiers, and (2) instruction tuning to elicit citation behavior. We find that simple Passive Indexing, which appends an identifier to each document, helps memorize verbatim text but fails on paraphrased or compositional facts. Instead, we propose Active Indexing, which continually pretrains on synthetic QA pairs that (1) restate each fact in diverse compositional forms, and (2) require bidirectional source-to-fact and fact-to-source generation, jointly teaching the model to generate content from a cited source and to attribute its own answers. Experiments with Qwen2.5-7B and 3B show that Active Indexing consistently outperforms Passive Indexing across all tasks and models, with citation precision gains up to 30.2 percent. Our ablation studies reveal that performance continues to improve as we scale the amount of augmented data, showing a clear upward trend even at 16 times the original token count.

[Arxiv](https://arxiv.org/abs/2506.17585)