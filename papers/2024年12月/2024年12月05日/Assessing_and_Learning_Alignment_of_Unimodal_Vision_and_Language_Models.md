# 评估并学习单模态视觉与语言模型的对齐情况

发布时间：2024年12月05日

`LLM应用` `计算机视觉` `迁移学习`

> Assessing and Learning Alignment of Unimodal Vision and Language Models

# 摘要

> 
单模态视觉和语言模型的一致性究竟如何？虽然此前已有工作尝试回答此问题，但其评估方法无法直接应用于这些模型在实际视觉语言任务中的运用。本文中，我们受线性探测启发，提出一种直接的评估方法来衡量视觉语言的一致性。我们发现，自监督学习（SSL）视觉模型的一致性程度取决于其 SSL 训练目标，并且 SSL 表示的聚类质量对一致性表现的影响大于线性可分离性。接着，我们引入了图像和语言的快速对齐（SAIL），这是一个高效的迁移学习框架，用于将预训练的单模态视觉和语言模型对齐，以服务于下游的视觉语言任务。由于 SAIL 借助了预训练单模态模型的优势，与从零开始训练的 CLIP 等模型相比，它在多模态对齐中所需的配对图像 - 文本数据大幅减少（仅 6%）。SAIL 训练仅需一个 A100 GPU，5 小时的训练时长，且能支持高达 32,768 的批量大小。SAIL 在 ImageNet 上达到 73.4%的零样本准确率（CLIP 为 72.7%），在零样本检索、复杂推理和语义分割方面表现卓越。此外，SAIL 提升了视觉编码器的语言兼容性，进而增强了多模态大型语言模型的性能。整个代码库和模型权重均开源：https://lezhang7.github.io/sail.github.io/


> How well are unimodal vision and language models aligned? Although prior work have approached answering this question, their assessment methods do not directly translate to how these models are used in practical vision-language tasks. In this paper, we propose a direct assessment method, inspired by linear probing, to assess vision-language alignment. We identify that the degree of alignment of the SSL vision models depends on their SSL training objective, and we find that the clustering quality of SSL representations has a stronger impact on alignment performance than their linear separability. Next, we introduce Swift Alignment of Image and Language (SAIL), a efficient transfer learning framework that aligns pretrained unimodal vision and language models for downstream vision-language tasks. Since SAIL leverages the strengths of pretrained unimodal models, it requires significantly fewer (6%) paired image-text data for the multimodal alignment compared to models like CLIP which are trained from scratch. SAIL training only requires a single A100 GPU, 5 hours of training and can accommodate a batch size up to 32,768. SAIL achieves 73.4% zero-shot accuracy on ImageNet (vs. CLIP's 72.7%) and excels in zero-shot retrieval, complex reasoning, and semantic segmentation. Additionally, SAIL improves the language-compatibility of vision encoders that in turn enhance the performance of multimodal large language models. The entire codebase and model weights are open-source: https://lezhang7.github.io/sail.github.io/

[Arxiv](https://arxiv.org/abs/2412.04616)