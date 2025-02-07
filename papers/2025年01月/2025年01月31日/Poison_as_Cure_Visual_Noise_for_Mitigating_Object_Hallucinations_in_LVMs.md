# 以毒攻毒：视觉噪声助力缓解大型视觉模型中的物体幻觉

发布时间：2025年01月31日

`LLM应用

**理由**：该论文主要讨论了如何通过视觉对抗扰动（VAP）方法来缓解大型视觉语言模型（LVMs）中的对象幻觉问题。虽然涉及视觉信息处理，但其核心仍然是关于如何改进和优化LLM在实际应用中的表现，特别是针对视觉信息的处理。因此，将其归类为LLM应用是合适的。` `计算机视觉` `人工智能`

> Poison as Cure: Visual Noise for Mitigating Object Hallucinations in LVMs

# 摘要

> 大型视觉语言模型（LVMs）通过视觉感知能力扩展了LLMs，使其能够处理和解释视觉信息。然而，对象幻觉问题严重影响了其可靠性，即LVMs可能生成看似合理但实际上不准确的信息。为此，我们提出了一种新颖的视觉对抗扰动（VAP）方法，通过战略优化的视觉噪声来缓解LVM幻觉，而无需改变基础模型。我们的方法将幻觉抑制视为一个优化问题，利用对抗策略生成有益的视觉扰动，增强模型的事实基础并减少参数知识偏差。大量实验结果表明，该方法在8个最先进的LVMs中持续减少了对象幻觉，验证了其在各种评估中的有效性。

> Large vision-language models (LVMs) extend large language models (LLMs) with visual perception capabilities, enabling them to process and interpret visual information. A major challenge compromising their reliability is object hallucination that LVMs may generate plausible but factually inaccurate information. We propose a novel visual adversarial perturbation (VAP) method to mitigate this hallucination issue. VAP alleviates LVM hallucination by applying strategically optimized visual noise without altering the base model. Our approach formulates hallucination suppression as an optimization problem, leveraging adversarial strategies to generate beneficial visual perturbations that enhance the model's factual grounding and reduce parametric knowledge bias. Extensive experimental results demonstrate that our method consistently reduces object hallucinations across 8 state-of-the-art LVMs, validating its efficacy across diverse evaluations.

[Arxiv](https://arxiv.org/abs/2501.19164)