# 基于多张图像的移动操作指令生成与自动指标优化

发布时间：2025年01月28日

`LLM应用

**理由**：该论文主要研究如何利用图像生成自由形式的移动操作指令，并引入了一种创新的训练方法，结合了基于学习和n-gram的自动评估指标分数作为奖励。这种方法旨在提升多模态语言理解模型在移动操作任务中的表现。虽然论文中提到了多模态大型语言模型（LLM），但其核心应用场景是生成指令和提升模型在特定任务（移动操作）中的表现，因此归类为LLM应用更为合适。` `机器人`

> Mobile Manipulation Instruction Generation from Multiple Images with Automatic Metric Enhancement

# 摘要

> 我们研究如何基于目标物体和容器的图像生成自由形式的移动操作指令。传统图像描述模型因针对单图像优化而难以胜任。为此，我们提出了一种新模型，能够同时处理目标物体和容器，生成适用于移动操作任务的自由形式指令。我们还引入了一种创新的训练方法，将基于学习和n-gram的自动评估指标分数作为奖励，使模型能够学习单词间的共现关系和恰当的释义。实验结果显示，该方法在标准自动评估指标上超越了包括多模态大型语言模型在内的基线方法。此外，物理实验表明，使用该方法增强语言指令数据能显著提升现有多模态语言理解模型在移动操作中的表现。

> We consider the problem of generating free-form mobile manipulation instructions based on a target object image and receptacle image. Conventional image captioning models are not able to generate appropriate instructions because their architectures are typically optimized for single-image. In this study, we propose a model that handles both the target object and receptacle to generate free-form instruction sentences for mobile manipulation tasks. Moreover, we introduce a novel training method that effectively incorporates the scores from both learning-based and n-gram based automatic evaluation metrics as rewards. This method enables the model to learn the co-occurrence relationships between words and appropriate paraphrases. Results demonstrate that our proposed method outperforms baseline methods including representative multimodal large language models on standard automatic evaluation metrics. Moreover, physical experiments reveal that using our method to augment data on language instructions improves the performance of an existing multimodal language understanding model for mobile manipulation.

[Arxiv](https://arxiv.org/abs/2501.17022)