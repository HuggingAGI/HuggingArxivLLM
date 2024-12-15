# ATPrompt：带有嵌入式属性的文本提示学习

发布时间：2024年12月12日

`LLM应用` `视觉语言` `图像识别`

> ATPrompt: Textual Prompt Learning with Embedded Attributes

# 摘要

> 基于文本的提示学习方法主要采用级联方式，将多个可学习的软提示和硬类别标记作为文本提示输入，旨在为下游任务实现图像与文本（类别）空间的对齐。然而，当下的训练只能让图像与预先设定的已知类别对齐，无法关联未知类别。在本研究中，我们提议以通用属性为桥梁，强化图像与未知类别的对齐。具体来说，我们为视觉语言模型引入了一种名为 ATPrompt 的嵌入属性的文本提示学习方法。该方法把多个通用属性标记融入可学习的软提示，将软提示的学习空间从原本的一维类别层面拓展到多维属性层面。通过这一改进，我们把文本提示从以类别为核心的形式转变为属性-类别混合形式。为确定下游任务的属性，我们提出一种可微的属性搜索方法，它能从大型语言模型总结的候选池中识别出有代表性且合适的属性。作为一种易用的插件技术，ATPrompt 能够无缝替换现有基于文本方法的提示格式，以微不足道的计算成本实现一般性的提升。在 11 个数据集上开展的大量实验证明了我们方法的有效性。

> Textual-based prompt learning methods primarily employ multiple learnable soft prompts and hard class tokens in a cascading manner as text prompt inputs, aiming to align image and text (category) spaces for downstream tasks. However, current training is restricted to aligning images with predefined known categories and cannot be associated with unknown categories. In this work, we propose utilizing universal attributes as a bridge to enhance the alignment between images and unknown categories. Specifically, we introduce an Attribute-embedded Textual Prompt learning method for vision-language models, named ATPrompt. This approach expands the learning space of soft prompts from the original one-dimensional category level into the multi-dimensional attribute level by incorporating multiple universal attribute tokens into the learnable soft prompts. Through this modification, we transform the text prompt from a category-centric form to an attribute-category hybrid form. To finalize the attributes for downstream tasks, we propose a differentiable attribute search method that learns to identify representative and suitable attributes from a candidate pool summarized by a large language model. As an easy-to-use plug-in technique, ATPrompt can seamlessly replace the existing prompt format of textual-based methods, offering general improvements at a negligible computational cost. Extensive experiments on 11 datasets demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2412.09442)