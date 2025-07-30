# MAGE：多模态对齐与生成增强，通过融合视觉与语义空间实现。

发布时间：2025年07月29日

`LLM应用` `人工智能`

> MAGE: Multimodal Alignment and Generation Enhancement via Bridging Visual and Semantic Spaces

# 摘要

> 在多模态学习领域，如何有效应对视觉数据编码后的空间与语义损失仍是当前研究的重点挑战。这源于大型多模态模型的表现与其视觉编码器与语言模型间的协同程度密切相关。现有方法往往受限于向量差距或语义鸿沟，导致信息在传递过程中发生损失。针对这一问题，我们创新性地提出了MAGE（多模态对齐与生成增强）框架，通过独特的对齐机制成功连接视觉与文本的语义空间。借助智能对齐网络（IAN），MAGE实现了维度与语义的精准匹配。为缩小同义异质数据间的差距，我们采用了结合交叉熵与均方误差的训练策略，显著提升了对齐效果。此外，为强化MAGE的"任意到任意"能力，我们构建了一个多模态工具调用指令微调数据集，拓展了模型的输出边界。最终，MAGE在MME、MMBench和SEED等评估基准上均显著超越现有同类模型。完整代码及附录已开源：https://github.com/GTCOM-NLP/MAGE。

> In the latest advancements in multimodal learning, effectively addressing the spatial and semantic losses of visual data after encoding remains a critical challenge. This is because the performance of large multimodal models is positively correlated with the coupling between visual encoders and large language models. Existing approaches often face issues such as vector gaps or semantic disparities, resulting in information loss during the propagation process. To address these issues, we propose MAGE (Multimodal Alignment and Generation Enhancement), a novel framework that bridges the semantic spaces of vision and text through an innovative alignment mechanism. By introducing the Intelligent Alignment Network (IAN), MAGE achieves dimensional and semantic alignment. To reduce the gap between synonymous heterogeneous data, we employ a training strategy that combines cross-entropy and mean squared error, significantly enhancing the alignment effect. Moreover, to enhance MAGE's "Any-to-Any" capability, we developed a fine-tuning dataset for multimodal tool-calling instructions to expand the model's output capability boundaries. Finally, our proposed multimodal large model architecture, MAGE, achieved significantly better performance compared to similar works across various evaluation benchmarks, including MME, MMBench, and SEED. Complete code and appendix are available at: https://github.com/GTCOM-NLP/MAGE.

[Arxiv](https://arxiv.org/abs/2507.21741)