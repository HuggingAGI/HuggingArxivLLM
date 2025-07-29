# 相信模型：轻量级视觉语言模型在上下文中的评估能力，用于图像文本数据质量

发布时间：2025年07月27日

`LLM应用` `计算机视觉` `数据处理`

> Trust the Model: Compact VLMs as In-Context Judges for Image-Text Data Quality

# 摘要

> 视觉语言模型 (VLMs) 将视觉数据整合到传统大型语言模型中，实现了更丰富的多模态推理，极大地扩展了AI的实际应用场景。然而，视觉输入的引入也带来了数据质量维护的新挑战。实证研究表明，精心策划且具有代表性的训练样本往往比单纯增加数据量更有效。基于这一观察，我们提出了一种精简的数据过滤框架，使用在高质量图像-文本描述标注数据集上微调的小型VLM。该模型能够根据描述质量和图像-文本对齐度有效评估和筛选潜在训练样本。与以往在现有大规模VLM上添加辅助过滤模块的方法不同，我们仅利用专门设计的小型VLM的内置评估能力。这种方法无需额外模块，降低了训练开销。我们的轻量化模型能高效过滤不准确、嘈杂的网络数据，提升图像-文本对齐度和描述的流畅性。实验结果表明，经过我们紧凑型VLM高精度过滤的数据集，其表现可与甚至超越大规模网络爬取的嘈杂数据集。因此，我们的方法为构建高质量视觉语言训练语料库提供了一个轻量级且稳健的解决方案。\ 	extbf{可用性和实现:} 我们的紧凑型VLM过滤模型、训练数据、实用脚本和补充数据（附录）均可在https://github.com/daulettoibazar/Compact_VLM_Filter免费获取。

> Vision-language models (VLMs) extend the conventional large language models by integrating visual data, enabling richer multimodal reasoning and significantly broadens the practical applications of AI. However, including visual inputs also brings new challenges in maintaining data quality. Empirical evidence consistently shows that carefully curated and representative training examples often yield superior results compared to simply increasing the quantity of data. Inspired by this observation, we introduce a streamlined data filtration framework that employs a compact VLM, fine-tuned on a high-quality image-caption annotated dataset. This model effectively evaluates and filters potential training samples based on caption and image quality and alignment. Unlike previous approaches, which typically add auxiliary filtration modules on top of existing full-scale VLMs, our method exclusively utilizes the inherent evaluative capability of a purpose-built small VLM. This strategy eliminates the need for extra modules and reduces training overhead. Our lightweight model efficiently filters out inaccurate, noisy web data, improving image-text alignment and caption linguistic fluency. Experimental results show that datasets underwent high-precision filtration using our compact VLM perform on par with, or even surpass, larger and noisier datasets gathered through high-volume web crawling. Thus, our method provides a lightweight yet robust solution for building high-quality vision-language training corpora. \\ \textbf{Availability and implementation:} Our compact VLM filtration model, training data, utility scripts, and Supplementary data (Appendices) are freely available at https://github.com/daulettoibazar/Compact_VLM_Filter.

[Arxiv](https://arxiv.org/abs/2507.20156)