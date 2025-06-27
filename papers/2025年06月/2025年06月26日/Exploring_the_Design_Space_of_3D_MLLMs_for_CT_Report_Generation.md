# 探索 3D 多语言大语言模型在 CT 报告生成中的设计领域

发布时间：2025年06月26日

`LLM应用` `医学影像` `医学影像处理`

> Exploring the Design Space of 3D MLLMs for CT Report Generation

# 摘要

> 多模态大语言模型（MLLMs）引领了放射报告生成（RRG）的自动化革命。本研究系统性地探索了3D MLLMs的设计空间，涵盖视觉输入表示、投影器、大型语言模型（LLMs）及3D CT报告生成的微调技术。我们创新性地提出了两种基于知识的报告增强方法，使GREEN得分取得显著提升（高达10%），在MICCAI 2024 AMOS-MM挑战中斩获亚军。基于AMOS-MM数据集的1,687例研究结果表明，RRG与LLM的规模几乎无关，即使采用相同的训练协议。研究还揭示，若原始的ViT是在较小的体积大小上进行预训练的，更大的体积大小并不一定能带来性能提升。此外，结合分割掩膜与CT体积可显著改善模型性能。我们的代码已公开发布，欢迎访问https://github.com/bowang-lab/AMOS-MM-Solution获取。

> Multimodal Large Language Models (MLLMs) have emerged as a promising way to automate Radiology Report Generation (RRG). In this work, we systematically investigate the design space of 3D MLLMs, including visual input representation, projectors, Large Language Models (LLMs), and fine-tuning techniques for 3D CT report generation. We also introduce two knowledge-based report augmentation methods that improve performance on the GREEN score by up to 10\%, achieving the 2nd place on the MICCAI 2024 AMOS-MM challenge. Our results on the 1,687 cases from the AMOS-MM dataset show that RRG is largely independent of the size of LLM under the same training protocol. We also show that larger volume size does not always improve performance if the original ViT was pre-trained on a smaller volume size. Lastly, we show that using a segmentation mask along with the CT volume improves performance. The code is publicly available at https://github.com/bowang-lab/AMOS-MM-Solution

[Arxiv](https://arxiv.org/abs/2506.21535)