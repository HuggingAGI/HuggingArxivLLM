# # 基于多模态大语言模型的可解释可靠AI图像生成检测方法

发布时间：2025年06月08日

`LLM应用` `图像生成` `计算机视觉`

> Interpretable and Reliable Detection of AI-Generated Images via Grounded Reasoning in MLLMs

# 摘要

> 图像生成技术的快速发展进一步推动了对可解释且稳健检测方法的需求。现有方法虽能实现高准确度，却常以黑箱形式运行，缺乏人类可理解的解释。尽管多模态大语言模型（MLLMs）最初并非为伪造检测设计，但其强大的分析和推理能力使其在经过适当微调后，能够有效识别AI生成图像并提供有意义的解释。然而，现有MLLMs仍面临生成幻觉和视觉解释与实际图像内容及人类推理不一致的挑战。为解决这一问题，我们构建了一个标注数据集，包含标注了边界框和描述性说明的AI生成图像，这些说明突出了合成伪迹，为与人类一致的视觉-文本推理奠定了基础。通过多阶段优化策略对MLLMs进行微调，逐步平衡了准确检测、视觉定位和连贯文本解释的目标。最终模型在检测AI生成图像和定位视觉缺陷方面表现卓越，显著超越了基线方法。

> The rapid advancement of image generation technologies intensifies the demand for interpretable and robust detection methods. Although existing approaches often attain high accuracy, they typically operate as black boxes without providing human-understandable justifications. Multi-modal Large Language Models (MLLMs), while not originally intended for forgery detection, exhibit strong analytical and reasoning capabilities. When properly fine-tuned, they can effectively identify AI-generated images and offer meaningful explanations. However, existing MLLMs still struggle with hallucination and often fail to align their visual interpretations with actual image content and human reasoning. To bridge this gap, we construct a dataset of AI-generated images annotated with bounding boxes and descriptive captions that highlight synthesis artifacts, establishing a foundation for human-aligned visual-textual grounded reasoning. We then finetune MLLMs through a multi-stage optimization strategy that progressively balances the objectives of accurate detection, visual localization, and coherent textual explanation. The resulting model achieves superior performance in both detecting AI-generated images and localizing visual flaws, significantly outperforming baseline methods.

[Arxiv](https://arxiv.org/abs/2506.07045)