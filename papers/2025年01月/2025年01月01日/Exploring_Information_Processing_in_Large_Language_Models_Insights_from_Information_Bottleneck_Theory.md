# 探索大型语言模型中的信息处理：信息瓶颈理论的启示

发布时间：2025年01月01日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的内部信息处理机制，特别是从信息瓶颈理论的角度分析了LLMs如何理解输入并做出预测。论文提出了新的理论框架和方法（如IC-ICL和TS-FT），并验证了这些方法在任务空间构建和模型性能提升方面的有效性。这些内容属于对LLMs的理论研究和机制探索，因此归类为LLM理论。` `机器学习`

> Exploring Information Processing in Large Language Models: Insights from Information Bottleneck Theory

# 摘要

> 大型语言模型（LLMs）通过理解输入信息并预测输出，在各种任务中表现出色。然而，LLMs如何理解输入并做出有效预测的内部机制仍不明确。本文从信息瓶颈理论的角度探讨了LLMs的信息处理机制，提出了一种非训练构建策略来定义任务空间，并得出以下关键发现：（1）LLMs将输入信息压缩到特定任务空间（如情感空间、主题空间）以促进任务理解；（2）它们在关键时刻从任务空间中提取并利用相关信息以生成准确预测。基于这些发现，我们提出了两种新方法：基于信息压缩的上下文学习（IC-ICL）和任务空间引导的微调（TS-FT）。IC-ICL通过将检索到的示例信息压缩到任务空间中来提升推理性能和效率。TS-FT则通过空间引导的损失微调LLMs，鼓励学习更有效的压缩和选择机制。多个数据集的实验验证了任务空间构建的有效性。此外，IC-ICL不仅提升了性能，还将推理速度提高了40%以上，而TS-FT通过最小策略调整实现了卓越效果。

> Large Language Models (LLMs) have demonstrated remarkable performance across a wide range of tasks by understanding input information and predicting corresponding outputs. However, the internal mechanisms by which LLMs comprehend input and make effective predictions remain poorly understood. In this paper, we explore the working mechanism of LLMs in information processing from the perspective of Information Bottleneck Theory. We propose a non-training construction strategy to define a task space and identify the following key findings: (1) LLMs compress input information into specific task spaces (e.g., sentiment space, topic space) to facilitate task understanding; (2) they then extract and utilize relevant information from the task space at critical moments to generate accurate predictions. Based on these insights, we introduce two novel approaches: an Information Compression-based Context Learning (IC-ICL) and a Task-Space-guided Fine-Tuning (TS-FT). IC-ICL enhances reasoning performance and inference efficiency by compressing retrieved example information into the task space. TS-FT employs a space-guided loss to fine-tune LLMs, encouraging the learning of more effective compression and selection mechanisms. Experiments across multiple datasets validate the effectiveness of task space construction. Additionally, IC-ICL not only improves performance but also accelerates inference speed by over 40\%, while TS-FT achieves superior results with a minimal strategy adjustment.

[Arxiv](https://arxiv.org/abs/2501.00999)