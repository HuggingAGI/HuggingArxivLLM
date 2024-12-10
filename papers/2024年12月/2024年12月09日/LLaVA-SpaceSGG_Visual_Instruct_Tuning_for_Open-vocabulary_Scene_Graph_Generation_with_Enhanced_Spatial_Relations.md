# LLaVA-SpaceSGG：针对具有强化空间关系的开放词汇场景图生成的视觉指令调优

发布时间：2024年12月09日

`LLM应用` `计算机视觉` `多模态模型`

> LLaVA-SpaceSGG: Visual Instruct Tuning for Open-vocabulary Scene Graph Generation with Enhanced Spatial Relations

# 摘要

> 场景图生成（SGG）能将视觉场景转化为结构化的图表示形式，从而为复杂视觉任务提供更深入的场景理解。然而，现有的 SGG 模型往往忽视了重要的空间关系，在开放词汇环境下泛化能力欠佳。为克服这些局限，我们推出了 LLaVA-SpaceSGG，这是一款专为具有强化空间关系建模的开放词汇 SGG 打造的多模态大型语言模型（MLLM）。为对其进行训练，我们收集了 SGG 指令调优数据集，命名为 SpaceSGG。该数据集通过整合公开可用的数据集，并在我们的数据构建管道中利用开源模型合成数据构建而成。它融合了对象位置、对象关系和深度信息，形成了三种数据格式：空间 SGG 描述、问答和对话。为增强 MLLM 的固有能力向 SGG 任务的迁移，我们引入了两阶段训练范式。实验显示，LLaVA-SpaceSGG 优于其他开放词汇 SGG 方法，与基线相比，召回率提升了 8.6%，平均召回率提高了 28.4%。我们的代码库、数据集和训练模型在 GitHub 上可公开获取，网址为：https://github.com/Endlinc/LLaVA-SpaceSGG。

> Scene Graph Generation (SGG) converts visual scenes into structured graph representations, providing deeper scene understanding for complex vision tasks. However, existing SGG models often overlook essential spatial relationships and struggle with generalization in open-vocabulary contexts. To address these limitations, we propose LLaVA-SpaceSGG, a multimodal large language model (MLLM) designed for open-vocabulary SGG with enhanced spatial relation modeling. To train it, we collect the SGG instruction-tuning dataset, named SpaceSGG. This dataset is constructed by combining publicly available datasets and synthesizing data using open-source models within our data construction pipeline. It combines object locations, object relations, and depth information, resulting in three data formats: spatial SGG description, question-answering, and conversation. To enhance the transfer of MLLMs' inherent capabilities to the SGG task, we introduce a two-stage training paradigm. Experiments show that LLaVA-SpaceSGG outperforms other open-vocabulary SGG methods, boosting recall by 8.6% and mean recall by 28.4% compared to the baseline. Our codebase, dataset, and trained models are publicly accessible on GitHub at the following URL: https://github.com/Endlinc/LLaVA-SpaceSGG.

[Arxiv](https://arxiv.org/abs/2412.06322)