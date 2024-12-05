# DynamicControl：用于优化文本到图像生成的自适应条件筛选

发布时间：2024年12月04日

`LLM应用` `图像合成` `人工智能`

> DynamicControl: Adaptive Condition Selection for Improved Text-to-Image Generation

# 摘要

> 为增强文本到图像扩散模型的可控性，当下类似 ControlNet 的模型已探索多种控制信号来界定图像属性。然而，现有的方法要么处理条件效率低，要么采用固定数量的条件，无法完全应对多个条件的复杂性及其潜在冲突。这凸显出需要创新手段来有效管理多个条件，以达成更可靠、更细致的图像合成。为解决此问题，我们提出全新框架 DynamicControl，它支持不同控制信号的动态组合，能够自适应选取不同数量和类型的条件。我们的方法以双循环控制器开篇，该控制器借助预训练的条件生成模型和判别模型，为所有输入条件生成初始的真实分数排序。此控制器评估提取条件与输入条件的相似性，以及与源图像的像素级相似性。接着，我们融入一个多模态大型语言模型（MLLM）来构建高效的条件评估器。该评估器依据双循环控制器的分数排名优化条件顺序。我们的方法共同优化 MLLM 和扩散模型，利用 MLLM 的推理能力助力多条件的文本到图像（T2I）任务。最终排序后的条件被输入并行多控制适配器，该适配器从动态视觉条件中学习特征图并加以整合，以调制 ControlNet，进而增强对生成图像的控制。通过定量和定性的对比，DynamicControl 在各种条件控制下的可控性、生成质量和可组合性方面，均展现出优于现有方法的长处。

> To enhance the controllability of text-to-image diffusion models, current ControlNet-like models have explored various control signals to dictate image attributes. However, existing methods either handle conditions inefficiently or use a fixed number of conditions, which does not fully address the complexity of multiple conditions and their potential conflicts. This underscores the need for innovative approaches to manage multiple conditions effectively for more reliable and detailed image synthesis. To address this issue, we propose a novel framework, DynamicControl, which supports dynamic combinations of diverse control signals, allowing adaptive selection of different numbers and types of conditions. Our approach begins with a double-cycle controller that generates an initial real score sorting for all input conditions by leveraging pre-trained conditional generation models and discriminative models. This controller evaluates the similarity between extracted conditions and input conditions, as well as the pixel-level similarity with the source image. Then, we integrate a Multimodal Large Language Model (MLLM) to build an efficient condition evaluator. This evaluator optimizes the ordering of conditions based on the double-cycle controller's score ranking. Our method jointly optimizes MLLMs and diffusion models, utilizing MLLMs' reasoning capabilities to facilitate multi-condition text-to-image (T2I) tasks. The final sorted conditions are fed into a parallel multi-control adapter, which learns feature maps from dynamic visual conditions and integrates them to modulate ControlNet, thereby enhancing control over generated images. Through both quantitative and qualitative comparisons, DynamicControl demonstrates its superiority over existing methods in terms of controllability, generation quality and composability under various conditional controls.

[Arxiv](https://arxiv.org/abs/2412.03255)