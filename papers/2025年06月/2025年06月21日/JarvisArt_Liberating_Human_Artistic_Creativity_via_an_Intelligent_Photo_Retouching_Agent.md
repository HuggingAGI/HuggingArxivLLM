# JarvisArt：借助智能修图助手，释放人类的艺术创造力

发布时间：2025年06月21日

`Agent` `图像处理` `人工智能`

> JarvisArt: Liberating Human Artistic Creativity via an Intelligent Photo Retouching Agent

# 摘要

> 图像修饰已成为当代视觉叙事的重要组成部分，使用户能够捕捉美学并表达创造力。尽管Adobe Lightroom等专业工具功能强大，但它们需要大量专业知识和手动操作。相比之下，现有的AI解决方案虽然提供了自动化，但通常缺乏调整性和泛化能力，无法满足多样化的个性化编辑需求。为了解决这一差距，我们引入了JarvisArt，这是一个由多模态大型语言模型（MLLM）驱动的智能体，能够理解用户意图，模拟专业艺术家的推理过程，并在Lightroom中智能协调超过200种修饰工具。JarvisArt采用两阶段训练流程：首先进行基于思维链的监督微调以建立基本推理和工具使用技能，随后通过基于组相对策略优化的修饰方法（GRPO-R）进一步提升其决策能力和工具熟练度。我们还提出了Agent-to-Lightroom协议，以实现与Lightroom的无缝集成。为了评估性能，我们开发了MMArt-Bench，这是一个基于真实用户编辑构建的新基准。JarvisArt展示了用户友好的交互、优越的泛化能力以及对全局和局部调整的精细控制，为智能图像修饰开辟了新途径。值得注意的是，在MMArt-Bench上，它在内容保真度的平均像素级指标上比GPT-4o高出60%，同时保持了相当的指令遵循能力。项目页面：https://jarvisart.vercel.app/。

> Photo retouching has become integral to contemporary visual storytelling, enabling users to capture aesthetics and express creativity. While professional tools such as Adobe Lightroom offer powerful capabilities, they demand substantial expertise and manual effort. In contrast, existing AI-based solutions provide automation but often suffer from limited adjustability and poor generalization, failing to meet diverse and personalized editing needs. To bridge this gap, we introduce JarvisArt, a multi-modal large language model (MLLM)-driven agent that understands user intent, mimics the reasoning process of professional artists, and intelligently coordinates over 200 retouching tools within Lightroom. JarvisArt undergoes a two-stage training process: an initial Chain-of-Thought supervised fine-tuning to establish basic reasoning and tool-use skills, followed by Group Relative Policy Optimization for Retouching (GRPO-R) to further enhance its decision-making and tool proficiency. We also propose the Agent-to-Lightroom Protocol to facilitate seamless integration with Lightroom. To evaluate performance, we develop MMArt-Bench, a novel benchmark constructed from real-world user edits. JarvisArt demonstrates user-friendly interaction, superior generalization, and fine-grained control over both global and local adjustments, paving a new avenue for intelligent photo retouching. Notably, it outperforms GPT-4o with a 60% improvement in average pixel-level metrics on MMArt-Bench for content fidelity, while maintaining comparable instruction-following capabilities. Project Page: https://jarvisart.vercel.app/.

[Arxiv](https://arxiv.org/abs/2506.17612)