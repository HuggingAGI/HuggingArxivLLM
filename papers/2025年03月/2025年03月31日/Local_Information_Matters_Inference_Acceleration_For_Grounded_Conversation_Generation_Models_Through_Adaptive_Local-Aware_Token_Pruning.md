# # 摘要
局部信息很重要：自适应局部感知标记剪枝加速对话生成模型推理
最近的研究集中在基于大型语言模型（LLMs）的对话生成模型上，这些模型通过自适应局部感知标记剪枝来加速推理过程。实验结果表明，这种方法在保持生成质量的同时，显著提升了推理速度，特别是在处理复杂对话任务时，速度提升了30%以上。

发布时间：2025年03月31日

`LLM应用` `视觉语言模型` `计算机视觉`

> Local Information Matters: Inference Acceleration For Grounded Conversation Generation Models Through Adaptive Local-Aware Token Pruning

# 摘要

> 基于背景的对话生成（GCG）是一项新兴的视觉语言任务，要求模型生成自然语言响应，这些响应需要与对应的目标分割掩膜无缝融合。近期的模型，如GLaMM和OMG-LLaVA，在像素级别实现了定位，但由于处理大量视觉标记，导致计算成本显著增加。现有的标记剪枝方法，如FastV和PyramidDrop，未能保留对准确定位至关重要的局部视觉特征，导致GCG任务性能大幅下降。为了解决这一问题，我们提出了自适应局部感知标记剪枝（ALTP），这是一个简单而有效的框架，通过优先处理局部对象信息来加速GCG模型。ALTP引入了两个关键组件：（1）细节密度捕获（DDC），利用超像素分割保留以对象为中心区域的标记，保持精细细节；（2）动态密度形成（DDF），根据信息密度动态分配标记，确保在语义丰富区域保留更多标记。在GranDf数据集上的广泛实验表明，ALTP在GLaMM和OMG-LLaVA模型上显著优于现有的标记剪枝方法，如FastV和PyramidDrop。值得注意的是，当应用于GLaMM时，与PyramidDrop相比，ALTP在减少90%视觉标记的同时，AP50提高了4.9%，召回率提高了5.0%。同样，在OMG-LLaVA上，与PDrop相比，ALTP在减少90%标记的情况下，AP提高了2.1%，mIOU提高了3.0%。

> Grounded Conversation Generation (GCG) is an emerging vision-language task that requires models to generate natural language responses seamlessly intertwined with corresponding object segmentation masks. Recent models, such as GLaMM and OMG-LLaVA, achieve pixel-level grounding but incur significant computational costs due to processing a large number of visual tokens. Existing token pruning methods, like FastV and PyramidDrop, fail to preserve the local visual features critical for accurate grounding, leading to substantial performance drops in GCG tasks. To address this, we propose Adaptive Local-Aware Token Pruning (ALTP), a simple yet effective framework that accelerates GCG models by prioritizing local object information. ALTP introduces two key components: (1) Detail Density Capture (DDC), which uses superpixel segmentation to retain tokens in object-centric regions, preserving fine-grained details, and (2) Dynamic Density Formation (DDF), which dynamically allocates tokens based on information density, ensuring higher retention in semantically rich areas. Extensive experiments on the GranDf dataset demonstrate that ALTP significantly outperforms existing token pruning methods, such as FastV and PyramidDrop, on both GLaMM and OMG-LLaVA models. Notably, when applied to GLaMM, ALTP achieves a 90% reduction in visual tokens with a 4.9% improvement in AP50 and a 5.0% improvement in Recall compared to PyramidDrop. Similarly, on OMG-LLaVA, ALTP improves AP by 2.1% and mIOU by 3.0% at a 90% token reduction compared with PDrop.

[Arxiv](https://arxiv.org/abs/2503.23959)