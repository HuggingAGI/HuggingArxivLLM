# # LMM4LMM：用于大规模多模态图像生成的基准评测与评估

发布时间：2025年04月11日

`LLM应用

理由：这篇论文主要讨论了大型多模态模型（LMMs）在文本到图像生成和图像到文本解释方面的应用，并提出了一种新的评估方法和基准数据集。这些内容属于模型的应用层面，特别是针对多模态生成任务的评估和优化，因此归类为LLM应用。` `图像处理` `计算机视觉`

> LMM4LMM: Benchmarking and Evaluating Large-multimodal Image Generation with LMMs

# 摘要

> 大型多模态模型（LMMs）的最新突破推动了文本到图像（T2I）生成和图像到文本（I2T）解释技术的显著进步。然而，当前生成的图像仍面临感知质量和文本-图像对齐方面的挑战。为解决人工评估效率低下的问题，我们开发了EvalMi-50K，一个全面的大型多模态图像生成评估数据集和基准，具有以下特点：(i) 覆盖20个细粒度任务维度的2,100个广泛提示；(ii) 基于50,400张来自24个T2I模型生成图像的10万条均值意见评分（MOS）和5万条问答（QA）对的标注。基于此，我们提出了LMM4LMM，一个从感知、文本-图像对应和任务特定准确性等多维度评估T2I生成的LMM基指标。实验结果表明，LMM4LMM在EvalMi-50K上表现优异，并在其他AI生成图像评估基准数据集上展现出强大的泛化能力，凸显了EvalMi-50K和LMM4LMM的通用价值。两者将在https://github.com/IntMeGroup/LMM4LMM上开放获取。

> Recent breakthroughs in large multimodal models (LMMs) have significantly advanced both text-to-image (T2I) generation and image-to-text (I2T) interpretation. However, many generated images still suffer from issues related to perceptual quality and text-image alignment. Given the high cost and inefficiency of manual evaluation, an automatic metric that aligns with human preferences is desirable. To this end, we present EvalMi-50K, a comprehensive dataset and benchmark for evaluating large-multimodal image generation, which features (i) comprehensive tasks, encompassing 2,100 extensive prompts across 20 fine-grained task dimensions, and (ii) large-scale human-preference annotations, including 100K mean-opinion scores (MOSs) and 50K question-answering (QA) pairs annotated on 50,400 images generated from 24 T2I models. Based on EvalMi-50K, we propose LMM4LMM, an LMM-based metric for evaluating large multimodal T2I generation from multiple dimensions including perception, text-image correspondence, and task-specific accuracy. Extensive experimental results show that LMM4LMM achieves state-of-the-art performance on EvalMi-50K, and exhibits strong generalization ability on other AI-generated image evaluation benchmark datasets, manifesting the generality of both the EvalMi-50K dataset and LMM4LMM metric. Both EvalMi-50K and LMM4LMM will be released at https://github.com/IntMeGroup/LMM4LMM.

[Arxiv](https://arxiv.org/abs/2504.08358)