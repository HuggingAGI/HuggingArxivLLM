# Tarsier2：从细节描述到全面理解，推动大型视觉-语言模型的飞跃

发布时间：2025年01月14日

`LLM应用

**理由**：这篇论文主要介绍了一个名为Tarsier2的大型视觉语言模型（LVLM），并详细描述了其在视频描述和视频理解任务中的应用和性能提升。论文的重点在于模型的优化和应用效果，属于LLM在实际任务中的应用，因此分类为LLM应用。` `视频生成` `视频理解`

> Tarsier2: Advancing Large Vision-Language Models from Detailed Video Description to Comprehensive Video Understanding

# 摘要

> 我们推出了Tarsier2，这是一款顶尖的大型视觉语言模型（LVLM），专为生成精准详尽的视频描述而设计，同时具备卓越的通用视频理解能力。Tarsier2通过三大升级实现显著突破：（1）预训练数据从1100万扩展至4000万视频-文本对，大幅提升数据量与多样性；（2）在监督微调中实现细粒度时间对齐；（3）采用基于模型的采样自动构建偏好数据，并应用DPO训练进行优化。大量实验表明，Tarsier2-7B在视频描述任务中持续超越GPT-4o和Gemini 1.5 Pro等领先专有模型。在DREAM-1K基准测试中，Tarsier2-7B的F1分数分别比GPT-4o和Gemini-1.5-Pro高出2.8%和5.8%。在人类并行评估中，Tarsier2-7B的性能优势分别达到+8.6%和+24.9%。此外，Tarsier2-7B在15个公共基准测试中刷新了多项记录，涵盖视频问答、视频定位、幻觉测试和具身问答等任务，充分展现了其作为全能视觉语言模型的强大实力。

> We introduce Tarsier2, a state-of-the-art large vision-language model (LVLM) designed for generating detailed and accurate video descriptions, while also exhibiting superior general video understanding capabilities. Tarsier2 achieves significant advancements through three key upgrades: (1) Scaling pre-training data from 11M to 40M video-text pairs, enriching both volume and diversity; (2) Performing fine-grained temporal alignment during supervised fine-tuning; (3) Using model-based sampling to automatically construct preference data and applying DPO training for optimization. Extensive experiments show that Tarsier2-7B consistently outperforms leading proprietary models, including GPT-4o and Gemini 1.5 Pro, in detailed video description tasks. On the DREAM-1K benchmark, Tarsier2-7B improves F1 by 2.8\% over GPT-4o and 5.8\% over Gemini-1.5-Pro. In human side-by-side evaluations, Tarsier2-7B shows a +8.6\% performance advantage over GPT-4o and +24.9\% over Gemini-1.5-Pro. Tarsier2-7B also sets new state-of-the-art results across 15 public benchmarks, spanning tasks such as video question-answering, video grounding, hallucination test, and embodied question-answering, demonstrating its versatility as a robust generalist vision-language model.

[Arxiv](https://arxiv.org/abs/2501.07888)