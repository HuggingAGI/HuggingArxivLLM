# 对比学习在大型语言模型生成树库上的应用：跨域 constituency 语法分析

发布时间：2025年05月27日

`LLM应用

摘要中提到，跨领域的句法分析在计算语言学中仍是一个未解决的难题，主要是因为现有的多领域句法树库十分有限。本文研究了大型语言模型（LLMs）在句法树库自动生成中的应用。由于LLMs在句法分析上的表现不尽如人意，我们提出了一种新颖的句法树库生成方法——LLM逆生成，它类似于句法分析的逆过程。LLM逆生成以仅包含领域关键词叶节点的不完整跨领域句法树作为输入，填充缺失的词语以生成跨领域句法树库。此外，我们还引入了基于跨度的对比学习预训练策略，充分利用LLM逆生成句法树库进行跨领域句法分析。我们在MCTB的五个目标领域上验证了我们的LLM逆生成句法树库与对比学习预训练的组合效果。实验结果表明，与各种基线方法相比，我们的方法在平均结果上达到了最先进的性能。` `计算语言学`

> Contrastive Learning on LLM Back Generation Treebank for Cross-domain Constituency Parsing

# 摘要

> 跨领域的句法分析在计算语言学中仍是一个未解决的难题，主要是因为现有的多领域句法树库十分有限。本文研究了大型语言模型（LLMs）在句法树库自动生成中的应用。由于LLMs在句法分析上的表现不尽如人意，我们提出了一种新颖的句法树库生成方法——LLM逆生成，它类似于句法分析的逆过程。LLM逆生成以仅包含领域关键词叶节点的不完整跨领域句法树作为输入，填充缺失的词语以生成跨领域句法树库。此外，我们还引入了基于跨度的对比学习预训练策略，充分利用LLM逆生成句法树库进行跨领域句法分析。我们在MCTB的五个目标领域上验证了我们的LLM逆生成句法树库与对比学习预训练的组合效果。实验结果表明，与各种基线方法相比，我们的方法在平均结果上达到了最先进的性能。

> Cross-domain constituency parsing is still an unsolved challenge in computational linguistics since the available multi-domain constituency treebank is limited. We investigate automatic treebank generation by large language models (LLMs) in this paper. The performance of LLMs on constituency parsing is poor, therefore we propose a novel treebank generation method, LLM back generation, which is similar to the reverse process of constituency parsing. LLM back generation takes the incomplete cross-domain constituency tree with only domain keyword leaf nodes as input and fills the missing words to generate the cross-domain constituency treebank. Besides, we also introduce a span-level contrastive learning pre-training strategy to make full use of the LLM back generation treebank for cross-domain constituency parsing. We verify the effectiveness of our LLM back generation treebank coupled with contrastive learning pre-training on five target domains of MCTB. Experimental results show that our approach achieves state-of-the-art performance on average results compared with various baselines.

[Arxiv](https://arxiv.org/abs/2505.20976)