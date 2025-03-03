# PathVG: 病理学视觉定位的新基准与数据集

发布时间：2025年02月28日

`LLM应用` `计算机视觉`

> PathVG: A New Benchmark and Dataset for Pathology Visual Grounding

# 摘要

> 随着计算病理学的快速发展，AI辅助诊断任务不断涌现。细胞核分割虽能分离多种细胞类型供后续分析，但受限于预定义类别，灵活性不足。病理视觉问答虽能理解图像整体，却无法精准定位区域。为此，我们推出病理视觉定位（PathVG）这一新基准，旨在根据多属性表达精确定位区域。为评估PathVG，我们构建了RefPath数据集，包含27,610张图像和33,500个语言定位框。与其它领域相比，PathVG的独特之处在于多尺度呈现病理图像，并融入专业知识。实验中，我们发现病理表达中的隐含信息是主要挑战。为此，我们开发了病理知识增强网络（PKNet）作为基线模型。PKNet借助大型语言模型的知识增强能力，将隐含信息的病理术语转化为显式视觉特征，并通过知识融合模块（KFM）实现特征融合。该方法在PathVG基准测试中表现优异，达到了当前最佳水平。

> With the rapid development of computational pathology, many AI-assisted diagnostic tasks have emerged. Cellular nuclei segmentation can segment various types of cells for downstream analysis, but it relies on predefined categories and lacks flexibility. Moreover, pathology visual question answering can perform image-level understanding but lacks region-level detection capability. To address this, we propose a new benchmark called Pathology Visual Grounding (PathVG), which aims to detect regions based on expressions with different attributes. To evaluate PathVG, we create a new dataset named RefPath which contains 27,610 images with 33,500 language-grounded boxes. Compared to visual grounding in other domains, PathVG presents pathological images at multi-scale and contains expressions with pathological knowledge. In the experimental study, we found that the biggest challenge was the implicit information underlying the pathological expressions. Based on this, we proposed Pathology Knowledge-enhanced Network (PKNet) as the baseline model for PathVG. PKNet leverages the knowledge-enhancement capabilities of Large Language Models (LLMs) to convert pathological terms with implicit information into explicit visual features, and fuses knowledge features with expression features through the designed Knowledge Fusion Module (KFM). The proposed method achieves state-of-the-art performance on the PathVG benchmark.

[Arxiv](https://arxiv.org/abs/2502.20869)