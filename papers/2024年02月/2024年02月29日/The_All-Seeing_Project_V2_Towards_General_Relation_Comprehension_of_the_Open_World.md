# 《全知计划V2》：旨在攻克开放世界的通用关系理解难题，探索更全面的关系认知能力。

发布时间：2024年02月29日

`Agent`

> The All-Seeing Project V2: Towards General Relation Comprehension of the Open World

# 摘要

> 现在呈献给大家的是全新升级的 All-Seeing Project V2，该项目研发出一款专用于理解图像中物体间关系的模型及配套数据集。我们创新性地提出了All-Seeing Model V2 (ASMv2)，巧妙地将文本生成、物体定位和关系理解融入一个名为“关系对话”(ReC)的任务中。得益于这一集成化任务，ASMv2 不仅能敏锐捕捉到图片中所有物体并精准识别，更能深入解析这些物体间的错综复杂关系网络，有效缓解了当前多模态大型语言模型(MMLMs)常面临的“关系臆断”难题。为了促进MMLMs在关系理解领域的训练与评测，我们精心打造了首个高标准的ReC数据集 AS-V2，其格式严格遵循标准指令调优数据的要求。此外，我们还创新设计了一项名为“循环关系探测评估”(CRPE)的新基准测试，以便全面检验MMLMs在关系理解上的实力。尤为突出的是，ASMv2在这一关系认知基准上取得了高达52.04的整体准确率，远超LLaVA-1.5的43.14，展现了显著的优势。我们期待本项目的研究成果能激发更多后续探索，并有力推动通向人工智能普遍智能的步伐。您可访问https://github.com/OpenGVLab/all-seeing获取我们的项目资源。

> We present the All-Seeing Project V2: a new model and dataset designed for understanding object relations in images. Specifically, we propose the All-Seeing Model V2 (ASMv2) that integrates the formulation of text generation, object localization, and relation comprehension into a relation conversation (ReC) task. Leveraging this unified task, our model excels not only in perceiving and recognizing all objects within the image but also in grasping the intricate relation graph between them, diminishing the relation hallucination often encountered by Multi-modal Large Language Models (MLLMs). To facilitate training and evaluation of MLLMs in relation understanding, we created the first high-quality ReC dataset ({AS-V2) which is aligned with the format of standard instruction tuning data. In addition, we design a new benchmark, termed Circular-based Relation Probing Evaluation (CRPE) for comprehensively evaluating the relation comprehension capabilities of MLLMs. Notably, our ASMv2 achieves an overall accuracy of 52.04 on this relation-aware benchmark, surpassing the 43.14 of LLaVA-1.5 by a large margin. We hope that our work can inspire more future research and contribute to the evolution towards artificial general intelligence. Our project is released at https://github.com/OpenGVLab/all-seeing.

[Arxiv](https://arxiv.org/abs/2402.19474)