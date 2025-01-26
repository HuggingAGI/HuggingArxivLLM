# 一提示一故事：用单一提示实现文本到图像生成的免费午餐一致性

发布时间：2025年01月23日

`LLM应用

**理由**：该论文主要探讨了如何利用语言模型的“上下文一致性”能力来改进文本到图像生成模型，特别是在故事叙述中保持角色身份一致性。虽然涉及图像生成，但其核心创新点在于利用语言模型的提示理解能力来优化生成过程，因此可以归类为LLM应用。` `图像生成` `故事叙述`

> One-Prompt-One-Story: Free-Lunch Consistent Text-to-Image Generation Using a Single Prompt

# 摘要

> # 摘要
文本到图像生成模型能够根据输入提示生成高质量图像，但在满足故事叙述中身份一致性需求方面仍有不足。现有方法通常依赖大规模数据集训练或对模型架构进行额外调整，这限制了其跨领域和多样化扩散模型配置的适用性。本文首次揭示了语言模型通过单一提示理解身份的“上下文一致性”能力。基于此，我们提出了一种无需训练的一致文本到图像生成方法——“一提示一故事”（1Prompt1Story）。该方法将所有提示整合为单一输入，初始保持角色身份，并通过“奇异值重加权”和“身份保持交叉注意力”两项新技术优化生成过程，确保每帧图像与输入描述高度一致。实验通过定量和定性评估，验证了该方法相较于现有一致T2I生成方法的优越性。代码已开源：https://github.com/byliutao/1Prompt1Story。

> Text-to-image generation models can create high-quality images from input prompts. However, they struggle to support the consistent generation of identity-preserving requirements for storytelling. Existing approaches to this problem typically require extensive training in large datasets or additional modifications to the original model architectures. This limits their applicability across different domains and diverse diffusion model configurations. In this paper, we first observe the inherent capability of language models, coined context consistency, to comprehend identity through context with a single prompt. Drawing inspiration from the inherent context consistency, we propose a novel training-free method for consistent text-to-image (T2I) generation, termed "One-Prompt-One-Story" (1Prompt1Story). Our approach 1Prompt1Story concatenates all prompts into a single input for T2I diffusion models, initially preserving character identities. We then refine the generation process using two novel techniques: Singular-Value Reweighting and Identity-Preserving Cross-Attention, ensuring better alignment with the input description for each frame. In our experiments, we compare our method against various existing consistent T2I generation approaches to demonstrate its effectiveness through quantitative metrics and qualitative assessments. Code is available at https://github.com/byliutao/1Prompt1Story.

[Arxiv](https://arxiv.org/abs/2501.13554)