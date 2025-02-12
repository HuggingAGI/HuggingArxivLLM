# Prot2Chat：融合序列与结构的蛋白质大型语言模型

发布时间：2025年02月07日

`LLM应用` `生命科学` `生物信息学`

> Prot2Chat: Protein LLM with Early Fusion of Sequence and Structure

# 摘要

> 蛋白质在生物体中扮演着关键角色，但理解其功能仍面临诸多挑战：分类方法的局限性、难以有效利用空间结构信息以及缺乏系统化的蛋白质问答评估体系。为应对这些挑战，我们提出了Prot2Chat框架，通过统一模块巧妙融合多模态蛋白质表示与自然语言，实现大型语言模型（LLM）驱动的回答生成。我们的模型采用改进版ProteinMPNN编码器，可统一编码蛋白质序列和结构信息；配备交叉注意力机制的蛋白质-文本适配器；以及LLaMA3解码器。为提升训练效率，我们冻结编码器并采用LoRA技术优化解码器。实验结果表明，无论是自动评估指标还是专家评估，我们的模型均表现出色。零样本预测进一步证明了其强大的泛化能力。这一框架为连接蛋白质知识与自然语言理解提供了创新解决方案，有望推动蛋白质研究领域实现重大突破。

> Proteins play a pivotal role in living organisms, yet understanding their functions presents significant challenges, including the limited flexibility of classification-based methods, the inability to effectively leverage spatial structural information, and the lack of systematic evaluation metrics for protein Q&A systems. To address these limitations, we propose Prot2Chat, a novel framework that integrates multimodal protein representations with natural language through a unified module, enabling large language model (LLM)-driven answer generation. Our model incorporates a modified ProteinMPNN encoder, which encodes protein sequence and structural information in a unified manner, a protein-text adapter with cross-attention mechanisms, and a LLaMA3 decoder. To optimize training efficiency, we freeze the encoder and employ LoRA techniques for the decoder. We conducted experiments on two datasets, both automated metrics and expert evaluations demonstrate the superior performance of our model. Furthermore, zero-shot prediction results highlight its strong generalization capabilities. This framework offers a promising solution for bridging protein domain knowledge with natural language understanding, paving the way for transformative advancements in protein-related research.

[Arxiv](https://arxiv.org/abs/2502.06846)