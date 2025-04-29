# # 借助多模态视觉-时间转换模型与生成式AI，提升手术文档质量
借助多模态视觉-时间转换模型与生成式AI，提升手术文档质量

发布时间：2025年04月28日

`LLM应用` `医疗影像`

> Enhancing Surgical Documentation through Multimodal Visual-Temporal Transformers and Generative AI

# 摘要

> # 摘要  
手术视频自动摘要在提升手术记录质量、支持手术培训以及辅助术后分析方面具有重要意义。本文提出了一种融合人工智能与医学的创新方法，致力于开发在手术场景中具有直接应用价值的机器学习模型。我们设计了一种多模态框架，结合计算机视觉和大型语言模型的最新进展，实现手术视频的全面摘要生成。  

该方法分为三个核心阶段：首先，通过视觉变压器在帧级别提取视觉特征，完成手术工具、组织、器官及手术动作的检测；其次，利用大型语言模型将视觉特征转化为帧级别描述，并结合基于ViViT的编码器捕获的时间特征，生成片段级别的上下文摘要；最后，通过专门针对摘要任务优化的大型语言模型，将片段描述整合为完整的手术报告。  

我们在CholecT50数据集上进行实验，基于50个腹腔镜视频的器械和动作标注进行评估。结果表明，本方法在工具检测方面达到了96%的精度，时间背景摘要的BERT得分为0.74。这项研究为AI辅助手术报告工具的发展奠定了基础，推动了临床文档记录的智能化与可靠性。

> The automatic summarization of surgical videos is essential for enhancing procedural documentation, supporting surgical training, and facilitating post-operative analysis. This paper presents a novel method at the intersection of artificial intelligence and medicine, aiming to develop machine learning models with direct real-world applications in surgical contexts. We propose a multi-modal framework that leverages recent advancements in computer vision and large language models to generate comprehensive video summaries. %
The approach is structured in three key stages. First, surgical videos are divided into clips, and visual features are extracted at the frame level using visual transformers. This step focuses on detecting tools, tissues, organs, and surgical actions. Second, the extracted features are transformed into frame-level captions via large language models. These are then combined with temporal features, captured using a ViViT-based encoder, to produce clip-level summaries that reflect the broader context of each video segment. Finally, the clip-level descriptions are aggregated into a full surgical report using a dedicated LLM tailored for the summarization task. %
We evaluate our method on the CholecT50 dataset, using instrument and action annotations from 50 laparoscopic videos. The results show strong performance, achieving 96\% precision in tool detection and a BERT score of 0.74 for temporal context summarization. This work contributes to the advancement of AI-assisted tools for surgical reporting, offering a step toward more intelligent and reliable clinical documentation.

[Arxiv](https://arxiv.org/abs/2504.19918)