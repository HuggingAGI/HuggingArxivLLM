# MoColl: 基于智能体的特定与通用模型协作实现图像描述

发布时间：2025年01月03日

`Agent

理由：这篇论文提出了一种代理增强模型协作框架（MoColl），通过将复杂图像描述任务分解为一系列相互关联的问答子任务，利用可训练的视觉问答（VQA）模型和具备通用知识的LLM代理来协同完成任务。LLM代理不仅生成问题并将问答对合成为连贯的描述，还指导VQA模型的训练。这种框架的核心在于代理的使用和协作，因此归类为Agent。` `计算机视觉`

> MoColl: Agent-Based Specific and General Model Collaboration for Image Captioning

# 摘要

> # 摘要
图像描述是计算机视觉与自然语言处理交叉领域的关键任务，应用广泛。对于诊断报告生成等复杂任务，深度学习模型不仅需要领域特定的图像-描述数据集，还需结合通用知识以确保上下文准确性。现有方法存在明显局限：专用模型虽能捕捉领域细节，但泛化能力不足；而基于大型语言模型（LLMs）的视觉语言模型（VLMs）虽能利用通用知识，却在领域适应上表现欠佳。为此，本文提出了一种新颖的代理增强模型协作框架——	extbf{MoColl}，旨在有效整合领域特定知识与通用知识。具体而言，我们将复杂图像描述任务分解为一系列相互关联的问答子任务。通过可训练的视觉问答（VQA）模型进行领域特定的视觉分析，回答基于图像内容的任务特定问题；同时，具备通用知识的LLM代理负责生成问题，并将问答对合成为连贯的描述。此外，该代理还指导VQA模型的训练，进一步提升其领域特定能力。放射学报告生成的实验结果验证了该框架的有效性，显著提升了生成报告的质量。

> Image captioning is a critical task at the intersection of computer vision and natural language processing, with wide-ranging applications across various domains. For complex tasks such as diagnostic report generation, deep learning models require not only domain-specific image-caption datasets but also the incorporation of relevant general knowledge to provide contextual accuracy. Existing approaches exhibit inherent limitations: specialized models excel in capturing domain-specific details but lack generalization, while vision-language models (VLMs) built on large language models (LLMs) leverage general knowledge but struggle with domain-specific adaptation. To address these limitations, this paper proposes a novel agent-enhanced model collaboration framework, which we called \textbf{MoColl}, designed to effectively integrate domain-specific and general knowledge. Specifically, our approach is to decompose complex image captioning tasks into a series of interconnected question-answer subtasks. A trainable visual question answering (VQA) model is employed as a specialized tool to focus on domain-specific visual analysis, answering task-specific questions based on image content. Concurrently, an LLM-based agent with general knowledge formulates these questions and synthesizes the resulting question-answer pairs into coherent captions. Beyond its role in leveraging the VQA model, the agent further guides its training to enhance its domain-specific capabilities. Experimental results on radiology report generation validate the effectiveness of the proposed framework, demonstrating significant improvements in the quality of generated reports.

[Arxiv](https://arxiv.org/abs/2501.01834)