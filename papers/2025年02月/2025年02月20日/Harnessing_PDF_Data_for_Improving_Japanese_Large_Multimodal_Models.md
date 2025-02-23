# <翻译失败>

发布时间：2025年02月20日

`LLM应用` `文档处理`

> Harnessing PDF Data for Improving Japanese Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在英语领域表现强劲，但受限于高质量训练数据的缺乏，其日语能力仍显不足。当前的日语LMMs通常依赖于翻译后的英语数据集，这限制了它们捕捉日本特有文化知识的能力。为解决这一问题，我们探索了日语PDF数据作为训练资源的潜力，这一领域目前仍鲜有触及。我们引入了一条全自动化的管道，利用预训练模型通过版式分析、OCR和视觉语言配对从PDF中提取图像-文本对，从而摆脱了人工标注的需要。此外，我们还从提取的图像-文本对中构建指令数据，以丰富训练数据。为了评估PDF来源数据的有效性，我们训练了日语LMMs，并在日语LMM基准测试中评估其性能。我们的结果显示了显著的性能提升，在Heron-Bench上的性能提升幅度介于3.9%到13.8%之间。进一步的分析突显了PDF来源数据对模型规模和语言模型等多方面的影响，进一步巩固了其作为日语LMMs多模态资源的价值。我们计划在论文被接收后公开源代码和数据集。

> Large Multimodal Models (LMMs) have demonstrated strong performance in English, but their effectiveness in Japanese remains limited due to the lack of high-quality training data. Current Japanese LMMs often rely on translated English datasets, restricting their ability to capture Japan-specific cultural knowledge. To address this, we explore the potential of Japanese PDF data as a training resource, an area that remains largely underutilized. We introduce a fully automated pipeline that leverages pretrained models to extract image-text pairs from PDFs through layout analysis, OCR, and vision-language pairing, removing the need for manual annotation. Additionally, we construct instruction data from extracted image-text pairs to enrich the training data. To evaluate the effectiveness of PDF-derived data, we train Japanese LMMs and assess their performance on the Japanese LMM Benchmark. Our results demonstrate substantial improvements, with performance gains ranging from 3.9% to 13.8% on Heron-Bench. Further analysis highlights the impact of PDF-derived data on various factors, such as model size and language models, reinforcing its value as a multimodal resource for Japanese LMMs. We plan to make the source code and data publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2502.14778)