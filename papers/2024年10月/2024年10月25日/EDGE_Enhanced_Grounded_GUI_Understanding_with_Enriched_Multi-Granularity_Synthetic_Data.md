# EDGE：借助丰富的多粒度合成数据提升有依据的图形用户界面理解能力

发布时间：2024年10月25日

`Agent` `图形用户界面` `自主代理`

> EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data

# 摘要

> 在各类应用程序的图形用户界面（GUIs）上运行的自主代理具备极大的实用价值。和依赖结构化文本及定制后端的基于大型语言模型（LLM）的方法不同，运用大型视觉语言模型（LVLMs）的方法更为直观且适应性更强，因其能够直观感知并直接与屏幕互动，所以在没有文本元数据和定制后端的一般场景中，它们不可或缺。鉴于现有工作中针对GUI相关任务缺乏高质量训练数据，本文旨在通过数据驱动的方式提升LVLMs的GUI理解与交互能力。我们提出EDGE，这是一个通用的数据合成框架，能够从网络上的网页自动生成大规模、多粒度的训练数据。在各类GUI和代理基准上的评估结果显示，使用EDGE生成的数据集训练的模型展现出卓越的网页理解能力，并且能够轻松迁移到此前未曾见过的桌面和移动环境中。我们的方法显著降低了对人工标注的依赖，让研究人员能够借助网络上丰富的公共资源推进工作。我们的源代码、数据集和模型可在https://anonymous.4open.science/r/EDGE-1CDB获取。

> Autonomous agents operating on the graphical user interfaces (GUIs) of various applications hold immense practical value. Unlike the large language model (LLM)-based methods which rely on structured texts and customized backends, the approaches using large vision-language models (LVLMs) are more intuitive and adaptable as they can visually perceive and directly interact with screens, making them indispensable in general scenarios without text metadata and tailored backends. Given the lack of high-quality training data for GUI-related tasks in existing work, this paper aims to enhance the GUI understanding and interacting capabilities of LVLMs through a data-driven approach. We propose EDGE, a general data synthesis framework that automatically generates large-scale, multi-granularity training data from webpages across the Web. Evaluation results on various GUI and agent benchmarks demonstrate that the model trained with the dataset generated through EDGE exhibits superior webpage understanding capabilities, which can then be easily transferred to previously unseen desktop and mobile environments. Our approach significantly reduces the dependence on manual annotations, empowering researchers to harness the vast public resources available on the Web to advance their work. Our source code, the dataset and the model are available at https://anonymous.4open.science/r/EDGE-1CDB.

[Arxiv](https://arxiv.org/abs/2410.19461)