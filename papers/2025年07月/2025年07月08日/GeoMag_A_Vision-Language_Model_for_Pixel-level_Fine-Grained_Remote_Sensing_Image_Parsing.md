# GeoMag：一款用于像素级细粒度遥感图像解析的视觉语言模型

发布时间：2025年07月08日

`LLM应用

理由：这篇论文主要讨论了视觉语言模型（VLMs）在遥感图像理解中的应用，提出了一种名为GeoMag的端到端通用大型模型框架，用于改进遥感图像的解析能力。论文的重点在于模型的应用和优化，而不是理论上的创新或智能体、检索增强生成等其他领域的研究。因此，它被归类为LLM应用。` `计算机视觉`

> GeoMag: A Vision-Language Model for Pixel-level Fine-Grained Remote Sensing Image Parsing

# 摘要

> 视觉语言模型（VLMs）在遥感图像理解领域取得了显著进展，展现出识别和描述地理实体的基础能力。然而，现有的RS-VLMs主要局限于图像级和区域级任务，缺乏处理像素级任务的能力，且在小物体识别场景中表现欠佳。此外，RS-VLMs在处理高分辨率遥感图像时消耗大量计算资源，限制了其实际应用。针对这些问题，我们提出了GeoMag——一个用于遥感的端到端通用大型模型框架。GeoMag基于提示语义动态调整注意力范围，能够高效地进行多粒度遥感图像解析。该方法创新性地引入了任务驱动的多粒度分辨率调整（TMRA）和提示引导的语义感知裁剪（PSC），通过自适应降低任务无关区域的空间分辨率，同时增强任务相关区域的视觉表征。这不仅提升了模型对关键目标区域的感知能力，还有效抑制了背景冗余，降低了高分辨率遥感图像解析的计算成本。在10个基准数据集上的广泛比较实验表明，GeoMag不仅在像素级任务中表现优异，还在其他粒度的任务中保持了强大的竞争力。

> The application of Vision-Language Models (VLMs) in remote sensing (RS) image understanding has achieved notable progress, demonstrating the basic ability to recognize and describe geographical entities. However, existing RS-VLMs are mostly limited to image-level and region-level tasks, lacking the capability to handle pixel-level tasks and performing poorly in small-object recognition scenarios. Moreover, RS-VLMs consume significant computational resources when processing high-resolution RS images, further restricting their practical applicability. In this context, we propose GeoMag (Geographical Magnifier), an end-to-end general-purpose large model framework for RS. GeoMag dynamically focuses the attention scope based on prompt semantics to effectively perform remote sensing image parsing across multiple levels of granularity. This method introduces Task-driven Multi-granularity Resolution Adjustment (TMRA) and Prompt-guided Semantic-aware Cropping (PSC), which adaptively reduce the spatial resolution of task-irrelevant regions while enhancing the visual representation of task-relevant areas. This approach improves the model's perception of critical target regions, suppresses background redundancy, and reduces the computational cost of interpreting high-resolution RS imagery. Extensive comparative experiments on 10 benchmarks demonstrate that GeoMag not only excels in handling pixel-level tasks but also maintains competitive performance across tasks of other granularities compared to existing RS-VLMs.

[Arxiv](https://arxiv.org/abs/2507.05887)