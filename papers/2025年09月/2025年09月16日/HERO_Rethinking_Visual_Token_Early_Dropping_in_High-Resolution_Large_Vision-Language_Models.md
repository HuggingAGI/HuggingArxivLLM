# # HERO：重新思考高分辨率大型视觉语言模型中的视觉令牌早期丢弃

发布时间：2025年09月16日

`LLM应用` `基础理论`

> HERO: Rethinking Visual Token Early Dropping in High-Resolution Large Vision-Language Models

# 摘要

> 高分辨率大型视觉语言模型（HR-LVLMs）通过将高分辨率图像裁剪为局部图块并独立编码，展现出卓越的细粒度视觉理解能力。然而，这种分而治之的策略大幅增加了视觉标记数量，造成了可观的计算与内存负担。为了深入理解并应对这一挑战，我们实证研究了HR-LVLMs中视觉标记的利用情况，发现了三个关键结论：（1）局部图块的重要性各不相同，由视觉显著性和任务相关性共同决定；（2）基于CLIP的视觉编码器中的CLS标记在各层呈现两阶段注意力模式，每个阶段关注不同类型的视觉标记；（3）不同阶段被重点关注的视觉标记编码不同粒度的信息，在LVLMs中起到互补作用。基于这些发现，我们提出了HERO——一个高分辨率视觉标记早期丢弃框架，它融合了内容自适应的标记预算分配与功能感知的标记选择。通过准确估计图块级重要性并选择性保留具有互补作用的视觉标记，HERO在各类基准测试和模型规模下均实现了更优的效率-准确性平衡，且全程无需训练。本研究为HR-LVLMs的高效推理提供了实证依据与实用方案。

> By cropping high-resolution images into local tiles and encoding them independently, High-Resolution Large Vision-Language Models (HR-LVLMs) have demonstrated remarkable fine-grained visual understanding capabilities. However, this divide-and-conquer paradigm significantly increases the number of visual tokens, resulting in substantial computational and memory overhead. To better understand and address this challenge, we empirically investigate visual token utilization in HR-LVLMs and uncover three key findings: (1) the local tiles have varying importance, jointly determined by visual saliency and task relevance; (2) the CLS token in CLIP-based vision encoders exhibits a two-stage attention pattern across layers, with each stage attending to different types of visual tokens; (3) the visual tokens emphasized at different stages encode information at varying levels of granularity, playing complementary roles within LVLMs. Building on these insights, we propose HERO, a High-resolution visual token early dropping framework that integrates content-adaptive token budget allocation with function-aware token selection. By accurately estimating tile-level importance and selectively retaining visual tokens with complementary roles, HERO achieves superior efficiency-accuracy trade-offs across diverse benchmarks and model scales, all in a training-free manner. This study provides both empirical insights and practical solutions toward efficient inference in HR-LVLMs.

[Arxiv](https://arxiv.org/abs/2509.13067)