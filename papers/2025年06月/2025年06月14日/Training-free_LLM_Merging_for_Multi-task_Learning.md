# 无需训练的多任务学习LLM合并方法

发布时间：2025年06月14日

`LLM理论`

> Training-free LLM Merging for Multi-task Learning

# 摘要

> 大型语言模型（LLMs）在各类自然语言处理（NLP）任务中表现优异。开源模型如LLaMA和Qwen的推出，催生了大量针对特定任务和语言的微调模型。本文提出一个关键问题：能否将这些专业模型整合，打造一个具备多任务能力的统一模型？为此，我们推出了无需训练的分层迭代合并（Hi-Merging）方法，可将多种专业LLMs无缝整合为单一模型。通过基于贡献分析的模型级和层级剪枝与缩放技术，Hi-Merging有效缓解了参数冲突问题。在中英文多选题和问答任务上的大量实验表明，Hi-Merging在多任务学习中表现出色。实验结果证明，Hi-Merging不仅超越现有合并技术，在大多数情况下还优于基于合并数据集微调的模型性能。项目代码已开源：https://github.com/Applied-Machine-Learning-Lab/Hi-Merging。

> Large Language Models (LLMs) have demonstrated exceptional capabilities across diverse natural language processing (NLP) tasks. The release of open-source LLMs like LLaMA and Qwen has triggered the development of numerous fine-tuned models tailored for various tasks and languages. In this paper, we explore an important question: is it possible to combine these specialized models to create a unified model with multi-task capabilities. We introduces Hierarchical Iterative Merging (Hi-Merging), a training-free method for unifying different specialized LLMs into a single model. Specifically, Hi-Merging employs model-wise and layer-wise pruning and scaling, guided by contribution analysis, to mitigate parameter conflicts. Extensive experiments on multiple-choice and question-answering tasks in both Chinese and English validate Hi-Merging's ability for multi-task learning. The results demonstrate that Hi-Merging consistently outperforms existing merging techniques and surpasses the performance of models fine-tuned on combined datasets in most scenarios. Code is available at: https://github.com/Applied-Machine-Learning-Lab/Hi-Merging.

[Arxiv](https://arxiv.org/abs/2506.12379)