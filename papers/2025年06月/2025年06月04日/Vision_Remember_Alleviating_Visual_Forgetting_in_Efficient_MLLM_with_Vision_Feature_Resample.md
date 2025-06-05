# Vision Remember：缓解高效多模态大语言模型中的视觉遗忘问题——基于视觉特征重采样

发布时间：2025年06月04日

`LLM应用` `计算机视觉` `多模态模型`

> Vision Remember: Alleviating Visual Forgetting in Efficient MLLM with Vision Feature Resample

# 摘要

> 本研究聚焦于高效多模态大型语言模型。冗余的视觉标记会占用大量计算资源，因此许多先前工作通过视觉投影器压缩这些标记以减少数量。然而，这种压缩方式可能导致视觉信息丢失，尤其对OCR和图表理解等依赖精细空间关系的任务影响较大。为解决这一问题，我们提出了名为Vision Remember的模块，将其嵌入到LLM解码器层之间，使视觉标记能够重新记忆视觉特征。具体而言，我们保留多级视觉特征，并与已与文本标记交互的视觉标记一起重新采样它们。在重新采样过程中，每个视觉标记仅关注视觉特征中的局部区域，这被称为增强显著性的局部注意力机制。这种机制不仅提升了计算效率，还能够捕捉到区域内更精细的上下文信息和空间关系。在多个视觉理解基准上的全面实验验证了我们方法的有效性，当与各种高效视觉投影器结合使用时，不仅性能有所提升，而且并未牺牲效率。基于Vision Remember模块，仅拥有20亿参数的LLaVA-VR也优于之前的代表性多模态大语言模型，如Tokenpacker-HD-7B和DeepSeek-VL-7B。

> In this work, we study the Efficient Multimodal Large Language Model. Redundant vision tokens consume a significant amount of computational memory and resources. Therefore, many previous works compress them in the Vision Projector to reduce the number of vision tokens. However, simply compressing in the Vision Projector can lead to the loss of visual information, especially for tasks that rely on fine-grained spatial relationships, such as OCR and Chart \& Table Understanding. To address this problem, we propose Vision Remember, which is inserted between the LLM decoder layers to allow vision tokens to re-memorize vision features. Specifically, we retain multi-level vision features and resample them with the vision tokens that have interacted with the text token. During the resampling process, each vision token only attends to a local region in vision features, which is referred to as saliency-enhancing local attention. Saliency-enhancing local attention not only improves computational efficiency but also captures more fine-grained contextual information and spatial relationships within the region. Comprehensive experiments on multiple visual understanding benchmarks validate the effectiveness of our method when combined with various Efficient Vision Projectors, showing performance gains without sacrificing efficiency. Based on Vision Remember, LLaVA-VR with only 2B parameters is also superior to previous representative MLLMs such as Tokenpacker-HD-7B and DeepSeek-VL-7B.

[Arxiv](https://arxiv.org/abs/2506.03928)