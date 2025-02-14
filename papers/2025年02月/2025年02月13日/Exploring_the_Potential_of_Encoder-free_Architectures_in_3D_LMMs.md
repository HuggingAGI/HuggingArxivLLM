# 无编码器架构在三维LMM中的潜力探索

发布时间：2025年02月13日

`LLM应用` `3D视觉` `多模态模型`

> Exploring the Potential of Encoder-free Architectures in 3D LMMs

# 摘要

> Encoder-free架构在2D视觉领域的初步探索已见成效，但它们能否在3D理解场景中发挥同样效能仍是一个值得探讨的问题。本文首次系统性地探究了Encoder-free架构在突破基于Encoder的3D大型多模态模型（LMMs）瓶颈方面的潜力。这些挑战主要包括：现有模型难以适应不同分辨率的点云数据，以及Encoder提取的点特征无法充分满足大型语言模型（LLMs）的语义需求。

我们明确了3D LMMs实现无Encoder化并赋予LLM承担3D编码器角色的关键要素：首先，在预训练阶段，我们提出了LLM嵌入语义编码策略，深入探究了多种点云自监督损失的影响，并创新性地提出了混合语义损失以提升高层语义提取能力。其次，在指令微调阶段，我们引入了层次化几何聚合策略，通过将归纳偏置融入LLM的早期层，使其能够有效关注点云的局部细节特征。

最终，我们成功推出了首个无Encoder的3D LMM——ENEL模型。实验结果显示，我们的70亿参数模型在分类、描述生成和视觉问答任务上分别达到了55.0%、50.92%和42.7%的优异性能，与当前最先进的ShapeLLM-13B模型不相上下。这一突破性成果充分证明，无Encoder架构在3D理解领域完全有可能取代传统的基于Encoder架构，展现出巨大的应用前景。项目代码已开源，详情请访问https://github.com/Ivan-Tang-3D/ENEL

> Encoder-free architectures have been preliminarily explored in the 2D visual domain, yet it remains an open question whether they can be effectively applied to 3D understanding scenarios. In this paper, we present the first comprehensive investigation into the potential of encoder-free architectures to overcome the challenges of encoder-based 3D Large Multimodal Models (LMMs). These challenges include the failure to adapt to varying point cloud resolutions and the point features from the encoder not meeting the semantic needs of Large Language Models (LLMs). We identify key aspects for 3D LMMs to remove the encoder and enable the LLM to assume the role of the 3D encoder: 1) We propose the LLM-embedded Semantic Encoding strategy in the pre-training stage, exploring the effects of various point cloud self-supervised losses. And we present the Hybrid Semantic Loss to extract high-level semantics. 2) We introduce the Hierarchical Geometry Aggregation strategy in the instruction tuning stage. This incorporates inductive bias into the LLM early layers to focus on the local details of the point clouds. To the end, we present the first Encoder-free 3D LMM, ENEL. Our 7B model rivals the current state-of-the-art model, ShapeLLM-13B, achieving 55.0%, 50.92%, and 42.7% on the classification, captioning, and VQA tasks, respectively. Our results demonstrate that the encoder-free architecture is highly promising for replacing encoder-based architectures in the field of 3D understanding. The code is released at https://github.com/Ivan-Tang-3D/ENEL

[Arxiv](https://arxiv.org/abs/2502.09620)