# 更高效、更具扩展性：LLM时代下放射科对比式视觉-语言预训练的再思考

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> More performant and scalable: Rethinking contrastive vision-language pre-training of radiology in the LLM era

# 摘要

> 大型语言模型（LLMs）的兴起为革新医学对比视觉-语言预训练带来了前所未有的机遇。本文中，我们展示了LLMs如何助力大规模监督预训练，进而推动视觉-语言对齐的发展。我们首先证实，现代LLMs无需复杂的提示工程设计，就能从放射学报告中自动提取诊断标签，且精度卓越（实验中AUC>96%）；这使得以极低成本构建大规模“银标准”数据集成为现实——约3美元即可获取5万对CT影像-报告对。进一步研究发现，基于该“银标准”数据集训练的视觉编码器，性能可媲美使用专业BERT基模型提取标签训练的模型，进而推动了大规模监督预训练的普及应用。基于此，我们进一步发现，监督预训练能从根本上改善对比视觉-语言对齐效果。我们的方法仅通过3D ResNet-18和基础CLIP训练，便取得了当前最佳性能：在CT-RATE数据集上零样本诊断AUC达83.8%，RAD-ChestCT数据集上AUC为77.3%，跨模态检索性能也得到显著提升（影像-影像检索MAP@50=53.7%，报告-影像检索Recall@100=52.2%）。这些结果表明，利用LLMs有望推动构建{f 更高效、更具扩展性}的医学AI系统。相关代码已开源至https://github.com/SadVoxel/More-performant-and-scalable。

> The emergence of Large Language Models (LLMs) presents unprecedented opportunities to revolutionize medical contrastive vision-language pre-training. In this paper, we show how LLMs can facilitate large-scale supervised pre-training, thereby advancing vision-language alignment. We begin by demonstrate that modern LLMs can automatically extract diagnostic labels from radiology reports with remarkable precision (>96\% AUC in our experiments) without complex prompt engineering, enabling the creation of large-scale "silver-standard" datasets at a minimal cost (~\$3 for 50k CT image-report pairs). Further, we find that vision encoder trained on this "silver-standard" dataset achieves performance comparable to those trained on labels extracted by specialized BERT-based models, thereby democratizing the access to large-scale supervised pre-training. Building on this foundation, we proceed to reveal that supervised pre-training fundamentally improves contrastive vision-language alignment. Our approach achieves state-of-the-art performance using only a 3D ResNet-18 with vanilla CLIP training, including 83.8\% AUC for zero-shot diagnosis on CT-RATE, 77.3\% AUC on RAD-ChestCT, and substantial improvements in cross-modal retrieval (MAP@50=53.7\% for image-image, Recall@100=52.2\% for report-image). These results demonstrate the potential of utilizing LLMs to facilitate {\bf more performant and scalable} medical AI systems. Our code is avaiable at https://github.com/SadVoxel/More-performant-and-scalable.

[Arxiv](https://arxiv.org/abs/2509.13175)