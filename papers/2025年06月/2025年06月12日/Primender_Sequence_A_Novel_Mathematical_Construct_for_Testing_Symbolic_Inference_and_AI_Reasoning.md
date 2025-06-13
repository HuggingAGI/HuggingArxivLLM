# 普林门德序列：用于测试符号推理与AI推理能力的全新数学结构

发布时间：2025年06月12日

`LLM应用

理由：这篇论文提出了一种新的整数序列，并将其作为评估大型语言模型符号推理能力的基准。研究的重点是测试LLMs在推断隐藏规则、验证数学假设和大规模符号逻辑推广方面的能力，属于LLM的应用领域。` `符号推理`

> Primender Sequence: A Novel Mathematical Construct for Testing Symbolic Inference and AI Reasoning

# 摘要

> 本文提出了一种全新的整数序列——Primender序列，它通过结合经典素性与基于模数的数字条件的混合规则定义而成。具体来说，一个数n将被纳入该序列，如果它是素数，或者其末尾数字是一个素数，或者其任何长度的部分都是素数。换句话说，该序列由所有素数以及至少包含一个素数后缀的数构成。该序列展现出一种结构清晰但又非显而易见的模式，巧妙地将数论特性与符号模式相结合。

我们建议将Primender序列作为评估大型语言模型（LLMs）符号推理能力的基准。这项研究的出发点是填补可解释性规则测试床的空白，从而更好地评估LLM在推断隐藏规则、验证数学假设以及大规模符号逻辑推广方面的能力。

研究重点探讨以下假设：当Primender序列中的某个数恰好比小于或等于它的最大素数大1时，该数与序列中前一个数的差也是1。为此，我们设计了一个结构化的提示框架和评估体系，用于测试包括ChatGPT、Copilot、DeepSeek、Gemini、Grok和LLaMA在内的多款先进LLM。这些模型需要完成三项任务：识别潜在规则、验证假设以及生成序列的前100,000项。

通过规则推断准确性、假设验证、序列有效性以及符号解释质量等多维度指标，我们对模型的表现进行了全面评估。这项研究不仅为符号推理、假设检验和可扩展模式推广提供了新的数学构造，还通过可复现的方法论在数论、人工智能和软件工程之间架起了连接的桥梁。


> This paper introduces the Primender sequence, a novel integer sequence defined by a hybrid rule that combines classical primality with modular digit-based conditions. Specifically, a number n is included in the sequence if it is prime or ends with a prime number of unit digit or any length. In other words, numbers which are primes or have at least one prime suffix. The resulting sequence exhibits a deterministic yet non-trivial structure, blending number-theoretic properties with symbolic patterning. We propose the Primender sequence as a benchmark for evaluating the symbolic reasoning capabilities of Large Language Models (LLMs). The study is motivated by the need for interpretable, rule-based testbeds that can assess an LLM's ability to infer hidden rules, validate mathematical hypotheses, and generalize symbolic logic at scale. A key hypothesis explored is: Whenever a number in the Primender sequence is exactly one more than the largest prime less than or equal to it, the difference between it and the previous number in the sequence is also 1. We design a structured prompt and evaluation framework to test this hypothesis across multiple state-of-the-art LLMs, including ChatGPT, Copilot, DeepSeek, Gemini, Grok, and LLaMA. The models are tasked with identifying the underlying rule, validating the hypothesis, and generating the next 100,000 terms of the sequence. Comparative metrics such as rule inference accuracy, hypothesis evaluation, sequence validity, and symbolic explanation quality are used to assess model performance. This work contributes a novel mathematical construct and a reproducible methodology for benchmarking LLMs in symbolic reasoning, hypothesis testing, and scalable pattern generalization - bridging the domains of number theory, artificial intelligence, and software engineering.

[Arxiv](https://arxiv.org/abs/2506.10585)