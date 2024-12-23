# J-EDI QA：深海生物特定多模态 LLM 的基准

发布时间：2024年12月20日

`LLM应用` `海洋科学` `图像识别`

> J-EDI QA: Benchmark for deep-sea organism-specific multimodal LLM

# 摘要

> 日本海洋地球科学技术厅（JAMSTEC）推出了 JAMSTEC 地球深海图像（J-EDI），这是一个深海视频和图像档案库（https://www.godac.jamstec.go.jp/jedi/e/index.html），为关注深海图像的研究人员和学者提供了珍贵资源。此数据集涵盖了深海现象的图像和视频，主要是海洋生物，也包括海底及物理过程。在本研究中，我们提出了 J-EDI QA，这是一个运用多模态大型语言模型（LLM）来理解深海生物图像的基准。该基准包含 100 张图像，每张图像都配有 JAMSTEC 研究人员给出的问题及四个选项的答案。问答对以日语呈现，该基准用于评估用日语理解深海物种的能力。在本文所做的评估中，OpenAI o1 的正确回答率为 50％。这一结果表明，即便以 2024 年 12 月最先进的模型能力，对深海物种的理解仍未达到专家水平。所以，在针对深海物种的特定 LLM 方面还需更进一步。

> Japan Agency for Marine-Earth Science and Technology (JAMSTEC) has made available the JAMSTEC Earth Deep-sea Image (J-EDI), a deep-sea video and image archive (https://www.godac.jamstec.go.jp/jedi/e/index.html). This archive serves as a valuable resource for researchers and scholars interested in deep-sea imagery. The dataset comprises images and videos of deep-sea phenomena, predominantly of marine organisms, but also of the seafloor and physical processes. In this study, we propose J-EDI QA, a benchmark for understanding images of deep-sea organisms using a multimodal large language model (LLM). The benchmark is comprised of 100 images, accompanied by questions and answers with four options by JAMSTEC researchers for each image. The QA pairs are provided in Japanese, and the benchmark assesses the ability to understand deep-sea species in Japanese. In the evaluation presented in this paper, OpenAI o1 achieved a 50% correct response rate. This result indicates that even with the capabilities of state-of-the-art models as of December 2024, deep-sea species comprehension is not yet at an expert level. Further advances in deep-sea species-specific LLMs are therefore required.

[Arxiv](https://arxiv.org/abs/2412.15574)