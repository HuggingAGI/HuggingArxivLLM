# # 摘要
PatientDx: 整合大型语言模型，守护医疗数据隐私安全

发布时间：2025年04月24日

`LLM应用` `数据科学`

> PatientDx: Merging Large Language Models for Protecting Data-Privacy in Healthcare

# 摘要

> 微调大型语言模型（LLMs）已成为提升模型在特定任务上性能的默认方法，但这一过程往往需要在大量敏感数据上进行训练，从而引发严重数据隐私问题。医疗领域作为数据隐私问题的重灾区，我们提出了PatientDx——一种无需在患者数据上进行微调或适应的模型融合框架，专为医疗预测任务设计。我们的提案基于近期提出的模型融合技术，旨在优化构建块融合策略。PatientDx采用适应数值推理的关键模型，并根据性能指标在示例上调整超参数，而无需对LLM进行训练。实验结果表明，在MIMIC-IV数据集的死亡率任务中，与初始模型相比，AUROC指标提升了7%。此外，我们的提案在不损害性能的情况下，相比微调模型更不易出现数据泄露问题。最后，我们通过案例研究定性展示了提案的能力。我们的最佳模型已公开发布，访问地址为https://huggingface.co/Jgmorenof/mistral_merged_0_4。


> Fine-tuning of Large Language Models (LLMs) has become the default practice for improving model performance on a given task. However, performance improvement comes at the cost of training on vast amounts of annotated data which could be sensitive leading to significant data privacy concerns. In particular, the healthcare domain is one of the most sensitive domains exposed to data privacy issues. In this paper, we present PatientDx, a framework of model merging that allows the design of effective LLMs for health-predictive tasks without requiring fine-tuning nor adaptation on patient data. Our proposal is based on recently proposed techniques known as merging of LLMs and aims to optimize a building block merging strategy. PatientDx uses a pivotal model adapted to numerical reasoning and tunes hyperparameters on examples based on a performance metric but without training of the LLM on these data. Experiments using the mortality tasks of the MIMIC-IV dataset show improvements up to 7% in terms of AUROC when compared to initial models. Additionally, we confirm that when compared to fine-tuned models, our proposal is less prone to data leak problems without hurting performance. Finally, we qualitatively show the capabilities of our proposal through a case study. Our best model is publicly available at https://huggingface.co/ Jgmorenof/mistral\_merged\_0\_4.

[Arxiv](https://arxiv.org/abs/2504.17360)