# GenEDA: 通过多模态编码解码对齐基础模型，在电路网表中释放生成式推理的潜力

发布时间：2025年04月13日

`LLM应用` `集成电路` `电路设计`

> GenEDA: Unleashing Generative Reasoning on Netlist via Multimodal Encoder-Decoder Aligned Foundation Model

# 摘要

> 基础AI的成功推动了电路基础模型的研究，这些模型被定制用于辅助集成电路（IC）设计流程。然而，现有的预训练电路模型通常局限于独立的预测任务编码器或生成任务解码器。这两种模型类型各自独立开发，处理不同的电路模态，且存在于不同的潜空间中，这限制了它们在更高级应用中相互补充的能力。本研究中，我们提出了GenEDA，这是首个在共享潜空间内对齐电路编码器与解码器的框架。GenEDA架起了基于图的电路表示与基于文本的大语言模型（LLMs）之间的桥梁，实现了它们各自潜空间之间的通信。为了实现这一对齐，我们提出了两种支持开源可训练LLMs和商用冻结LLMs的范式。基于这一对齐架构，GenEDA实现了三项前所未有的网表生成推理任务，其中模型能够从不同粒度的低级网表反向生成高级功能。这些任务将传统的门级预测扩展为完整电路功能的直接生成。实验表明，GenEDA显著提升了先进LLMs（如GPT-4o和DeepSeek-V3）在所有任务中的性能表现。

> The success of foundation AI has motivated the research of circuit foundation models, which are customized to assist the integrated circuit (IC) design process. However, existing pre-trained circuit models are typically limited to standalone encoders for predictive tasks or decoders for generative tasks. These two model types are developed independently, operate on different circuit modalities, and reside in separate latent spaces, which restricts their ability to complement each other for more advanced applications. In this work, we present GenEDA, the first framework that aligns circuit encoders with decoders within a shared latent space. GenEDA bridges the gap between graph-based circuit representations and text-based large language models (LLMs), enabling communication between their respective latent spaces. To achieve the alignment, we propose two paradigms that support both open-source trainable LLMs and commercial frozen LLMs. Built on this aligned architecture, GenEDA enables three unprecedented generative reasoning tasks over netlists, where the model reversely generates the high-level functionality from low-level netlists in different granularities. These tasks extend traditional gate-type prediction to direct generation of full-circuit functionality. Experiments demonstrate that GenEDA significantly boosts advanced LLMs' (e.g., GPT-4o and DeepSeek-V3) performance in all tasks.

[Arxiv](https://arxiv.org/abs/2504.09485)