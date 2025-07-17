# # Quantized Rank Reduction: A Communications-Efficient Federated Learning Scheme for Network-Critical Applications
# 量化秩减少：适用于网络关键应用的通信高效联邦学习方案

发布时间：2025年07月15日

`其他` `数据隐私`

> Quantized Rank Reduction: A Communications-Efficient Federated Learning Scheme for Network-Critical Applications

# 摘要

> 联邦学习是一种机器学习方法，允许多个设备协作训练共享模型，同时无需交换原始数据，从而确保数据隐私和安全。每个设备仅在本地数据上训练模型并共享更新，避免了数据泄露。然而，设备与中央服务器之间频繁的模型更新交换带来了较高的通信开销。本文提出了一种通信高效的联邦学习方案，通过神经网络梯度的低秩近似和量化技术，显著降低了去中心化学习的网络负载，同时保持了模型的高准确性。

> Federated learning is a machine learning approach that enables multiple devices (i.e., agents) to train a shared model cooperatively without exchanging raw data. This technique keeps data localized on user devices, ensuring privacy and security, while each agent trains the model on their own data and only shares model updates. The communication overhead is a significant challenge due to the frequent exchange of model updates between the agents and the central server. In this paper, we propose a communication-efficient federated learning scheme that utilizes low-rank approximation of neural network gradients and quantization to significantly reduce the network load of the decentralized learning process with minimal impact on the model's accuracy.

[Arxiv](https://arxiv.org/abs/2507.11183)