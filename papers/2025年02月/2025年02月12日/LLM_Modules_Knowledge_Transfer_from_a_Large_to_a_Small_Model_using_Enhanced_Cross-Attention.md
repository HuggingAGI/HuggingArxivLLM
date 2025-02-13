# LLM 模块：借助增强交叉注意力机制，实现从大型模型到小型模型的知识迁移

发布时间：2025年02月12日

`LLM理论` `模型压缩` `知识迁移`

> LLM Modules: Knowledge Transfer from a Large to a Small Model using Enhanced Cross-Attention

# 摘要

> 我们提出了一种基于增强交叉注意力机制的LLM模块架构，用于将大型预训练模型的知识迁移到更小的模型中。在我们的方案中，Qwen2-1.5B模型被冻结，其表示通过专门设计的注意力层传递给GPT-Neo-125M模型，该模型在有限计算资源下进行训练。实验结果表明，在Bespoke-Stratos-17k数据集上，经过15个训练周期后，结合模型生成的回答质量与蒸馏方法相当。本文将探讨模块化方法的优势，并通过具体输入查询和比较分析进行说明，同时展望该方法的进一步扩展前景。

> In this work, we propose an architecture of LLM Modules that enables the transfer of knowledge from a large pre-trained model to a smaller model using an Enhanced Cross-Attention mechanism. In the proposed scheme, the Qwen2-1.5B model is frozen and its representations are passed through specially designed attention layers to the GPT-Neo-125M model, which is trained on limited computational resources. Experimental results on the Bespoke-Stratos-17k dataset demonstrate that after 15 epochs of training, the combined model generates responses comparable in quality to those obtained by distillation. We discuss the advantages of the modular approach, provide examples of input queries and comparative analysis, and outline prospects for further extension of the method.

[Arxiv](https://arxiv.org/abs/2502.08213)