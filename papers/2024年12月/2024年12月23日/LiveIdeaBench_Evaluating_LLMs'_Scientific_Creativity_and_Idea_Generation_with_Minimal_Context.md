# LiveIdeaBench：以最少的上下文来评估大型语言模型的科学创造力和想法生成能力

发布时间：2024年12月23日

`LLM应用` `评估框架`

> LiveIdeaBench: Evaluating LLMs' Scientific Creativity and Idea Generation with Minimal Context

# 摘要

> 虽然大型语言模型（LLMs）在科学任务方面表现出色，但现有的评估框架多凭借丰富的上下文输入评估其性能，而忽视了它们从少量信息生成新想法的能力。我们推出了 LiveIdeaBench，这一综合基准通过单关键字提示来衡量 LLMs 的科学创造力与发散思维能力。依据 Guilford 的创造力理论，我们的框架运用一组动态的前沿 LLMs，从原创性、可行性、流畅性和灵活性这四个关键维度评估所生成的想法。通过针对 18 个科学领域的 1180 个关键字对 20 个领先模型展开广泛实验，我们发现科学创造能力与一般智力指标有着显著不同的模式。特别值得一提的是，我们的结果显示，像 QwQ-32B-preview 这类模型的创意表现与 o1-preview 等顶级模型相当，尽管它们在一般智力得分上差距明显。这些发现凸显了针对科学创造力的专门评估框架的重要性，也表明 LLMs 中创造力的发展可能与传统解决问题的能力遵循不同的路径。

> While Large Language Models (LLMs) have demonstrated remarkable capabilities in scientific tasks, existing evaluation frameworks primarily assess their performance using rich contextual inputs, overlooking their ability to generate novel ideas from minimal information. We introduce LiveIdeaBench, a comprehensive benchmark that evaluates LLMs' scientific creativity and divergent thinking capabilities using single-keyword prompts. Drawing from Guilford's creativity theory, our framework employs a dynamic panel of state-of-the-art LLMs to assess generated ideas across four key dimensions: originality, feasibility, fluency, and flexibility. Through extensive experimentation with 20 leading models across 1,180 keywords spanning 18 scientific domains, we reveal that scientific creative ability shows distinct patterns from general intelligence metrics. Notably, our results demonstrate that models like QwQ-32B-preview achieve comparable creative performance to top-tier models like o1-preview, despite significant gaps in their general intelligence scores. These findings highlight the importance of specialized evaluation frameworks for scientific creativity and suggest that the development of creative capabilities in LLMs may follow different trajectories than traditional problem-solving abilities.

[Arxiv](https://arxiv.org/abs/2412.17596)