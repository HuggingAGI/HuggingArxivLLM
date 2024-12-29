# 一个经由混合指令生成的高质量、富含文本的图像指令调优数据集

发布时间：2024年12月20日

`LLM应用` `多模态` `图像处理`

> A High-Quality Text-Rich Image Instruction Tuning Dataset via Hybrid Instruction Generation

# 摘要

> 大型多模态模型因训练数据匮乏，在处理富含文本的图像时仍面临困境。Self-Instruct 虽提供了一种无需标注即可生成指令数据的途径，但其质量欠佳，毕竟多模态对齐对最大的模型而言仍是难题。在本研究中，我们提出了 LLaVAR-2，借助人类标注者与大型语言模型之间的混合指令生成，来强化富含文本图像的多模态对齐。具体而言，先是由人类标注者给出详细的图像描述，再将这些标注用于为 GPT-4o 定制的文本提示中以整理数据集。同时，还采用了多种机制来剔除低质量数据，最终得到的数据集包含 424k 对高质量指令。实证结果显示，在该数据集上微调的模型相较于使用 Self-Instruct 数据训练的模型有显著的改进。

> Large multimodal models still struggle with text-rich images because of inadequate training data. Self-Instruct provides an annotation-free way for generating instruction data, but its quality is poor, as multimodal alignment remains a hurdle even for the largest models. In this work, we propose LLaVAR-2, to enhance multimodal alignment for text-rich images through hybrid instruction generation between human annotators and large language models. Specifically, it involves detailed image captions from human annotators, followed by the use of these annotations in tailored text prompts for GPT-4o to curate a dataset. It also implements several mechanisms to filter out low-quality data, and the resulting dataset comprises 424k high-quality pairs of instructions. Empirical results show that models fine-tuned on this dataset exhibit impressive enhancements over those trained with self-instruct data.

[Arxiv](https://arxiv.org/abs/2412.16364)