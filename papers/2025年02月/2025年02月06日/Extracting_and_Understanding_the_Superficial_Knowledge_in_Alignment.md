# 提取与理解对齐中的浅层知识

# 摘要
大型语言模型（LLMs）通过对其所训练的大量文本数据的捕捉和表示，展现出了卓越的知识获取能力。然而，LLMs所捕捉到的知识往往局限于文本中存在的表面信息，我们称之为'浅层知识'。本文旨在研究LLMs如何获取和处理这种浅层知识，以及这对模型对齐和下游应用的影响。我们提出了一种系统化的框架，用于从LLMs中提取和分析浅层知识，揭示其知识获取背后的机制。我们的实验表明，理解浅层知识可以显著提升模型输出与用户意图之间的对齐，同时保持高质量的文本生成能力。

发布时间：2025年02月06日

`LLM理论` `AI伦理` `机器学习`

> Extracting and Understanding the Superficial Knowledge in Alignment

# 摘要

> 大型语言模型（LLMs）与人类价值观和偏好的对齐，通常通过基于人类反馈的微调来实现，这对于确保AI行为的安全性和责任性至关重要。然而，这一过程通常需要大量数据和计算资源。近期研究发现，通过更简单的方法，如上下文学习，对齐或许可以在更低的成本下实现。这引出了一个问题：对齐主要是表面的吗？在这篇论文中，我们深入探讨了这一问题，并进行了定量分析。我们定义了表面知识的概念，认为它是可以通过简单的token重写获得的知识，而不会影响模型捕捉token之间潜在因果关系的能力。我们提出了一种从对齐模型中提取和分离表面知识的方法，重点关注最终token选择过程的浅层修改。通过比较仅增强表面知识的模型与完全对齐的模型，我们量化了对齐中的表面部分。我们的研究发现，尽管表面知识在对齐中占据了重要比重，尤其是在安全和去毒化任务中，但这并非全部。需要推理和上下文理解的任务仍依赖于更深层次的知识。此外，我们展示了分离的表面知识的两个实际优势：（1）它可以跨模型转移，利用小型模型提取的表面知识实现大型模型的高效远程对齐；（2）它是可恢复的，允许在不牺牲性能的情况下修复受损模型的对齐状态。

> Alignment of large language models (LLMs) with human values and preferences, often achieved through fine-tuning based on human feedback, is essential for ensuring safe and responsible AI behaviors. However, the process typically requires substantial data and computation resources. Recent studies have revealed that alignment might be attainable at lower costs through simpler methods, such as in-context learning. This leads to the question: Is alignment predominantly superficial? In this paper, we delve into this question and provide a quantitative analysis. We formalize the concept of superficial knowledge, defining it as knowledge that can be acquired through easily token restyling, without affecting the model's ability to capture underlying causal relationships between tokens. We propose a method to extract and isolate superficial knowledge from aligned models, focusing on the shallow modifications to the final token selection process. By comparing models augmented only with superficial knowledge to fully aligned models, we quantify the superficial portion of alignment. Our findings reveal that while superficial knowledge constitutes a significant portion of alignment, particularly in safety and detoxification tasks, it is not the whole story. Tasks requiring reasoning and contextual understanding still rely on deeper knowledge. Additionally, we demonstrate two practical advantages of isolated superficial knowledge: (1) it can be transferred between models, enabling efficient offsite alignment of larger models using extracted superficial knowledge from smaller models, and (2) it is recoverable, allowing for the restoration of alignment in compromised models without sacrificing performance.

[Arxiv](https://arxiv.org/abs/2502.04602)