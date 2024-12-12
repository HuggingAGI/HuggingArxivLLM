# 通过有向场景图对大型视觉语言模型进行基准测试，从而实现全面的图像字幕

发布时间：2024年12月11日

`LLM应用` `视觉语言模型` `图像字幕`

> Benchmarking Large Vision-Language Models via Directed Scene Graph for Comprehensive Image Captioning

# 摘要

> 生成能够理解图像中富含文本的视觉内容的详细字幕，在大型视觉语言模型（LVLMs）中受到了越来越多的关注。然而，专门为详细字幕开发以衡量其准确性和全面性的基准研究却很少。在本文中，我们引入了一个名为 CompreCap 的详细字幕基准，从有向场景图的视角来评估视觉上下文。具体而言，我们首先依据常见对象词汇将图像手动分割为具有语义意义的区域（即语义分割掩码），同时区分所有这些区域内对象的属性。接着，为这些对象的方向关系标签进行标注，从而构建一个能够良好编码图像丰富组合信息的有向场景图。基于我们的有向场景图，我们开发了一个流程，从多个层面评估 LVLMs 生成的详细字幕，涵盖对象层面的覆盖度、属性描述的准确性、关键关系的得分等。CompreCap 数据集上的实验结果表明，我们的评估方法在 LVLMs 中与人类评估得分高度一致。

> Generating detailed captions comprehending text-rich visual content in images has received growing attention for Large Vision-Language Models (LVLMs). However, few studies have developed benchmarks specifically tailored for detailed captions to measure their accuracy and comprehensiveness. In this paper, we introduce a detailed caption benchmark, termed as CompreCap, to evaluate the visual context from a directed scene graph view. Concretely, we first manually segment the image into semantically meaningful regions (i.e., semantic segmentation mask) according to common-object vocabulary, while also distinguishing attributes of objects within all those regions. Then directional relation labels of these objects are annotated to compose a directed scene graph that can well encode rich compositional information of the image. Based on our directed scene graph, we develop a pipeline to assess the generated detailed captions from LVLMs on multiple levels, including the object-level coverage, the accuracy of attribute descriptions, the score of key relationships, etc. Experimental results on the CompreCap dataset confirm that our evaluation method aligns closely with human evaluation scores across LVLMs.

[Arxiv](https://arxiv.org/abs/2412.08614)