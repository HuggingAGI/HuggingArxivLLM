# GNN-ViTCap: 基于图神经网络增强的视觉Transformer多示例学习方法，用于全切片图像分类与描述生成

发布时间：2025年07月09日

`LLM应用` `图像处理`

> GNN-ViTCap: GNN-Enhanced Multiple Instance Learning with Vision Transformers for Whole Slide Image Classification and Captioning

# 摘要

> 显微镜下组织病理学图像的评估对癌症诊断和治疗至关重要。WSI 的分类和描述已成为计算机辅助病理学中的核心任务。然而，显微镜下的 WSI 存在冗余补丁和未知补丁位置等挑战，这些问题源于病理学家的主观捕捉。此外，自动生成病理描述仍面临重大挑战。为了解决这些问题，我们提出了 GNN-ViTCap 框架，用于从显微图像中进行分类和描述生成。首先，视觉特征提取器生成补丁嵌入。通过深度嵌入聚类动态聚类这些嵌入，并使用标量点积注意力机制选择代表补丁以去除冗余。我们通过构建相似性矩阵并连接每个节点的最近邻来构建图，然后应用图神经网络捕获局部和全局上下文。聚合后的图像嵌入通过线性层投影到语言模型的输入空间，并与描述令牌结合，以微调大型语言模型。我们在 BreakHis 和 PatchGastric 数据集上验证了该方法。GNN-ViTCap 在分类任务中达到 0.934 的 F1 分数和 0.963 的 AUC，在描述任务中实现 0.811 的 BLEU-4 分数和 0.569 的 METEOR 分数。实验结果表明，GNN-ViTCap 在性能上超越现有最优方法，为基于显微镜的患者诊断提供了一种可靠且高效的新方案。

> Microscopic assessment of histopathology images is vital for accurate cancer diagnosis and treatment. Whole Slide Image (WSI) classification and captioning have become crucial tasks in computer-aided pathology. However, microscopic WSI face challenges such as redundant patches and unknown patch positions due to subjective pathologist captures. Moreover, generating automatic pathology captions remains a significant challenge. To address these issues, we introduce a novel GNN-ViTCap framework for classification and caption generation from histopathological microscopic images. First, a visual feature extractor generates patch embeddings. Redundant patches are then removed by dynamically clustering these embeddings using deep embedded clustering and selecting representative patches via a scalar dot attention mechanism. We build a graph by connecting each node to its nearest neighbors in the similarity matrix and apply a graph neural network to capture both local and global context. The aggregated image embeddings are projected into the language model's input space through a linear layer and combined with caption tokens to fine-tune a large language model. We validate our method on the BreakHis and PatchGastric datasets. GNN-ViTCap achieves an F1 score of 0.934 and an AUC of 0.963 for classification, along with a BLEU-4 score of 0.811 and a METEOR score of 0.569 for captioning. Experimental results demonstrate that GNN-ViTCap outperforms state of the art approaches, offering a reliable and efficient solution for microscopy based patient diagnosis.

[Arxiv](https://arxiv.org/abs/2507.07006)