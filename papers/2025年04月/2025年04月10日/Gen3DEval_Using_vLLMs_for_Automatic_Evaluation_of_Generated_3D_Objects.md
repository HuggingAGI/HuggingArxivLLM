# Gen3DEval：使用视觉大型语言模型实现生成三维对象的自动评估

发布时间：2025年04月10日

`LLM应用` `计算机图形学` `3D生成`

> Gen3DEval: Using vLLMs for Automatic Evaluation of Generated 3D Objects

# 摘要

> 文本到3D生成技术突飞猛进，亟需与人类判断高度契合的稳健、可扩展评估指标。现有指标如PSNR和CLIP因依赖真实数据或仅关注提示保真度而难以满足需求。为此，我们推出Gen3DEval——基于视觉大型语言模型（vLLMs）的创新评估框架，专为3D物体质量评估优化。通过分析3D表面法线，Gen3DEval无需真实数据对比即可评估文本保真度、外观和表面质量，成功弥合自动化指标与用户偏好之间的鸿沟。相比现有任务无关模型，Gen3DEval在用户对齐评估中表现更优，成为未来文本到3D生成研究的全面且便捷基准。了解更多请访问项目页面：\href{https://shalini-maiti.github.io/gen3deval.github.io/}{https://shalini-maiti.github.io/gen3deval.github.io/}。

> Rapid advancements in text-to-3D generation require robust and scalable evaluation metrics that align closely with human judgment, a need unmet by current metrics such as PSNR and CLIP, which require ground-truth data or focus only on prompt fidelity. To address this, we introduce Gen3DEval, a novel evaluation framework that leverages vision large language models (vLLMs) specifically fine-tuned for 3D object quality assessment. Gen3DEval evaluates text fidelity, appearance, and surface quality by analyzing 3D surface normals, without requiring ground-truth comparisons, bridging the gap between automated metrics and user preferences. Compared to state-of-the-art task-agnostic models, Gen3DEval demonstrates superior performance in user-aligned evaluations, placing it as a comprehensive and accessible benchmark for future research on text-to-3D generation. The project page can be found here: \href{https://shalini-maiti.github.io/gen3deval.github.io/}{https://shalini-maiti.github.io/gen3deval.github.io/}.

[Arxiv](https://arxiv.org/abs/2504.08125)