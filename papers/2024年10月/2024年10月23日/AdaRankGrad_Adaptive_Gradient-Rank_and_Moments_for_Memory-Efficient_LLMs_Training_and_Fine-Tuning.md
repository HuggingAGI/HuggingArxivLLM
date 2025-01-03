# AdaRankGrad: 自适应梯度-排名与动量，助力内存高效的LLM训练与微调

发布时间：2024年10月23日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在训练和微调过程中面临的内存和计算需求挑战，并提出了一种新的方法来减少训练内存需求并提升模型性能。论文的核心内容涉及LLM的训练动态、优化器状态、梯度秩降低等理论问题，属于对LLM训练和优化过程的深入理论研究，因此应归类为LLM理论。` `人工智能` `机器学习`

> AdaRankGrad: Adaptive Gradient-Rank and Moments for Memory-Efficient LLMs Training and Fine-Tuning

# 摘要

> # 摘要
训练和微调大型语言模型（LLMs）面临内存和计算需求的挑战，主要源于模型权重和优化器状态的规模增长。为解决这些问题，已有多种技术应运而生，如低秩适应（LoRA），即在每层的固定预训练权重中引入可训练的低秩矩阵。然而，这些方法通常不及全秩权重训练，因为它们将参数搜索限制在低秩子空间内，可能破坏训练动态，需全秩预热启动以缓解影响。本文提出一种新方法，灵感来自我们证明的现象：训练过程中，层梯度的秩逐渐降低，最终趋近于秩一。基于此，我们在Adam优化步骤中自适应降低梯度秩，采用高效的在线更新低秩投影规则，并提出随机SVD方案以高效获取投影矩阵。该方法通过自适应低秩梯度更新实现全参数微调，显著减少训练内存需求，并在预训练和微调中提升模型性能。最后，我们提供了方法的收敛性分析，并展示了其在语言和生物基础模型训练与微调中的优势。

> Training and fine-tuning large language models (LLMs) come with challenges related to memory and computational requirements due to the increasing size of the model weights and the optimizer states. Various techniques have been developed to tackle these challenges, such as low-rank adaptation (LoRA), which involves introducing a parallel trainable low-rank matrix to the fixed pre-trained weights at each layer. However, these methods often fall short compared to the full-rank weight training approach, as they restrict the parameter search to a low-rank subspace. This limitation can disrupt training dynamics and require a full-rank warm start to mitigate the impact. In this paper, we introduce a new method inspired by a phenomenon we formally prove: as training progresses, the rank of the estimated layer gradients gradually decreases, and asymptotically approaches rank one. Leveraging this, our approach involves adaptively reducing the rank of the gradients during Adam optimization steps, using an efficient online-updating low-rank projections rule. We further present a randomized SVD scheme for efficiently finding the projection matrix. Our technique enables full-parameter fine-tuning with adaptive low-rank gradient updates, significantly reducing overall memory requirements during training compared to state-of-the-art methods while improving model performance in both pretraining and fine-tuning. Finally, we provide a convergence analysis of our method and demonstrate its merits for training and fine-tuning language and biological foundation models.

[Arxiv](https://arxiv.org/abs/2410.17881)