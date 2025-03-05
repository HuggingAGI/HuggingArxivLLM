# 助教小模型相互讨论，通过选择性理由优化听取第二意见有帮助

发布时间：2025年03月04日

`LLM应用` `人工智能`

> It Helps to Take a Second Opinion: Teaching Smaller LLMs to Deliberate Mutually via Selective Rationale Optimisation

# 摘要

> 超大型语言模型（LLMs）如GPT-4已展现出通过生成并自我精炼逐步推理的能力来处理复杂任务。较小规模的语言模型（SLMs，通常参数量低于130亿）通过知识蒸馏利用超大模型生成的数据得到了改进。然而，API成本、版权、法律及伦理政策等各种实际限制因素阻碍了使用大型（通常不透明）模型来训练用于商业用途的更小模型。在提升SLM探索可能推理空间并通过自我思辨评估这些推理的能力方面，目前取得的进展有限。

为解决这一问题，我们提出了COALITION，这是一个可训练的框架，促进同一SLM的两个变体之间的交互，并训练它们生成和精炼优化于最终任务的推理。这两个变体会表现出不同的行为，在生成和精炼推理的过程中产生一组多样化的候选推理。随后，通过选择性推理优化（SRO），模型训练偏好生成那些能最大化生成正确答案可能性的推理候选。在推理阶段，COALITION利用一个控制器选择合适的变体来生成和精炼推理。

在涵盖数学问题、常识推理和自然语言推理的五个不同数据集上，COALITION相较于多个基线模型提升了最高5%的性能。我们的消融研究表明，两个变体之间的跨通信效果优于单一模型自我精炼推理。我们还展示了COALITION在不同规模（40亿至140亿参数）和不同模型家族（Mistral、Llama、Qwen、Phi）中的适用性。我们已在GitHub上开源了本工作的代码：https://github.com/Sohanpatnaik106/coalition。


> Very large language models (LLMs) such as GPT-4 have shown the ability to handle complex tasks by generating and self-refining step-by-step rationales. Smaller language models (SLMs), typically with < 13B parameters, have been improved by using the data generated from very-large LMs through knowledge distillation. However, various practical constraints such as API costs, copyright, legal and ethical policies restrict using large (often opaque) models to train smaller models for commercial use. Limited success has been achieved at improving the ability of an SLM to explore the space of possible rationales and evaluate them by itself through self-deliberation. To address this, we propose COALITION, a trainable framework that facilitates interaction between two variants of the same SLM and trains them to generate and refine rationales optimized for the end-task. The variants exhibit different behaviors to produce a set of diverse candidate rationales during the generation and refinement steps. The model is then trained via Selective Rationale Optimization (SRO) to prefer generating rationale candidates that maximize the likelihood of producing the ground-truth answer. During inference, COALITION employs a controller to select the suitable variant for generating and refining the rationales. On five different datasets covering mathematical problems, commonsense reasoning, and natural language inference, COALITION outperforms several baselines by up to 5%. Our ablation studies reveal that cross-communication between the two variants performs better than using the single model to self-refine the rationales. We also demonstrate the applicability of COALITION for LMs of varying scales (4B to 14B parameters) and model families (Mistral, Llama, Qwen, Phi). We release the code for this work at https://github.com/Sohanpatnaik106/coalition.

[Arxiv](https://arxiv.org/abs/2503.02463)