# ControlMed: 为医疗语言模型注入推理控制，提升智能与精准

发布时间：2025年07月30日

`LLM应用`

> ControlMed: Adding Reasoning Control to Medical Language Model

# 摘要

> 推理大型语言模型 (LLMs) 凭借其增强的准确性和可解释性，正在被越来越多地应用于医疗领域，因为临床决策的生死攸关性需要可靠的支持。尽管取得了这些进展，现有的推理 LLMs 通常会产生冗长的推理过程，导致显著的计算开销和响应延迟。这些限制阻碍了它们在现实世界临床环境中的实际部署。为了解决这些挑战，我们引入了 	extbf{ControlMed}，这是一种医疗语言模型，允许用户通过细粒度控制标记在推理时主动控制推理过程的长度。ControlMed 通过三阶段管道进行训练：1) 在涵盖 	extit{直接} 和 	extit{推理响应} 的大规模合成医疗指令数据集上进行预训练；2) 使用多长度推理数据和显式长度控制标记进行监督微调；3) 使用基于模型的奖励信号进行强化学习，以增强事实准确性并提升响应质量。在各种英语和韩语医疗基准测试上的实验结果表明，我们的模型与现有最先进的模型相比，能够达到相似或更好的性能。此外，用户可以根据需要灵活控制推理长度，从而平衡推理准确性和计算效率。这些发现表明，ControlMed 是临床问答和医学信息分析的实用且灵活的解决方案。

> Reasoning Large Language Models (LLMs) with enhanced accuracy and explainability are increasingly being adopted in the medical domain, as the life-critical nature of clinical decision-making demands reliable support. Despite these advancements, existing reasoning LLMs often generate unnecessarily lengthy reasoning processes, leading to significant computational overhead and response latency. These limitations hinder their practical deployment in real-world clinical environments. To address these challenges, we introduce \textbf{ControlMed}, a medical language model that enables users to actively control the length of the reasoning process at inference time through fine-grained control markers. ControlMed is trained through a three-stage pipeline: 1) pre-training on a large-scale synthetic medical instruction dataset covering both \textit{direct} and \textit{reasoning responses}; 2) supervised fine-tuning with multi-length reasoning data and explicit length-control markers; and 3) reinforcement learning with model-based reward signals to enhance factual accuracy and response quality. Experimental results on a variety of English and Korean medical benchmarks demonstrate that our model achieves similar or better performance compared to state-of-the-art models. Furthermore, users can flexibly balance reasoning accuracy and computational efficiency by controlling the reasoning length as needed. These findings demonstrate that ControlMed is a practical and adaptable solution for clinical question answering and medical information analysis.

[Arxiv](https://arxiv.org/abs/2507.22545)