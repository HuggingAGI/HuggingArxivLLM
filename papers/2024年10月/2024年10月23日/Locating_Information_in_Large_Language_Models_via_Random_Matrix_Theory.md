# 利用随机矩阵理论在大型语言模型中定位信息

发布时间：2024年10月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的内部机制，特别是通过随机矩阵理论（RMT）分析预训练的Transformer模型的权重矩阵。研究涉及模型的学习结构、特征学习的区域以及微调和对齐背景下小奇异值的重要性。这些内容属于对LLM内部工作机制的理论性研究，因此归类为“LLM理论”。` `人工智能` `机器学习`

> Locating Information in Large Language Models via Random Matrix Theory

# 摘要

> 随着大型语言模型（LLMs）在AI应用中的核心地位日益凸显，深入了解其内部机制变得愈发重要。本研究利用随机矩阵理论（RMT）作为零信息假设，分析了预训练的Transformer模型（如BERT和Llama）的权重矩阵。随机初始化的权重完全符合RMT预测，但训练后会出现偏差，帮助我们定位模型中的学习结构。我们识别出所有块和架构中一致的层类型特定行为。通过精确定位偏离RMT预测的区域，我们突出了特征学习的区域，并通过与相应层的激活协方差矩阵的比较来验证这一点。我们的方法提供了一种诊断工具，仅使用训练后的矩阵即可识别Transformer权重中的相关区域。此外，我们还探讨了LLMs中微调和对齐背景下小奇异值重要性的争议。研究发现，微调后的小奇异值在模型能力中扮演关键角色，移除它们可能损害模型的对齐。

> As large language models (LLMs) become central to AI applications, gaining a deeper understanding of their inner workings is increasingly important. In this work, we analyze the weight matrices of pretrained transformer models -- specifically BERT and Llama -- using random matrix theory (RMT) as a zero-information hypothesis. While randomly initialized weights perfectly agree with RMT predictions, deviations emerge after training, allowing us to locate learned structures within the models. We identify layer-type specific behaviors that are consistent across all blocks and architectures considered. By pinpointing regions that deviate from RMT predictions, we highlight areas of feature learning and confirm this through comparisons with the activation covariance matrices of the corresponding layers. Our method provides a diagnostic tool for identifying relevant regions in transformer weights using only the trained matrices. Additionally, we address the ongoing debate regarding the significance of small singular values in the context of fine-tuning and alignment in LLMs. Our findings reveal that, after fine-tuning, small singular values play a crucial role in the models' capabilities, suggesting that removing them in an already aligned transformer can be detrimental, as it may compromise model alignment.

[Arxiv](https://arxiv.org/abs/2410.17770)