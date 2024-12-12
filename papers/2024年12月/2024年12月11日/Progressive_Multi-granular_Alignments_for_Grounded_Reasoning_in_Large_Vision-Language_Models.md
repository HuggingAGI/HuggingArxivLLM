# 大型视觉语言模型中用于基础推理的渐进式多粒度对齐

发布时间：2024年12月11日

`LLM应用` `视觉语言` `推理任务`

> Progressive Multi-granular Alignments for Grounded Reasoning in Large Vision-Language Models

# 摘要

> 现有的大型视觉语言模型（LVLMs）虽能出色匹配多模态输入中的概念，却在组合概念及实体间的高级关系处理上力不从心。本文引入了渐进式多粒度视觉语言对齐（PromViL）这一新颖框架，以提升LVLMs执行基于基础的组合视觉推理任务的能力。我们的方法构建了从简单到复杂概念的多模态对齐层次结构。通过逐步将文本描述与相应视觉区域对齐，我们的模型学会借助低层次的上下文信息为高层次推理提供依据。为推动这一学习进程，我们引入了一种数据生成流程，它从Visual Genome创建了新的数据集，提供了众多嵌套组合的视觉语言对。实验结果显示，我们的PromViL框架在各类视觉基础和组合问答任务上显著优于基线。

> Existing Large Vision-Language Models (LVLMs) excel at matching concepts across multi-modal inputs but struggle with compositional concepts and high-level relationships between entities. This paper introduces Progressive multi-granular Vision-Language alignments (PromViL), a novel framework to enhance LVLMs' ability in performing grounded compositional visual reasoning tasks. Our approach constructs a hierarchical structure of multi-modal alignments, ranging from simple to complex concepts. By progressively aligning textual descriptions with corresponding visual regions, our model learns to leverage contextual information from lower levels to inform higher-level reasoning. To facilitate this learning process, we introduce a data generation process that creates a novel dataset derived from Visual Genome, providing a wide range of nested compositional vision-language pairs. Experimental results demonstrate that our PromViL framework significantly outperforms baselines on various visual grounding and compositional question answering tasks.

[Arxiv](https://arxiv.org/abs/2412.08125)