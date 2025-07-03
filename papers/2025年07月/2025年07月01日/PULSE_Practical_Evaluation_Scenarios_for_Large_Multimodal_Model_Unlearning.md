# PULSE：大型多模态模型无学习的实用评估方案

发布时间：2025年07月01日

`LLM理论` `隐私保护` `人工智能`

> PULSE: Practical Evaluation Scenarios for Large Multimodal Model Unlearning

# 摘要

> 近年来，反学习技术作为一种应对大型语言模型（LLMs）和大型多模态模型（LMMs）中隐私和版权问题的方法，受到了广泛关注。尽管为LLMs建立了一些反学习基准，但针对LMMs的反学习实用评估框架却鲜有探索。具体而言，现有的LMMs反学习基准仅考虑了模型需要通过单一反学习操作来遗忘微调知识的场景。在本研究中，我们引入了PULSE协议，通过引入两个关键视角，为LMMs的现实反学习场景提供支持：(i) 预训练知识反学习，用于分析不同知识获取阶段的影响；(ii) 长期可持续性评估，用于应对连续请求。随后，我们根据这些维度对现有的反学习方法进行了评估。结果显示，尽管某些技术能够成功地遗忘通过微调获得的知识，但它们难以消除预训练过程中学习的信息。此外，那些在单一操作中有效遗忘一批目标数据的方法，在面对相同数据被分割并按顺序反学习时，性能会显著下降。

> In recent years, unlearning techniques, which are methods for inducing a model to "forget" previously learned information, have attracted attention as a way to address privacy and copyright concerns in large language models (LLMs) and large multimodal models (LMMs). While several unlearning benchmarks have been established for LLMs, a practical evaluation framework for unlearning in LMMs has been less explored. Specifically, existing unlearning benchmark for LMMs considers only scenarios in which the model is required to unlearn fine-tuned knowledge through a single unlearning operation. In this study, we introduce PULSE protocol for realistic unlearning scenarios for LMMs by introducing two critical perspectives: (i) Pre-trained knowledge Unlearning for analyzing the effect across different knowledge acquisition phases and (ii) Long-term Sustainability Evaluation to address sequential requests. We then evaluate existing unlearning methods along these dimensions. Our results reveal that, although some techniques can successfully unlearn knowledge acquired through fine-tuning, they struggle to eliminate information learned during pre-training. Moreover, methods that effectively unlearn a batch of target data in a single operation exhibit substantial performance degradation when the same data are split and unlearned sequentially.

[Arxiv](https://arxiv.org/abs/2507.01271)