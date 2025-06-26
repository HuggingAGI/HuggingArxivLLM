# VisualChef：通过Mask Inpainting打造烹饪视觉辅助

发布时间：2025年06月23日

`其他` `计算机视觉`

> VisualChef: Generating Visual Aids in Cooking via Mask Inpainting

# 摘要

> 烹饪不仅是遵循指令，更是理解、执行和监控每一步骤的过程，缺少视觉指导会带来不小挑战。虽然食谱图片和视频提供了有用提示，但它们常在焦点、工具和设置上缺乏一致性。为此，我们推出VisualChef，一种专为烹饪场景设计的上下文视觉辅助生成方法。通过输入初始帧和指定动作，VisualChef不仅能呈现动作执行过程，还能展示物体最终状态，同时保留初始环境。与以往需要通过详细文本描述整合大型语言模型知识、要求高精度视觉-文本对齐且需额外标注的研究不同，VisualChef采用基于掩码的视觉定位，大大简化了对齐过程。我们的核心突破在于识别与动作相关的物体并进行分类，从而实现精准修改，既反映预期动作和结果，又保持环境一致性。此外，我们还开发了一套自动化流程，用于提取高质量的初始、动作和最终状态帧。通过在三个第一人称视角视频数据集上的定量和定性评估，VisualChef展现出超越现有最优方法的显著优势。

> Cooking requires not only following instructions but also understanding, executing, and monitoring each step - a process that can be challenging without visual guidance. Although recipe images and videos offer helpful cues, they often lack consistency in focus, tools, and setup. To better support the cooking process, we introduce VisualChef, a method for generating contextual visual aids tailored to cooking scenarios. Given an initial frame and a specified action, VisualChef generates images depicting both the action's execution and the resulting appearance of the object, while preserving the initial frame's environment. Previous work aims to integrate knowledge extracted from large language models by generating detailed textual descriptions to guide image generation, which requires fine-grained visual-textual alignment and involves additional annotations. In contrast, VisualChef simplifies alignment through mask-based visual grounding. Our key insight is identifying action-relevant objects and classifying them to enable targeted modifications that reflect the intended action and outcome while maintaining a consistent environment. In addition, we propose an automated pipeline to extract high-quality initial, action, and final state frames. We evaluate VisualChef quantitatively and qualitatively on three egocentric video datasets and show its improvements over state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2506.18569)