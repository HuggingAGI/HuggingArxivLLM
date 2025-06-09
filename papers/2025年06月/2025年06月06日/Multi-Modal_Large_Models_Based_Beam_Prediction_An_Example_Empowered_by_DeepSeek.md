# # 基于多模态大模型的束预测方法：以深度求索为例

发布时间：2025年06月06日

`LLM应用`

> Multi-Modal Large Models Based Beam Prediction: An Example Empowered by DeepSeek

# 摘要

> Beam预测是减少大规模多输入多输出（MIMO）系统训练开销的有效方法。然而，现有模型在多样化场景中的泛化能力仍显不足，这仍是亟待解决的关键挑战。本文提出了一种基于DeepSeek多模态大模型的MLM-BP框架，充分考虑了多模态环境信息。具体而言，感知设备捕捉影响最优波束的散射器分布。位置信息通过分词生成文本表示，多视角图像经图像编码器处理（采用低秩适应LoRA微调）提取环境嵌入。这些嵌入随后输入大模型，并设计输出投影模块确定最优波束索引。实验结果表明，MLM-BP在仿真数据集上实现了98.1%的Top-1准确率。更值得关注的是，该框架在真实世界数据集上展现了卓越的少量样本泛化能力，仅使用30%的数据就达到了72.7%的Top-1准确率和92.4%的Top-3准确率，相较于现有小型模型，性能提升超过15%。


> Beam prediction is an effective approach to reduce training overhead in massive multiple-input multiple-output (MIMO) systems. However, existing beam prediction models still exhibit limited generalization ability in diverse scenarios, which remains a critical challenge. In this paper, we propose MLM-BP, a beam prediction framework based on the multi-modal large model released by DeepSeek, with full consideration of multi-modal environmental information. Specifically, the distribution of scatterers that impact the optimal beam is captured by the sensing devices. Then positions are tokenized to generate text-based representations, and multi-view images are processed by an image encoder, which is fine-tuned with low-rank adaptation (LoRA), to extract environmental embeddings. Finally, these embeddings are fed into the large model, and an output projection module is designed to determine the optimal beam index. Simulation results show that MLM-BP achieves 98.1% Top-1 accuracy on the simulation dataset. Additionally, it demonstrates few-shot generalization on a real-world dataset, achieving 72.7% Top-1 accuracy and 92.4% Top-3 accuracy with only 30% of the dataset, outperforming the existing small models by over 15%.

[Arxiv](https://arxiv.org/abs/2506.05921)