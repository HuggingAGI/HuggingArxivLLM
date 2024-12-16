# BrushEdit：一站式图像修复与编辑

发布时间：2024年12月13日

`LLM应用` `图像编辑` `计算机视觉`

> BrushEdit: All-In-One Image Inpainting and Editing

# 摘要

> 图像编辑因使用基于反转和基于指令的方法的扩散模型而有了显著进展。但当前基于反转的方法因反转噪声的结构化特性，在大的修改（如添加或删除对象）上遭遇难题，阻碍了实质性变化。同时，基于指令的方法常把用户限制在黑箱操作里，限制了指定编辑区域和强度的直接交互。为应对这些局限，我们提出了 BrushEdit，这是一种新颖的基于修复的指令引导图像编辑范式，借助多模态大型语言模型（MLLMs）和图像修复模型，实现了自主、用户友好且交互式的自由形式指令编辑。具体而言，我们设计了一个系统，在代理协作框架中集成 MLLMs 和双分支图像修复模型，实现自由形式的指令编辑，进行编辑类别分类、主要对象识别、掩码获取和编辑区域修复。大量实验表明，我们的框架有效结合了 MLLMs 和修复模型，在掩码区域保留和编辑效果一致性等七个指标上表现出色。

> Image editing has advanced significantly with the development of diffusion models using both inversion-based and instruction-based methods. However, current inversion-based approaches struggle with big modifications (e.g., adding or removing objects) due to the structured nature of inversion noise, which hinders substantial changes. Meanwhile, instruction-based methods often constrain users to black-box operations, limiting direct interaction for specifying editing regions and intensity. To address these limitations, we propose BrushEdit, a novel inpainting-based instruction-guided image editing paradigm, which leverages multimodal large language models (MLLMs) and image inpainting models to enable autonomous, user-friendly, and interactive free-form instruction editing. Specifically, we devise a system enabling free-form instruction editing by integrating MLLMs and a dual-branch image inpainting model in an agent-cooperative framework to perform editing category classification, main object identification, mask acquisition, and editing area inpainting. Extensive experiments show that our framework effectively combines MLLMs and inpainting models, achieving superior performance across seven metrics including mask region preservation and editing effect coherence.

[Arxiv](https://arxiv.org/abs/2412.10316)