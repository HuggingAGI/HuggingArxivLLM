# HyViLM：采用混合编码器增强视觉语言模型的细粒度识别能力

发布时间：2024年12月11日

`LLM应用` `计算机视觉` `多模态语言模型`

> HyViLM: Enhancing Fine-Grained Recognition with a Hybrid Encoder for Vision-Language Models

# 摘要

> 最近，多模态大型语言模型（MLLMs）处理高分辨率图像的能力愈发受到关注。当下常见的做法是把原始高分辨率图像动态裁剪成较小的子图像，再将其输入在低分辨率图像上预训练过的视觉编码器。但这种裁剪方式常截断原始图像中的对象和连接区域，造成语义中断。为克服这一局限，我们推出了 HyViLM，它能够处理任何分辨率的图像，且在编码时能保留整体语境。具体而言，我们：（i）设计了名为混合编码器的新型视觉编码器，它不但能对单个子图像编码，还能与详细的全局视觉特征交互，大幅提升了模型对高分辨率图像的编码能力。（ii）为动态裁剪方法提出了最优特征融合策略，有效利用了视觉编码器不同层的信息。在相同设置下与最先进的 MLLMs 相比，我们的 HyViLM 在十个任务中有九个表现更优。具体来说，HyViLM 在 TextVQA 任务上的性能提升了 9.6％，在 DocVQA 任务上提升了 6.9％。

> Recently, there has been growing interest in the capability of multimodal large language models (MLLMs) to process high-resolution images. A common approach currently involves dynamically cropping the original high-resolution image into smaller sub-images, which are then fed into a vision encoder that was pre-trained on lower-resolution images. However, this cropping approach often truncates objects and connected areas in the original image, causing semantic breaks. To address this limitation, we introduce HyViLM, designed to process images of any resolution while retaining the overall context during encoding. Specifically, we: (i) Design a new visual encoder called Hybrid Encoder that not only encodes individual sub-images but also interacts with detailed global visual features, significantly improving the model's ability to encode high-resolution images. (ii) Propose an optimal feature fusion strategy for the dynamic cropping approach, effectively leveraging information from different layers of the vision encoder. Compared with the state-of-the-art MLLMs under the same setting, our HyViLM outperforms existing MLLMs in nine out of ten tasks. Specifically, HyViLM achieves a 9.6% improvement in performance on the TextVQA task and a 6.9% enhancement on the DocVQA task.

[Arxiv](https://arxiv.org/abs/2412.08378)