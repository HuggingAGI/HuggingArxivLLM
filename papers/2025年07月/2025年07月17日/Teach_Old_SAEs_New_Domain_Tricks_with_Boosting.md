# 助力旧模型焕发新机：用Boosting技术赋予SAEs跨领域新技能

发布时间：2025年07月17日

`LLM理论` `机器学习`

> Teach Old SAEs New Domain Tricks with Boosting

# 摘要

> 稀疏自动编码器在解释大型语言模型的内部表示方面已经展现出强大的能力，但它们往往难以捕捉训练语料库中不常见的领域特定特征。本文提出了一种无需重新训练的残差学习方法，有效解决了这一特征盲的问题。我们通过训练一个辅助稀疏自动编码器，专门建模预训练稀疏自动编码器在领域特定文本上的重建误差，成功捕捉到主模型未能捕捉到的特征。在推理过程中，将两个模型的输出相加，显著提升了大型语言模型在多个专业领域的交叉熵和可解释方差指标。实验结果表明，该方法能够高效地将新的领域知识整合到现有稀疏自动编码器中，同时保持其在通用任务上的性能。这一方法使研究人员能够有选择地增强稀疏自动编码器在特定领域的可解释性，为大型语言模型的定向机制解释开辟了新的可能性。

> Sparse Autoencoders have emerged as powerful tools for interpreting the internal representations of Large Language Models, yet they often fail to capture domain-specific features not prevalent in their training corpora. This paper introduces a residual learning approach that addresses this feature blindness without requiring complete retraining. We propose training a secondary SAE specifically to model the reconstruction error of a pretrained SAE on domain-specific texts, effectively capturing features missed by the primary model. By summing the outputs of both models during inference, we demonstrate significant improvements in both LLM cross-entropy and explained variance metrics across multiple specialized domains. Our experiments show that this method efficiently incorporates new domain knowledge into existing SAEs while maintaining their performance on general tasks. This approach enables researchers to selectively enhance SAE interpretability for specific domains of interest, opening new possibilities for targeted mechanistic interpretability of LLMs.

[Arxiv](https://arxiv.org/abs/2507.12990)