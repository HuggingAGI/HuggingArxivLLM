# 本研究提出了一种新颖方法，利用分布性逆偏优化技术，在没有人工标注的正样本情况下也能实现对齐效果。这种方法巧妙地“消除负例”，突破了以往依赖正样本的局限。

发布时间：2024年03月05日

`LLM应用`

> Negating Negatives: Alignment without Human Positive Samples via Distributional Dispreference Optimization

# 摘要

> LLMs 已颠覆了 AI 的角色，但也潜藏传播不道德内容的风险。为引导 LLMs 更符合人类偏好，对齐技术应运而生并日渐受到重视。然而，现有的对齐方法过于依赖高质量的正负样本对，易受噪声标签干扰，且难以精准区分优选和非优选响应数据。鉴于 LLMs 最近在生成有益回复上的卓越表现，本研究创新聚焦于仅使用人工标注的负面样本达成对齐效果，力求在保留回复的有益性的同时降低其潜在危害。为此，我们提出了“分布型逆偏优化”（D$^2$O）技术，通过最大化生成回复与非优选回复之间的差距，有效地剔除有害信息。理论上，D$^2$O 等同于构建一个针对负向回复分布的人类逆偏好分布模型，而非单个实例的偏好模型。此外，D$^2$O 还巧妙地融入了隐式杰弗里散度正则化机制，在训练中平衡了参照策略的利用与探索，并确保在训练过程中趋于非负值。大量实验验证了该方法在生成质量上能与最新基准比肩，而且在输出更少有害、更多有价值信息的回复时，不仅稳定性更高，而且收敛速度更快。

> Large language models (LLMs) have revolutionized the role of AI, yet also pose potential risks of propagating unethical content. Alignment technologies have been introduced to steer LLMs towards human preference, gaining increasing attention. Despite notable breakthroughs in this direction, existing methods heavily rely on high-quality positive-negative training pairs, suffering from noisy labels and the marginal distinction between preferred and dispreferred response data. Given recent LLMs' proficiency in generating helpful responses, this work pivots towards a new research focus: achieving alignment using solely human-annotated negative samples, preserving helpfulness while reducing harmfulness. For this purpose, we propose Distributional Dispreference Optimization (D$^2$O), which maximizes the discrepancy between the generated responses and the dispreferred ones to effectively eschew harmful information. We theoretically demonstrate that D$^2$O is equivalent to learning a distributional instead of instance-level preference model reflecting human dispreference against the distribution of negative responses. Besides, D$^2$O integrates an implicit Jeffrey Divergence regularization to balance the exploitation and exploration of reference policies and converges to a non-negative one during training. Extensive experiments demonstrate that our method achieves comparable generation quality and surpasses the latest baselines in producing less harmful and more informative responses with better training stability and faster convergence.

[Arxiv](https://arxiv.org/abs/2403.03419)