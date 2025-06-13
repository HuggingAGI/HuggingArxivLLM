# CreatiPoster：致力于可编辑且可控的多层图形设计的生成

发布时间：2025年06月12日

`LLM应用` `图形设计`

> CreatiPoster: Towards Editable and Controllable Multi-Layer Graphic Design Generation

# 摘要

> 图形设计在商业和个人领域都发挥着重要作用，但创建高质量、可编辑且美观的图形作品仍然是一个耗时费力的任务，尤其是对于初学者而言。现有的AI工具虽然能够自动化部分工作流程，但难以准确整合用户提供的素材、保持可编辑性以及达到专业视觉效果。商用系统如Canva Magic Design依赖庞大的模板库，这在实际应用中并不现实。本文中，我们介绍了一个名为CreatiPoster的框架，它能够根据可选的自然语言指令或素材生成可编辑的多层图形作品。首先，一个协议模型（RGBA大模态模型）会生成一个JSON规范，详细描述每一层（文字或素材）的精确布局、层次、内容和样式，同时包含一个简洁的背景提示。接着，一个条件背景模型根据生成的前景层合成一个连贯的背景。我们构建了一个用于图形设计生成的基准测试集，并通过自动化指标证明，CreatiPoster超越了现有的开源方法和专有商业系统。为了促进进一步研究，我们发布了一个无版权限制的10万个多层设计数据集。CreatiPoster支持多种应用场景，包括画布编辑、文字叠加、响应式缩放、多语言适配和动态海报制作，推动了AI辅助图形设计的普及。项目主页：https://github.com/graphic-design-ai/creatiposter

> Graphic design plays a crucial role in both commercial and personal contexts, yet creating high-quality, editable, and aesthetically pleasing graphic compositions remains a time-consuming and skill-intensive task, especially for beginners. Current AI tools automate parts of the workflow, but struggle to accurately incorporate user-supplied assets, maintain editability, and achieve professional visual appeal. Commercial systems, like Canva Magic Design, rely on vast template libraries, which are impractical for replicate. In this paper, we introduce CreatiPoster, a framework that generates editable, multi-layer compositions from optional natural-language instructions or assets. A protocol model, an RGBA large multimodal model, first produces a JSON specification detailing every layer (text or asset) with precise layout, hierarchy, content and style, plus a concise background prompt. A conditional background model then synthesizes a coherent background conditioned on this rendered foreground layers. We construct a benchmark with automated metrics for graphic-design generation and show that CreatiPoster surpasses leading open-source approaches and proprietary commercial systems. To catalyze further research, we release a copyright-free corpus of 100,000 multi-layer designs. CreatiPoster supports diverse applications such as canvas editing, text overlay, responsive resizing, multilingual adaptation, and animated posters, advancing the democratization of AI-assisted graphic design. Project homepage: https://github.com/graphic-design-ai/creatiposter

[Arxiv](https://arxiv.org/abs/2506.10890)