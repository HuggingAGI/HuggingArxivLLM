# # GRAIL：大型语言模型中的隐私与版权保护——基于梯度的自适应遗忘方法

发布时间：2025年04月17日

`LLM应用` `隐私保护` `数据管理`

> GRAIL: Gradient-Based Adaptive Unlearning for Privacy and Copyright in LLMs

# 摘要

> 大型语言模型 (LLMs) 在广泛的数据集上进行训练时，往往会学习到大量敏感信息，这在“被遗忘权”等原则下引发了重大的社会和法律担忧。从头重新训练整个模型以去除不需要的信息不仅成本高昂，而且在实践中难以操作。此外，现有的单领域遗忘方法无法应对多领域场景，因为在隐私、版权等不同领域中，知识往往是相互交织的，导致表示出现重叠，从而引发过度知识删除或性能下降。为了解决这些问题，我们提出了 GRAIL（基于梯度的自适应遗忘框架），这是一个创新的多领域遗忘框架。GRAIL 利用多领域中的梯度信息，精确区分遗忘范围和保留范围，并采用自适应参数级定位策略，选择性地移除目标知识，同时为每个领域保留关键参数。在遗忘基准测试中的实验结果表明，GRAIL 的遗忘成功率与现有方法相当，同时与之前最先进的方法相比，知识保留成功率提高了多达 17%。我们的研究结果为大规模预训练语言模型中敏感信息的有效管理和监管奠定了新的范式。

> Large Language Models (LLMs) trained on extensive datasets often learn sensitive information, which raises significant social and legal concerns under principles such as the "Right to be forgotten." Retraining entire models from scratch to remove undesired information is both costly and impractical. Furthermore, existing single-domain unlearning methods fail to address multi-domain scenarios, where knowledge is interwoven across domains such as privacy and copyright, creating overlapping representations that lead to excessive knowledge removal or degraded performance. To tackle these issues, we propose GRAIL (GRadient-based AdaptIve unLearning), a novel multi-domain unlearning framework. GRAIL leverages gradient information from multiple domains to precisely distinguish the unlearning scope from the retention scope, and applies an adaptive parameter-wise localization strategy to selectively remove targeted knowledge while preserving critical parameters for each domain. Experimental results on unlearning benchmarks show that GRAIL achieves unlearning success on par with the existing approaches, while also demonstrating up to 17% stronger knowledge retention success compared to the previous state-of-art method. Our findings establish a new paradigm for effectively managing and regulating sensitive information in large-scale pre-trained language models.

[Arxiv](https://arxiv.org/abs/2504.12681)