# MELLA：连接语言能力与文化根基，为低资源语言的多语言模型搭建桥梁。

发布时间：2025年08月07日

`LLM应用

论文摘要：多模态大型语言模型（MLLMs）在高资源语言中展现出了卓越的能力，但在低资源语言环境下效果明显减弱。当前的多语言增强方法往往局限于文本模态或依赖机器翻译，虽然这些方法帮助模型获得基础语言能力并生成“薄描述”，但忽视了多模态信息量和文化根基的重要性，这两者对有效服务低资源语言用户至关重要。为解决这一问题，本研究在低资源语言环境下，提出了真正有效的MLLM的两大核心目标：1）语言能力，2）文化根基，特别强调文化意识。为此，我们提出了一种双源策略，指导数据收集以适应每个目标，具体包括从网络中获取原生网页的替代文本用于文化信息，以及利用MLLM生成的字幕用于语言能力。作为具体实现，我们引入了MELLA，一个多模态、多语言的数据集。实验结果表明，在MELLA上进行微调后，八种语言在各种MLLM骨架上都表现出了整体性能的显著提升，模型能够生成“厚描述”。我们验证了性能提升源于文化知识的增强和语言能力的增强。我们的数据集可以在https://opendatalab.com/applyMultilingualCorpus找到。` `人工智能` `跨文化交流`

> MELLA: Bridging Linguistic Capability and Cultural Groundedness for Low-Resource Language MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在高资源语言中展现出了卓越的能力，但在低资源语言环境下效果明显减弱。当前的多语言增强方法往往局限于文本模态或依赖机器翻译，虽然这些方法帮助模型获得基础语言能力并生成“薄描述”，但忽视了多模态信息量和文化根基的重要性，这两者对有效服务低资源语言用户至关重要。为解决这一问题，本研究在低资源语言环境下，提出了真正有效的MLLM的两大核心目标：1）语言能力，2）文化根基，特别强调文化意识。为此，我们提出了一种双源策略，指导数据收集以适应每个目标，具体包括从网络中获取原生网页的替代文本用于文化信息，以及利用MLLM生成的字幕用于语言能力。作为具体实现，我们引入了MELLA，一个多模态、多语言的数据集。实验结果表明，在MELLA上进行微调后，八种语言在各种MLLM骨架上都表现出了整体性能的显著提升，模型能够生成“厚描述”。我们验证了性能提升源于文化知识的增强和语言能力的增强。我们的数据集可以在https://opendatalab.com/applyMultilingualCorpus找到。

> Multimodal Large Language Models (MLLMs) have shown remarkable performance in high-resource languages. However, their effectiveness diminishes significantly in the contexts of low-resource languages. Current multilingual enhancement methods are often limited to text modality or rely solely on machine translation. While such approaches help models acquire basic linguistic capabilities and produce "thin descriptions", they neglect the importance of multimodal informativeness and cultural groundedness, both of which are crucial for serving low-resource language users effectively. To bridge this gap, in this study, we identify two significant objectives for a truly effective MLLM in low-resource language settings, namely 1) linguistic capability and 2) cultural groundedness, placing special emphasis on cultural awareness. To achieve these dual objectives, we propose a dual-source strategy that guides the collection of data tailored to each goal, sourcing native web alt-text for culture and MLLM-generated captions for linguistics. As a concrete implementation, we introduce MELLA, a multimodal, multilingual dataset. Experiment results show that after fine-tuning on MELLA, there is a general performance improvement for the eight languages on various MLLM backbones, with models producing "thick descriptions". We verify that the performance gains are from both cultural knowledge enhancement and linguistic capability enhancement. Our dataset can be found at https://opendatalab.com/applyMultilingualCorpus.

[Arxiv](https://arxiv.org/abs/2508.05502)