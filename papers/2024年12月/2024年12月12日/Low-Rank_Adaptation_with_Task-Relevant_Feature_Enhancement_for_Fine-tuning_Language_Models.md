# 基于任务相关特征增强的低秩适应方法用于语言模型微调

发布时间：2024年12月12日

`LLM理论

**理由**：这篇论文主要讨论的是参数高效的预训练大模型微调方法（LoRATRF），这是一种针对大语言模型（LLM）的理论改进方法。它通过编辑神经网络表示来增强任务相关特征，属于对LLM的理论研究和优化，因此归类为LLM理论。` `机器学习`

> Low-Rank Adaptation with Task-Relevant Feature Enhancement for Fine-tuning Language Models

# 摘要

> # 摘要
参数高效的预训练大模型微调因其高效性备受关注。LoRA 作为主流方法之一，基于低维优化假设。然而，LoRA 与全微调在新任务学习上仍有明显差距。为此，我们提出 LoRATRF 方法，通过编辑神经网络表示来增强任务相关特征。该方法设计了任务感知过滤器，从隐藏表示中智能提取任务关键知识。实验表明，在自然语言理解、常识推理和数学推理等任务上，LoRATRF 不仅减少了 33.71% 的参数，还超越了现有低秩方法的性能表现。

> Fine-tuning pre-trained large language models in a parameter-efficient manner is widely studied for its effectiveness and efficiency. LoRA is one of the most widely used methods, which assumes that the optimization process is essentially low dimensional. Although LoRA has demonstrated commendable performance, there remains a significant performance gap between LoRA and full fine-tuning when learning new tasks. In this work, we propose Low-Rank Adaptation with Task-Relevant Feature Enhancement(LoRATRF) for enhancing task-relevant features from the perspective of editing neural network representations. To prioritize task-relevant features, a task-aware filter that selectively extracts valuable knowledge from hidden representations for the target or current task is designed. As the experiments on a vareity of datasets including NLU, commonsense reasoning and mathematical reasoning tasks demonstrates, our method reduces 33.71% parameters and achieves better performance on a variety of datasets in comparison with SOTA low-rank methods.

[Arxiv](https://arxiv.org/abs/2412.09827)