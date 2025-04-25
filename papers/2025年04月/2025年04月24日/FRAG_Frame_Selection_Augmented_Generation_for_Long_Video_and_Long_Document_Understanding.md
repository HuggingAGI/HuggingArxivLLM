# FRAG：基于帧选择增强的生成方法，助力长视频与长文档理解

发布时间：2025年04月24日

`LLM应用` `视频处理` `文档分析`

> FRAG: Frame Selection Augmented Generation for Long Video and Long Document Understanding

# 摘要

> 大型多模态模型（LMMs）的发展令人瞩目，近期研究已将其扩展至长输入处理，涵盖多页文档与长视频。然而，受限于训练与推理的计算成本，现有长上下文模型的规模与性能仍显不足。本研究另辟蹊径，提出无需依赖长上下文LMMs的解决方案——帧选择增强生成（FRAG）。该方法通过模型先筛选输入中的关键帧，再基于这些帧生成最终输出。其核心在于为每个帧独立打分，无需复杂的长上下文处理。随后采用简单的Top-K策略选出高分帧。实验表明，FRAG框架无需额外微调，即可借助现有LMMs高效处理长视频与多页文档。我们在LLaVA-OneVision与InternVL2模型上进行了测试，结果显示FRAG显著提升了模型性能，尤其在长视频与长文档理解任务中达到业界领先水平。具体而言，FRAG使InternVL2-76B在MLVU任务中提升5.8%，在Video-MME任务中提升3.7%。在文档理解任务MP-DocVQA中，FRAG相比专注于长文档的LMMs实现了超20%的性能提升。项目代码已开源，访问地址为：https://github.com/NVlabs/FRAG

> There has been impressive progress in Large Multimodal Models (LMMs). Recent works extend these models to long inputs, including multi-page documents and long videos. However, the model size and performance of these long context models are still limited due to the computational cost in both training and inference. In this work, we explore an orthogonal direction and process long inputs without long context LMMs. We propose Frame Selection Augmented Generation (FRAG), where the model first selects relevant frames within the input, and then only generates the final outputs based on the selected frames. The core of the selection process is done by scoring each frame independently, which does not require long context processing. The frames with the highest scores are then selected by a simple Top-K selection. We show that this frustratingly simple framework is applicable to both long videos and multi-page documents using existing LMMs without any fine-tuning. We consider two models, LLaVA-OneVision and InternVL2, in our experiments and show that FRAG consistently improves the performance and achieves state-of-the-art performances for both long video and long document understanding. For videos, FRAG substantially improves InternVL2-76B by 5.8% on MLVU and 3.7% on Video-MME. For documents, FRAG achieves over 20% improvements on MP-DocVQA compared with recent LMMs specialized in long document understanding. Code is available at: https://github.com/NVlabs/FRAG

[Arxiv](https://arxiv.org/abs/2504.17447)