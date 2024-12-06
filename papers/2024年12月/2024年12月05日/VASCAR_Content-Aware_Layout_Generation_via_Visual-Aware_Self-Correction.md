# VASCAR：借助视觉感知自校正实现内容感知布局生成

发布时间：2024年12月05日

`LLM应用` `布局生成` `多模态`

> VASCAR: Content-Aware Layout Generation via Visual-Aware Self-Correction

# 摘要

> 大型语言模型（LLMs）因能生成诸如 HTML 或 JSON 这样的结构描述语言，即便没有视觉信息也能有效用于布局生成。近来，LLM 供应商已将这些模型发展成大型视觉语言模型（LVLM），其展现出突出的多模态理解能力。那么，我们怎样借助这种多模态能力来进行布局生成呢？为回答此问题，我们提出了用于基于 LVLM 的内容感知布局生成的视觉感知自校正布局生成（VASCAR）。在我们的方法中，LVLMs 参照渲染的布局图像进行迭代优化输出，这些图像在海报背景上以彩色边框的形式呈现。在实验中，我们表明我们的方法与 Gemini 相结合。无需任何额外训练，VASCAR 就达到了最先进（SOTA）的布局生成质量，超越了现有的特定布局生成模型和其他基于 LLM 的方法。

> Large language models (LLMs) have proven effective for layout generation due to their ability to produce structure-description languages, such as HTML or JSON, even without access to visual information. Recently, LLM providers have evolved these models into large vision-language models (LVLM), which shows prominent multi-modal understanding capabilities. Then, how can we leverage this multi-modal power for layout generation? To answer this, we propose Visual-Aware Self-Correction LAyout GeneRation (VASCAR) for LVLM-based content-aware layout generation. In our method, LVLMs iteratively refine their outputs with reference to rendered layout images, which are visualized as colored bounding boxes on poster backgrounds. In experiments, we demonstrate that our method combined with the Gemini. Without any additional training, VASCAR achieves state-of-the-art (SOTA) layout generation quality outperforming both existing layout-specific generative models and other LLM-based methods.

[Arxiv](https://arxiv.org/abs/2412.04237)