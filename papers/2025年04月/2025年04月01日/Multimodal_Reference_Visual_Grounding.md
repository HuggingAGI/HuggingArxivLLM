# 多模态基准视觉定位

发布时间：2025年04月01日

`其他

理由：这篇论文主要探讨的是视觉定位任务，结合多模态参考图像和语言描述，提出了一种新的方法MRVG-Net。虽然文中提到了大型语言模型（LLMs）的应用，但研究的核心是视觉定位和多模态数据处理，属于视觉和多模态领域的应用，而非专注于LLM本身的理论或应用。因此，归类为其他。` `计算机视觉` `多模态`

> Multimodal Reference Visual Grounding

# 摘要

> 视觉定位旨在根据语言描述从图像中识别物体。近年来，大型视觉语言模型（LVLMs）通过大规模数据训练显著提升了视觉定位能力。然而，当图像中出现相似物体时，这一任务依然充满挑战。例如，LVLM可能难以区分 Diet Coke 和普通可乐。此时，若能提供这两种可乐的参考图像，将有助于更准确地定位相似物体。

在本研究中，我们提出了一个新任务——多模态参考视觉定位（MRVG）。该任务中，模型可访问数据库中的物体参考图像。结合这些参考图像和语言描述，模型需从查询图像中识别目标物体。我们首先构建了一个新数据集用于研究 MRVG 问题，随后提出了一种名为 MRVG-Net 的创新方法来解决视觉定位难题。通过高效利用参考图像进行少量样本检测，并结合大型语言模型（LLMs）进行物体匹配，我们的方法在视觉定位性能上超越了 Qwen2.5-VL-7B 等先进 LVLMs。MRVG-Net 成功连接了少量样本检测与视觉定位，为视觉理解开辟了新可能。项目页面（含代码与数据集）：https://irvlutd.github.io/MultiGrounding

> Visual grounding focuses on detecting objects from images based on language expressions. Recent Large Vision-Language Models (LVLMs) have significantly advanced visual grounding performance by training large models with large-scale datasets. However, the problem remains challenging, especially when similar objects appear in the input image. For example, an LVLM may not be able to differentiate Diet Coke and regular Coke in an image. In this case, if additional reference images of Diet Coke and regular Coke are available, it can help the visual grounding of similar objects.
  In this work, we introduce a new task named Multimodal Reference Visual Grounding (MRVG). In this task, a model has access to a set of reference images of objects in a database. Based on these reference images and a language expression, the model is required to detect a target object from a query image. We first introduce a new dataset to study the MRVG problem. Then we introduce a novel method, named MRVG-Net, to solve this visual grounding problem. We show that by efficiently using reference images with few-shot object detection and using Large Language Models (LLMs) for object matching, our method achieves superior visual grounding performance compared to the state-of-the-art LVLMs such as Qwen2.5-VL-7B. Our approach bridges the gap between few-shot detection and visual grounding, unlocking new capabilities for visual understanding. Project page with our code and dataset: https://irvlutd.github.io/MultiGrounding

[Arxiv](https://arxiv.org/abs/2504.02876)