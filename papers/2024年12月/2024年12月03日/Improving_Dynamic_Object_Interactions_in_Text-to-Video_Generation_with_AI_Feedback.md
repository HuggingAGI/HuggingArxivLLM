# 利用人工智能反馈提升文本到视频生成中的动态对象交互

发布时间：2024年12月03日

`LLM应用` `人工智能`

> Improving Dynamic Object Interactions in Text-to-Video Generation with AI Feedback

# 摘要

> 大型文本到视频模型在众多下游应用中潜力巨大。然而，这些模型在准确描绘动态对象的相互作用方面存在困难，常常导致运动不真实，频繁违背现实世界的物理规律。受大型语言模型启发，一个解决方案是利用外部反馈让生成的输出与期望结果相符。如此一来，模型能够自主优化响应，无需大量手动收集数据。在本项工作中，我们探究了运用反馈来强化文本到视频模型中的对象动态。我们想要解答一个关键问题：何种反馈与哪些特定的自我改进算法搭配，能最有效地改进文本与视频的对齐以及真实的对象相互作用？首先，我们为文本到视频模型的离线 RL 微调推导出一个统一的概率目标。这一视角凸显了现有算法中的设计元素，如 KL 正则化和策略投影，如何在统一框架内成为特定选择。接着，我们使用推导得出的方法来优化一组文本 - 视频对齐指标（比如 CLIP 分数、光流），但发现它们常常与人类对生成质量的感知不符。为解决这一限制，我们提议借助视觉语言模型提供更精细的反馈，专门针对视频中的对象动态。我们的实验表明，我们的方法能够有效优化各类奖励，其中二进制 AI 反馈在动态交互的视频质量方面带来了最为显著的提升，这一点得到了 AI 和人类评估的证实。值得注意的是，在使用源自 AI 反馈的奖励信号时，我们观察到了显著的成效，特别是在涉及多个对象之间复杂交互以及对象掉落的真实描绘等场景中。

> Large text-to-video models hold immense potential for a wide range of downstream applications. However, these models struggle to accurately depict dynamic object interactions, often resulting in unrealistic movements and frequent violations of real-world physics. One solution inspired by large language models is to align generated outputs with desired outcomes using external feedback. This enables the model to refine its responses autonomously, eliminating extensive manual data collection. In this work, we investigate the use of feedback to enhance the object dynamics in text-to-video models. We aim to answer a critical question: what types of feedback, paired with which specific self-improvement algorithms, can most effectively improve text-video alignment and realistic object interactions? We begin by deriving a unified probabilistic objective for offline RL finetuning of text-to-video models. This perspective highlights how design elements in existing algorithms like KL regularization and policy projection emerge as specific choices within a unified framework. We then use derived methods to optimize a set of text-video alignment metrics (e.g., CLIP scores, optical flow), but notice that they often fail to align with human perceptions of generation quality. To address this limitation, we propose leveraging vision-language models to provide more nuanced feedback specifically tailored to object dynamics in videos. Our experiments demonstrate that our method can effectively optimize a wide variety of rewards, with binary AI feedback driving the most significant improvements in video quality for dynamic interactions, as confirmed by both AI and human evaluations. Notably, we observe substantial gains when using reward signals derived from AI feedback, particularly in scenarios involving complex interactions between multiple objects and realistic depictions of objects falling.

[Arxiv](https://arxiv.org/abs/2412.02617)