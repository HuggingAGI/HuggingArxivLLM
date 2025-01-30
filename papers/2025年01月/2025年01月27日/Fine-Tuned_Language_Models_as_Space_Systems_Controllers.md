# 微调语言模型：空间系统的新一代控制器

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了大型语言模型（LLMs）在经过微调后，能够控制简化的空间系统。这属于LLM在实际应用中的具体使用场景，即通过微调LLM来解决特定的控制问题。因此，将其分类为LLM应用是合适的。` `航空航天` `控制系统`

> Fine-Tuned Language Models as Space Systems Controllers

# 摘要

> 大型语言模型（LLMs）或基础模型（FMs）是经过预训练的变换器，能够自回归地生成连贯的句子。本文展示了LLMs在经过微调后，能够控制简化的空间系统。我们研究了参数在70亿到130亿之间的较小模型，重点关注三维弹簧玩具问题、低推力轨道转移、低推力地月控制和动力下降制导四个问题。微调后的LLMs能够生成精确的多维向量（最多10位有效数字）来控制系统。我们发现，对于某些问题，微调所需的数据量比传统深度神经网络（DNNs）要少，且微调后的LLMs在训练数据之外表现出良好的泛化能力。此外，同一个LLM可以用不同问题的数据进行微调，性能下降极小。这项研究为开发通用空间系统控制器迈出了第一步。

> Large language models (LLMs), or foundation models (FMs), are pretrained transformers that coherently complete sentences auto-regressively. In this paper, we show that LLMs can control simplified space systems after some additional training, called fine-tuning. We look at relatively small language models, ranging between 7 and 13 billion parameters. We focus on four problems: a three-dimensional spring toy problem, low-thrust orbit transfer, low-thrust cislunar control, and powered descent guidance. The fine-tuned LLMs are capable of controlling systems by generating sufficiently accurate outputs that are multi-dimensional vectors with up to 10 significant digits. We show that for several problems the amount of data required to perform fine-tuning is smaller than what is generally required of traditional deep neural networks (DNNs), and that fine-tuned LLMs are good at generalizing outside of the training dataset. Further, the same LLM can be fine-tuned with data from different problems, with only minor performance degradation with respect to LLMs trained for a single application. This work is intended as a first step towards the development of a general space systems controller.

[Arxiv](https://arxiv.org/abs/2501.16588)