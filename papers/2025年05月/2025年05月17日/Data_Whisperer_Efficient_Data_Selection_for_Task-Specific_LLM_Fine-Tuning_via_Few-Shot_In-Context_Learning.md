# 数据低语者：通过少量样本的上下文学习，实现任务特定LLM的高效微调

发布时间：2025年05月17日

`LLM应用

论文摘要：在特定任务数据上对大型语言模型（LLMs）进行微调，是实现有效部署的关键。随着数据集规模的不断扩大，如何高效选择最优子集用于训练，成为平衡性能与计算成本的核心问题。传统数据选择方法通常需要在目标数据集上微调一个评分模型，耗时耗资源，或者依赖无法充分利用模型预测能力的启发式方法。为了解决这些挑战，我们提出了一种高效、无需训练、基于注意力机制的方法——Data Whisperer，该方法通过利用待微调模型的少量样本上下文学习能力，实现数据选择。我们在多种任务和模型上，对原始数据集和合成数据集进行了全面评估。值得注意的是，在Llama-3-8B-Instruct模型上，Data Whisperer仅使用10%的数据，就超越了完整的GSM8K数据集的表现，并以3.1个百分点的优势和7.4×的速度提升，超越了现有方法。

LLM应用` `数据科学` `机器学习`

> Data Whisperer: Efficient Data Selection for Task-Specific LLM Fine-Tuning via Few-Shot In-Context Learning

# 摘要

> 在特定任务数据上对大型语言模型（LLMs）进行微调，是实现有效部署的关键。随着数据集规模的不断扩大，如何高效选择最优子集用于训练，成为平衡性能与计算成本的核心问题。传统数据选择方法通常需要在目标数据集上微调一个评分模型，耗时耗资源，或者依赖无法充分利用模型预测能力的启发式方法。为了解决这些挑战，我们提出了一种高效、无需训练、基于注意力机制的方法——Data Whisperer，该方法通过利用待微调模型的少量样本上下文学习能力，实现数据选择。我们在多种任务和模型上，对原始数据集和合成数据集进行了全面评估。值得注意的是，在Llama-3-8B-Instruct模型上，Data Whisperer仅使用10%的数据，就超越了完整的GSM8K数据集的表现，并以3.1个百分点的优势和7.4×的速度提升，超越了现有方法。

> Fine-tuning large language models (LLMs) on task-specific data is essential for their effective deployment. As dataset sizes grow, efficiently selecting optimal subsets for training becomes crucial to balancing performance and computational costs. Traditional data selection methods often require fine-tuning a scoring model on the target dataset, which is time-consuming and resource-intensive, or rely on heuristics that fail to fully leverage the model's predictive capabilities. To address these challenges, we propose Data Whisperer, an efficient, training-free, attention-based method that leverages few-shot in-context learning with the model to be fine-tuned. Comprehensive evaluations were conducted on both raw and synthetic datasets across diverse tasks and models. Notably, Data Whisperer achieves superior performance compared to the full GSM8K dataset on the Llama-3-8B-Instruct model, using just 10% of the data, and outperforms existing methods with a 3.1-point improvement and a 7.4$\times$ speedup.

[Arxiv](https://arxiv.org/abs/2505.12212)