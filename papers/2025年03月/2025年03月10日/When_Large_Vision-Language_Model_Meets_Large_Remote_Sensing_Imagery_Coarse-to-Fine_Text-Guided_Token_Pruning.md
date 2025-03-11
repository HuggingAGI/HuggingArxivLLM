# 大规模视觉语言模型邂逅大规模遥感影像：基于文本引导的粗细结合分词剪裁

发布时间：2025年03月10日

`其他` `计算机视觉`

> When Large Vision-Language Model Meets Large Remote Sensing Imagery: Coarse-to-Fine Text-Guided Token Pruning

# 摘要

> 高效处理大型遥感图像（RSIs）的视觉-语言理解意义重大，但充满挑战。现有的大型视觉-语言模型（LVLMs）通常依赖有限的预定义网格处理图像，这在面对巨幅遥感图像时会引发信息流失。而采用无限网格则会导致计算成本激增。为了解决这一矛盾，我们提出了一种结合动态图像金字塔（DIP）的文本引导式token剪枝方法，旨在保留图像细节的同时降低计算复杂度。我们的方法包含两大创新：(i) 区域聚焦模块（RFM），它通过文本感知的区域定位能力精准识别关键视觉token；(ii) 基于DIP的从粗到细的图像块选择与视觉token剪枝策略，该策略由RFM的输出引导，避免直接处理完整大型图像。此外，现有用于评估LVLMs处理大遥感图像能力的基准测试在问题多样性和图像尺寸方面存在明显限制。为此，我们构建了一个全新的基准测试LRS-VQA，包含8个类别的7,333个问答对，图像长度可达27,328像素。在使用相同数据的四个数据集上，我们的方法在高分辨率策略中表现优于现有方法。与现有token减少方法相比，我们的方法在高分辨率设置下展现出更高的效率。数据集和代码可在https://github.com/VisionXLab/LRS-VQA获取。

> Efficient vision-language understanding of large Remote Sensing Images (RSIs) is meaningful but challenging. Current Large Vision-Language Models (LVLMs) typically employ limited pre-defined grids to process images, leading to information loss when handling gigapixel RSIs. Conversely, using unlimited grids significantly increases computational costs. To preserve image details while reducing computational complexity, we propose a text-guided token pruning method with Dynamic Image Pyramid (DIP) integration. Our method introduces: (i) a Region Focus Module (RFM) that leverages text-aware region localization capability to identify critical vision tokens, and (ii) a coarse-to-fine image tile selection and vision token pruning strategy based on DIP, which is guided by RFM outputs and avoids directly processing the entire large imagery. Additionally, existing benchmarks for evaluating LVLMs' perception ability on large RSI suffer from limited question diversity and constrained image sizes. We construct a new benchmark named LRS-VQA, which contains 7,333 QA pairs across 8 categories, with image length up to 27,328 pixels. Our method outperforms existing high-resolution strategies on four datasets using the same data. Moreover, compared to existing token reduction methods, our approach demonstrates higher efficiency under high-resolution settings. Dataset and code are in https://github.com/VisionXLab/LRS-VQA.

[Arxiv](https://arxiv.org/abs/2503.07588)