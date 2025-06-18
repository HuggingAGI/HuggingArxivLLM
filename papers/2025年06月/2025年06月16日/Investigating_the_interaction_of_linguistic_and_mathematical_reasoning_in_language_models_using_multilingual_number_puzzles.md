# 利用多语言数字谜题研究语言模型中的语言与数学推理交互

发布时间：2025年06月16日

`LLM理论` `数学推理`

> Investigating the interaction of linguistic and mathematical reasoning in language models using multilingual number puzzles

# 摘要

> 不同语言的数字系统在构建和组合数字方面差异显著。虽然人类能够轻松应对这种多样性，但大型语言模型（LLMs）在处理跨语言数字系统相关的语言-数学难题时却显得力不从心，而这些难题对人类来说却是可学习和解决的。我们通过一系列实验，探究了LLMs难以完成此任务的原因，这些实验深入剖析了语言中数字的语言和数学特性。实验结果表明，除非问题中的数学运算使用已知符号（如“+”、“×”等）明确标出（例如“twenty + three”），否则模型难以稳定地解决此类问题。在进一步的消融研究中，我们探讨了数字构建和组合的各个参数对性能的影响。人类能够利用其对数字的语言理解，推断出数字符号的隐含组合结构，而LLMs似乎缺乏这种对数字结构隐含性的认知。我们得出结论，从人类规模数据中的隐性模式灵活推断组合规则的能力，仍然是当前推理模型尚未攻克的难题。

> Across languages, numeral systems vary widely in how they construct and combine numbers. While humans consistently learn to navigate this diversity, large language models (LLMs) struggle with linguistic-mathematical puzzles involving cross-linguistic numeral systems, which humans can learn to solve successfully. We investigate why this task is difficult for LLMs through a series of experiments that untangle the linguistic and mathematical aspects of numbers in language. Our experiments establish that models cannot consistently solve such problems unless the mathematical operations in the problems are explicitly marked using known symbols ($+$, $\times$, etc, as in "twenty + three"). In further ablation studies, we probe how individual parameters of numeral construction and combination affect performance. While humans use their linguistic understanding of numbers to make inferences about the implicit compositional structure of numerals, LLMs seem to lack this notion of implicit numeral structure. We conclude that the ability to flexibly infer compositional rules from implicit patterns in human-scale data remains an open challenge for current reasoning models.

[Arxiv](https://arxiv.org/abs/2506.13886)