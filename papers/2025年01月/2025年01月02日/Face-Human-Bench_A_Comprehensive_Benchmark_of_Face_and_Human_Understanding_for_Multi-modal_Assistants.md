# Face-Human-Bench：多模态助手的面部与人类理解综合基准

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了多模态大语言模型（MLLMs）在人脸和人类理解方面的应用，并提出了一个新的基准测试（Face-Human-Bench）来评估这些模型的能力。论文还探讨了如何通过专家模型来补充MLLMs的能力，这些都是典型的LLM应用场景。因此，这篇论文应被分类为LLM应用。` `社交互动` `多模态助手`

> Face-Human-Bench: A Comprehensive Benchmark of Face and Human Understanding for Multi-modal Assistants

# 摘要

> # 摘要
人脸和人类是社交互动中的核心元素，广泛存在于日常照片和视频中。深入理解这些元素将显著提升多模态助手的响应质量和应用范围。然而，目前多模态助手社区对人脸和人类理解能力的评估尚不全面和科学。本文首先提出了一种包含三个层次的分层能力分类法。基于此分类法，我们从公开数据集中收集图像和注释，构建了一个半自动数据管道，为新基准生成问题。最终，我们创建了Face-Human-Bench，包含900个问题的开发集和1800个问题的测试集，支持中英文。我们使用该基准对25个主流多模态大语言模型（MLLMs）进行了评估，重点分析了能力相关性、目标位置对性能的影响以及思维链（CoT）提示的作用。此外，受多模态代理的启发，我们还探讨了MLLMs需要哪些专家模型来补充其能力。

> Faces and humans are crucial elements in social interaction and are widely included in everyday photos and videos. Therefore, a deep understanding of faces and humans will enable multi-modal assistants to achieve improved response quality and broadened application scope. Currently, the multi-modal assistant community lacks a comprehensive and scientific evaluation of face and human understanding abilities. In this paper, we first propose a hierarchical ability taxonomy that includes three levels of abilities. Then, based on this taxonomy, we collect images and annotations from publicly available datasets in the face and human community and build a semi-automatic data pipeline to produce problems for the new benchmark. Finally, the obtained Face-Human-Bench comprises a development set with 900 problems and a test set with 1800 problems, supporting both English and Chinese. We conduct evaluations over 25 mainstream multi-modal large language models (MLLMs) with our Face-Human-Bench, focusing on the correlation between abilities, the impact of the relative position of targets on performance, and the impact of Chain of Thought (CoT) prompting on performance. Moreover, inspired by multi-modal agents, we also explore which abilities of MLLMs need to be supplemented by specialist models.

[Arxiv](https://arxiv.org/abs/2501.01243)