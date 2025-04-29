# 提升大型语言模型推理能力的表示工程方法

发布时间：2025年04月28日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的推理机制，提出了一种通过分析模型激活状态和控制向量来调节模型表示空间的方法，以提升推理能力。研究重点在于理解模型的工作原理和优化方法，属于理论层面的研究。` `模型优化`

> Improving Reasoning Performance in Large Language Models via Representation Engineering

# 摘要

> 近期，大型语言模型（LLMs）在推理能力方面取得了显著进展，生成的语言也更加具有人类特征。然而，关于LLMs中的推理是否本质上与人类推理不同这一点，仍然存在广泛争议。我们提出了一种表示工程方法，即在LLM处理推理任务时，从其残差流中读取模型激活状态。这些激活状态被用于推导出一个控制向量，并在推理时将其应用于模型，从而调节模型的表示空间，以提升特定任务的性能。我们公开了用于推导控制向量和分析模型表示的代码。该方法使我们能够通过控制向量改进推理基准的表现，并通过KL散度和熵等指标评估其对模型最终logit分布的影响。我们将控制向量应用于Mistral-7B-Instruct和一系列Pythia模型，针对归纳、演绎和数学推理任务进行测试。实验结果表明，通过调节激活状态，LLM在一定程度上可以被控制以提升其推理能力。这种干预方法依赖于可靠提取模型在正确解决任务时的典型状态的能力。我们的研究结果表明，推理性能的提升与LLMs执行其他信息处理任务的方式相似，并且我们能够通过简单的残差流干预（无需额外训练）来提升特定任务的性能。

> Recent advancements in large language models (LLMs) have resulted in increasingly anthropomorphic language concerning the ability of LLMs to reason. Whether reasoning in LLMs should be understood to be inherently different is, however, widely debated. We propose utilizing a representation engineering approach wherein model activations are read from the residual stream of an LLM when processing a reasoning task. The activations are used to derive a control vector that is applied to the model as an inference-time intervention, modulating the representational space of the model, to improve performance on the specified task. We publish the code for deriving control vectors and analyzing model representations. The method allows us to improve performance on reasoning benchmarks and assess how control vectors influence the final logit distribution of a model via metrics such as KL divergence and entropy. We apply control vectors to Mistral-7B-Instruct and a range of Pythia models on an inductive, a deductive and mathematical reasoning task. We show that an LLM can, to a certain degree, be controlled to improve its perceived reasoning ability by modulating activations. The intervention is dependent upon the ability to reliably extract the model's typical state when correctly solving a task. Our results suggest that reasoning performance can be modulated in the same manner as other information-processing tasks performed by LLMs and demonstrate that we are capable of improving performance on specific tasks via a simple intervention on the residual stream with no additional training.

[Arxiv](https://arxiv.org/abs/2504.19483)