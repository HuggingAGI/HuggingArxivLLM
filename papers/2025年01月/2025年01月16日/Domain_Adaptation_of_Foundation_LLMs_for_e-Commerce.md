# 基础LLM在电商领域的适应性优化

发布时间：2025年01月16日

`LLM应用

理由：这篇论文介绍了专门为电子商务领域定制的大型语言模型 e-Llama，并详细描述了其训练方法和评估过程。这属于将大型语言模型应用于特定领域（电子商务）的实际应用场景，因此归类为LLM应用。` `电子商务` `语言模型`

> Domain Adaptation of Foundation LLMs for e-Commerce

# 摘要

> 我们推出了 e-Llama 模型：80 亿和 700 亿参数的大型语言模型，专为电子商务领域量身定制。这些模型作为基础模型，具备丰富的电商知识，为指令微调和精细调整打下坚实基础。e-Llama 模型通过对 Llama 3.1 基础模型在 1 万亿个领域数据上的持续预训练获得。
    我们详细阐述了方法，并通过一系列消融研究验证了超参数选择的合理性。为了评估模型在电商领域的适应能力，我们设计并实施了一组多语言的电商专用评估任务。
    研究表明，精心设计的训练设置可以使 Llama 3.1 模型在不影响通用任务性能的前提下适应新领域。我们还探索了将适应模型与基础模型合并的可能性，以更好地平衡不同领域的性能表现。

> We present the e-Llama models: 8 billion and 70 billion parameter large language models that are adapted towards the e-commerce domain. These models are meant as foundation models with deep knowledge about e-commerce, that form a base for instruction- and fine-tuning. The e-Llama models are obtained by continuously pretraining the Llama 3.1 base models on 1 trillion tokens of domain-specific data.
  We discuss our approach and motivate our choice of hyperparameters with a series of ablation studies. To quantify how well the models have been adapted to the e-commerce domain, we define and implement a set of multilingual, e-commerce specific evaluation tasks.
  We show that, when carefully choosing the training setup, the Llama 3.1 models can be adapted towards the new domain without sacrificing significant performance on general domain tasks. We also explore the possibility of merging the adapted model and the base model for a better control of the performance trade-off between domains.

[Arxiv](https://arxiv.org/abs/2501.09706)