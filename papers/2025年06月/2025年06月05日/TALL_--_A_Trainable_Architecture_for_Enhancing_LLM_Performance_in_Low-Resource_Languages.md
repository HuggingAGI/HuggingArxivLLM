# # **TALL——助力低资源语言LLM性能提升的可训练架构**

发布时间：2025年06月05日

`LLM应用` `语言模型`

> TALL -- A Trainable Architecture for Enhancing LLM Performance in Low-Resource Languages

# 摘要

> 大型语言模型（LLMs）在高资源语言中表现出色，但在低资源语言方面表现欠佳，主要因为训练数据有限。本文介绍了一种名为TALL（增强低资源语言LLM性能的可训练架构）的解决方案，它将一个LLM与两个双语翻译模型相结合。TALL通过维度对齐层和自定义变换器，将低资源语言输入转换为高资源语言表示，既利用了LLM的能力，又保留了语言特征。我们在希伯来语上的实验结果显示，与直接使用、简单翻译和微调等几种基线方法相比，TALL取得了显著提升。该架构采用了一种参数高效策略，冻结预训练组件，仅训练轻量级适配模块，在计算效率与性能提升之间实现了平衡。

> Large Language Models (LLMs) excel in high-resource languages but struggle with low-resource languages due to limited training data. This paper presents TALL (Trainable Architecture for Enhancing LLM Performance in Low-Resource Languages), which integrates an LLM with two bilingual translation models. TALL transforms low-resource inputs into high-resource representations, leveraging the LLM's capabilities while preserving linguistic features through dimension alignment layers and custom transformers. Our experiments on Hebrew demonstrate significant improvements over several baselines, including direct use, naive translation, and fine-tuning approaches. The architecture employs a parameter-efficient strategy, freezing pre-trained components while training only lightweight adapter modules, balancing computational efficiency with performance gains.

[Arxiv](https://arxiv.org/abs/2506.05057)