# 探索大型语言模型中的预训练数据：基于神经元激活机制的检测框架

发布时间：2025年07月22日

`LLM理论` `数据检测` `基准测试`

> Identifying Pre-training Data in LLMs: A Neuron Activation-Based Detection Framework

# 摘要

> 大型语言模型（LLMs）的性能与其训练数据密切相关，而这些数据可能包含受版权保护的材料或私人信息，引发法律和伦理方面的担忧。此外，LLMs还因数据集污染和内化偏见而受到批评。为了解决这些问题，我们提出了预训练数据检测（PDD）任务，以确定特定数据是否包含在LLMs的预训练语料库中。然而，现有PDD方法通常依赖于预测置信度和损失等表层特征，导致性能平庸。为此，我们引入了NA-PDD，这是一种新型算法，通过分析LLMs中训练数据与非训练数据之间的差异化的神经元激活模式来提升检测能力。这一方法基于我们在LLMs推理过程中观察到的不同数据类型会激活不同的神经元。我们还引入了CCNewsPDD，这是一个时间无偏的基准测试，采用严格的数据转换以确保训练数据与非训练数据之间的时间分布一致。实验结果表明，NA-PDD在三个基准测试和多个LLMs上显著优于现有方法。

> The performance of large language models (LLMs) is closely tied to their training data, which can include copyrighted material or private information, raising legal and ethical concerns. Additionally, LLMs face criticism for dataset contamination and internalizing biases. To address these issues, the Pre-Training Data Detection (PDD) task was proposed to identify if specific data was included in an LLM's pre-training corpus. However, existing PDD methods often rely on superficial features like prediction confidence and loss, resulting in mediocre performance. To improve this, we introduce NA-PDD, a novel algorithm analyzing differential neuron activation patterns between training and non-training data in LLMs. This is based on the observation that these data types activate different neurons during LLM inference. We also introduce CCNewsPDD, a temporally unbiased benchmark employing rigorous data transformations to ensure consistent time distributions between training and non-training data. Our experiments demonstrate that NA-PDD significantly outperforms existing methods across three benchmarks and multiple LLMs.

[Arxiv](https://arxiv.org/abs/2507.16414)