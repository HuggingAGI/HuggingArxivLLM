# 大规模角色数据工程下的对话语言模型

发布时间：2024年12月12日

`LLM应用` `对话系统` `开放域`

> Dialogue Language Model with Large-Scale Persona Data Engineering

# 摘要

> 在开放域对话系统的运用中，保持角色的一致性极为重要，像 ChatGPT 这类模型就是很好的例子。尽管有了显著进步，可当前角色对话数据集规模有限、多样性不足，依旧是达成强大且角色一致的对话模型的难题。在此次研究里，受大规模预训练成功的启发，我们推出了 PPDS，这是一个开放域角色对话系统，它在角色对话数据集上开展了广泛的生成式预训练，以提升角色一致性。具体而言，我们给出了一个角色提取模型，能够自主且精准地生成大量角色对话数据集。另外，我们还公布了一种开创性的角色增强技术，用以处理构建数据集中固有的无效角色偏差。定量和人工评估均一致表明我们所提出模型的响应质量优越、角色一致性良好，凸显了其有效性。

> Maintaining persona consistency is paramount in the application of open-domain dialogue systems, as exemplified by models like ChatGPT. Despite significant advancements, the limited scale and diversity of current persona dialogue datasets remain challenges to achieving robust persona-consistent dialogue models. In this study, drawing inspiration from the success of large-scale pre-training, we introduce PPDS, an open-domain persona dialogue system that employs extensive generative pre-training on a persona dialogue dataset to enhance persona consistency. Specifically, we present a persona extraction model designed to autonomously and precisely generate vast persona dialogue datasets. Additionally, we unveil a pioneering persona augmentation technique to address the invalid persona bias inherent in the constructed dataset. Both quantitative and human evaluations consistently highlight the superior response quality and persona consistency of our proposed model, underscoring its effectiveness.

[Arxiv](https://arxiv.org/abs/2412.09034)