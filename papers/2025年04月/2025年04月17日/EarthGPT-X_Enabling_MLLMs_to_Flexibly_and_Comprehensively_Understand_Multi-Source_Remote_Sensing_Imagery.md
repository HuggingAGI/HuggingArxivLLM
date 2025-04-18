# EarthGPT-X：赋能多语言模型灵活全面解析多源遥感影像

发布时间：2025年04月17日

`LLM应用` `视觉语言模型`

> EarthGPT-X: Enabling MLLMs to Flexibly and Comprehensively Understand Multi-Source Remote Sensing Imagery

# 摘要

> 视觉语言领域的开创性进展催生了通过视觉提示进行空间推理的自然多模态大型语言模型（MLLMs）。然而，遥感（RS）图像蕴含丰富的地理空间信息，与自然图像存在显著差异，这使得将自然空间模型直接应用于RS领域面临挑战。此外，现有RS MLLMs在解释范围和交互方式上过于局限，限制了其在实际场景中的应用潜力。为应对这些挑战，我们提出了一种名为EarthGPT-X的空间MLLM，它能够全面理解多源RS图像，包括光学、合成孔径雷达（SAR）和红外图像。EarthGPT-X不仅具备 zoom-in 和 zoom-out 的独特视角，还拥有灵活的多粒度交互能力。此外，它将两种关键空间任务（即引用和定位）巧妙地统一在一个视觉提示框架中。为了实现这些卓越功能，我们开发了三项核心策略：首先，多模态内容整合方法增强了图像、视觉提示与文本指令之间的协同作用；其次，跨域单阶段融合训练策略利用大型语言模型（LLM）作为多源多任务学习的统一接口；最后，通过引入像素感知模块，成功将引用和定位任务无缝整合到同一框架中。实验结果充分证明了EarthGPT-X在多粒度任务中的卓越性能以及在多模态交互中的出色灵活性，标志着MLLM在RS领域的重要突破。

> Recent advances in the visual-language area have developed natural multi-modal large language models (MLLMs) for spatial reasoning through visual prompting. However, due to remote sensing (RS) imagery containing abundant geospatial information that differs from natural images, it is challenging to effectively adapt natural spatial models to the RS domain. Moreover, current RS MLLMs are limited in overly narrow interpretation levels and interaction manner, hindering their applicability in real-world scenarios. To address those challenges, a spatial MLLM named EarthGPT-X is proposed, enabling a comprehensive understanding of multi-source RS imagery, such as optical, synthetic aperture radar (SAR), and infrared. EarthGPT-X offers zoom-in and zoom-out insight, and possesses flexible multi-grained interactive abilities. Moreover, EarthGPT-X unifies two types of critical spatial tasks (i.e., referring and grounding) into a visual prompting framework. To achieve these versatile capabilities, several key strategies are developed. The first is the multi-modal content integration method, which enhances the interplay between images, visual prompts, and text instructions. Subsequently, a cross-domain one-stage fusion training strategy is proposed, utilizing the large language model (LLM) as a unified interface for multi-source multi-task learning. Furthermore, by incorporating a pixel perception module, the referring and grounding tasks are seamlessly unified within a single framework. In addition, the experiments conducted demonstrate the superiority of the proposed EarthGPT-X in multi-grained tasks and its impressive flexibility in multi-modal interaction, revealing significant advancements of MLLM in the RS field.

[Arxiv](https://arxiv.org/abs/2504.12795)