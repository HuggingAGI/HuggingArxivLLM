# Patch Matters：无需训练的图像细粒度描述增强——通过局部感知实现

发布时间：2025年04月09日

`LLM应用` `图像处理`

> Patch Matters: Training-free Fine-grained Image Caption Enhancement via Local Perception

# 摘要

> 高质量的图像描述对提升文本到图像生成、文本到视频生成以及文本-图像检索等跨模态应用的性能至关重要。为了生成长篇且高质量的描述，许多近期研究采用了多模态大型语言模型（MLLMs）。然而，当前MLLMs生成的描述往往缺乏精细细节或存在幻觉问题，这一现象在开源和闭源模型中都普遍存在。受特征整合理论启发，我们提出了一种	extbf{分而治之再聚合}的策略。首先，我们将图像划分为语义和空间补丁以提取精细细节，增强模型的局部感知能力。随后，这些局部细节以层次化方式聚合，生成全面的全局描述。为了解决生成描述中的幻觉和不一致问题，我们在层次化聚合过程中引入了语义层面的过滤机制。这一无需重新训练模型的pipeline支持开源模型（LLaVA-1.5, LLaVA-1.6, Mini-Gemini）和闭源模型（Claude-3.5-Sonnet, GPT-4o, GLM-4V-Plus）。实验结果表明，我们的方法能够生成更详细、可靠的描述，推动了多模态描述生成技术的发展。源代码可在https://github.com/GeWu-Lab/Patch-Matters获取

> High-quality image captions play a crucial role in improving the performance of cross-modal applications such as text-to-image generation, text-to-video generation, and text-image retrieval. To generate long-form, high-quality captions, many recent studies have employed multimodal large language models (MLLMs). However, current MLLMs often produce captions that lack fine-grained details or suffer from hallucinations, a challenge that persists in both open-source and closed-source models. Inspired by Feature-Integration theory, which suggests that attention must focus on specific regions to integrate visual information effectively, we propose a \textbf{divide-then-aggregate} strategy. Our method first divides the image into semantic and spatial patches to extract fine-grained details, enhancing the model's local perception of the image. These local details are then hierarchically aggregated to generate a comprehensive global description. To address hallucinations and inconsistencies in the generated captions, we apply a semantic-level filtering process during hierarchical aggregation. This training-free pipeline can be applied to both open-source models (LLaVA-1.5, LLaVA-1.6, Mini-Gemini) and closed-source models (Claude-3.5-Sonnet, GPT-4o, GLM-4V-Plus). Extensive experiments demonstrate that our method generates more detailed, reliable captions, advancing multimodal description generation without requiring model retraining. The source code are available at https://github.com/GeWu-Lab/Patch-Matters

[Arxiv](https://arxiv.org/abs/2504.06666)