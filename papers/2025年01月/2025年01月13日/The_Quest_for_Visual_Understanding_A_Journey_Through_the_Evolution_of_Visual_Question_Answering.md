# 视觉理解之旅：视觉问答的演进历程

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了视觉问答（VQA）系统的发展历程，特别是其在深度学习、注意力机制和Transformer模型推动下的进展。虽然VQA涉及计算机视觉和自然语言处理的交叉领域，但其核心在于利用大型语言模型（LLM）和多模态预训练技术来提升系统的性能。论文还探讨了VQA在医疗等领域的应用，并展望了大型多模态语言模型和外部知识集成的新趋势。因此，这篇论文主要属于LLM应用的范畴。` `计算机视觉`

> The Quest for Visual Understanding: A Journey Through the Evolution of Visual Question Answering

# 摘要

> # 摘要
视觉问答（VQA）作为连接计算机视觉（CV）与自然语言处理（NLP）的桥梁，赋予了AI系统回答图像相关问题的能力。自2015年诞生以来，VQA在深度学习、注意力机制和Transformer模型的推动下飞速发展。本文回顾了VQA从起步到重大突破的历程，包括注意力机制、组合推理以及视觉语言预训练方法的崛起。我们重点分析了推动VQA系统发展的核心模型、数据集和技术，特别强调了Transformer架构和多模态预训练在近期进展中的关键作用。此外，我们还探讨了VQA在医疗等领域的应用，并指出了当前面临的挑战，如数据集偏差、模型可解释性以及常识推理的需求。最后，我们展望了大型多模态语言模型和外部知识集成的新趋势，为VQA的未来发展提供了方向。本文旨在全面梳理VQA的演进历程，展现其现状与未来潜力。

> Visual Question Answering (VQA) is an interdisciplinary field that bridges the gap between computer vision (CV) and natural language processing(NLP), enabling Artificial Intelligence(AI) systems to answer questions about images. Since its inception in 2015, VQA has rapidly evolved, driven by advances in deep learning, attention mechanisms, and transformer-based models. This survey traces the journey of VQA from its early days, through major breakthroughs, such as attention mechanisms, compositional reasoning, and the rise of vision-language pre-training methods. We highlight key models, datasets, and techniques that shaped the development of VQA systems, emphasizing the pivotal role of transformer architectures and multimodal pre-training in driving recent progress. Additionally, we explore specialized applications of VQA in domains like healthcare and discuss ongoing challenges, such as dataset bias, model interpretability, and the need for common-sense reasoning. Lastly, we discuss the emerging trends in large multimodal language models and the integration of external knowledge, offering insights into the future directions of VQA. This paper aims to provide a comprehensive overview of the evolution of VQA, highlighting both its current state and potential advancements.

[Arxiv](https://arxiv.org/abs/2501.07109)