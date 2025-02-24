# # LAVID：一个检测扩散生成视频的代理式LVLM框架

发布时间：2025年02月20日

`LLM应用` `视频生成` `AI生成内容检测`

> LAVID: An Agentic LVLM Framework for Diffusion-Generated Video Detection

# 摘要

> 生成模型在视频创作领域的卓越表现引发了人们对数字完整性和隐私安全的广泛关注。尽管AI生成内容检测在图像领域（如深度伪造）取得了显著进展，但视频领域的研究仍是一片蓝海。大型视觉语言模型（LVLM）凭借其强大的推理和多模态处理能力，正在成为AI生成内容检测的重要工具。它突破了传统深度学习方法的局限，如缺乏透明度和难以识别新型生成内容。基于这一趋势，我们提出了LAVID——一种基于LVLM的AI生成视频检测方法，通过显式知识增强实现更高效的视频检测。我们的主要发现包括：(1) 领先的LVLM能够调用外部工具提取有用信息，从而辅助自身完成视频检测任务；(2) 优化提示结构能够显著提升LVLM对视频内容信息的推理和解释能力。我们的方法 pipeline 自动选择一组显式知识工具用于检测，并通过自我重写自适应调整提示结构。与现有最优方法不同，我们无需额外训练检测器，整个方法完全无需训练，只需对LVLM进行推理即可完成检测。为了支持我们的研究，我们还创建了一个新的基准数据集idfor，包含来自多种视频生成工具的高质量视频。实验结果表明，与现有最优基线模型相比，LAVID在四个SOTA LVLM上的F1分数提升了6.2%到30.2%。

> The impressive achievements of generative models in creating high-quality videos have raised concerns about digital integrity and privacy vulnerabilities. Recent works of AI-generated content detection have been widely studied in the image field (e.g., deepfake), yet the video field has been unexplored. Large Vision Language Model (LVLM) has become an emerging tool for AI-generated content detection for its strong reasoning and multimodal capabilities. It breaks the limitations of traditional deep learning based methods faced with like lack of transparency and inability to recognize new artifacts. Motivated by this, we propose LAVID, a novel LVLMs-based ai-generated video detection with explicit knowledge enhancement. Our insight list as follows: (1) The leading LVLMs can call external tools to extract useful information to facilitate its own video detection task; (2) Structuring the prompt can affect LVLM's reasoning ability to interpret information in video content. Our proposed pipeline automatically selects a set of explicit knowledge tools for detection, and then adaptively adjusts the structure prompt by self-rewriting. Different from prior SOTA that trains additional detectors, our method is fully training-free and only requires inference of the LVLM for detection. To facilitate our research, we also create a new benchmark \vidfor with high-quality videos generated from multiple sources of video generation tools. Evaluation results show that LAVID improves F1 scores by 6.2 to 30.2% over the top baselines on our datasets across four SOTA LVLMs.

[Arxiv](https://arxiv.org/abs/2502.14994)