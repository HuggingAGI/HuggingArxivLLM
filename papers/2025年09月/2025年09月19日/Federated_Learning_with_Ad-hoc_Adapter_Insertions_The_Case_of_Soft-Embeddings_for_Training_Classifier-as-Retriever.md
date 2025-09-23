# 联邦学习结合临时适配器插入：以软嵌入训练分类器即检索器为例

发布时间：2025年09月19日

`RAG` `基础理论`

> Federated Learning with Ad-hoc Adapter Insertions: The Case of Soft-Embeddings for Training Classifier-as-Retriever

# 摘要

> 现有检索增强生成（RAG）解决方案若要应用于新知识领域，需更新其编码器——这些编码器通常是预训练大型语言模型（LLMs）。然而，全量微调大模型计算与内存成本极高，在资源受限的边缘设备上甚至完全不可行。为此，我们提出一种新型编码器架构：采用冻结的小型语言模型（SLM）——其满足边缘设备的内存限制——并在SLM的Transformer块前插入小型适配器网络。可训练的适配器接收新语料的令牌嵌入，学习生成增强软嵌入，且更新所需计算资源远低于全量微调。我们还提出一种新型检索机制：在SLM编码器上附加分类头，通过训练使其学习输入嵌入与对应文档的相似性映射。最后，为实现在边缘设备上对（i）编码器软嵌入和（ii）分类器检索器的在线微调，我们引入联邦学习（FL）与差分隐私（DP），构建了高效、隐私保护的产品级训练方案。我们对所提方法进行了理论分析，在梯度方差的温和假设下，证明了其在一般平滑非凸损失函数上的收敛保证。大量数值实验验证了：（i）软嵌入对编码器的增强效果，（ii）分类器训练对检索器的改进作用，以及（iii）联邦学习在加速训练中的关键价值。

> When existing retrieval-augmented generation (RAG) solutions are intended to be used for new knowledge domains, it is necessary to update their encoders, which are taken to be pretrained large language models (LLMs). However, fully finetuning these large models is compute- and memory-intensive, and even infeasible when deployed on resource-constrained edge devices. We propose a novel encoder architecture in this work that addresses this limitation by using a frozen small language model (SLM), which satisfies the memory constraints of edge devices, and inserting a small adapter network before the transformer blocks of the SLM. The trainable adapter takes the token embeddings of the new corpus and learns to produce enhanced soft embeddings for it, while requiring significantly less compute power to update than full fine-tuning. We further propose a novel retrieval mechanism by attaching a classifier head to the SLM encoder, which is trained to learn a similarity mapping of the input embeddings to their corresponding documents. Finally, to enable the online fine-tuning of both (i) the encoder soft embeddings and (ii) the classifier-as-retriever on edge devices, we adopt federated learning (FL) and differential privacy (DP) to achieve an efficient, privacy-preserving, and product-grade training solution. We conduct a theoretical analysis of our methodology, establishing convergence guarantees under mild assumptions on gradient variance when deployed for general smooth nonconvex loss functions. Through extensive numerical experiments, we demonstrate (i) the efficacy of obtaining soft embeddings to enhance the encoder, (ii) training a classifier to improve the retriever, and (iii) the role of FL in achieving speedup.

[Arxiv](https://arxiv.org/abs/2509.16508)