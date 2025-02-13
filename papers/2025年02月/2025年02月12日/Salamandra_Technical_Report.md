# Salamandra技术报告

发布时间：2025年02月12日

`LLM应用

摘要中提到Salamandra是一个开源的解码器模型套件，专注于多语言和多模态应用，展示了其在聊天场景和多模态领域的应用潜力，因此属于LLM应用。` `多模态`

> Salamandra Technical Report

# 摘要

> 我们很高兴推出Salamandra——一款开源解码器模型套件，提供20亿、70亿和400亿参数三种版本。这些模型基于包含35种欧洲语言文本和代码的高质量多语言数据从零训练而成，所有数据均来自开放获取资源。除了基础模型，我们还发布了经过公开指令数据微调的检查点，特别适用于聊天场景。此外，我们展示了Salamandra在多模态领域的初步探索，这些概念验证实验彰显了其广阔的应用前景。在多语言基准测试中，Salamandra表现卓越，与同规模开源模型相比毫不逊色。我们不仅提供了标准下游任务的全面评估结果，还深入分析了偏见与安全等关键指标。通过这份技术报告，我们希望推动开放科学，透明地分享设计思路、数据整理策略和评估方法。与众不同的是，我们开源了所有训练和评估脚本，进一步降低研究门槛。所有模型均采用Apache 2.0许可证发布，旨在助力未来研究，支持商业应用，为开源大模型生态贡献力量。

> This work introduces Salamandra, a suite of open-source decoder-only large language models available in three different sizes: 2, 7, and 40 billion parameters. The models were trained from scratch on highly multilingual data that comprises text in 35 European languages and code. Our carefully curated corpus is made exclusively from open-access data compiled from a wide variety of sources. Along with the base models, supplementary checkpoints that were fine-tuned on public-domain instruction data are also released for chat applications. Additionally, we also share our preliminary experiments on multimodality, which serve as proof-of-concept to showcase potential applications for the Salamandra family. Our extensive evaluations on multilingual benchmarks reveal that Salamandra has strong capabilities, achieving competitive performance when compared to similarly sized open-source models. We provide comprehensive evaluation results both on standard downstream tasks as well as key aspects related to bias and safety.With this technical report, we intend to promote open science by sharing all the details behind our design choices, data curation strategy and evaluation methodology. In addition to that, we deviate from the usual practice by making our training and evaluation scripts publicly accessible. We release all models under a permissive Apache 2.0 license in order to foster future research and facilitate commercial use, thereby contributing to the open-source ecosystem of large language models.

[Arxiv](https://arxiv.org/abs/2502.08489)