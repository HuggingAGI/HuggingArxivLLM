# 局部参数归属能否影响知识遗忘？对语言模型知识遗忘机制的深入研究.

发布时间：2025年05月22日

`LLM理论` `人工智能` `计算机科学`

> Does Localization Inform Unlearning? A Rigorous Examination of Local Parameter Attribution for Knowledge Unlearning in Language Models

# 摘要

> 大型语言模型常会意外保留某些内容，这引发了人们对知识遗忘技术的浓厚兴趣。近期研究主要集中在局部遗忘方法上，通过限制参数更新范围来实现目标知识的移除，同时保留无关的通用知识。然而，现有方法的有效性仍存疑，因为缺乏对遗忘目标间权衡的系统性评估。本文首先梳理了现有的局部遗忘技术，随后通过受控实验严格验证局部参数更新对遗忘的因果贡献。研究发现，实现有效遗忘所需的参数修改范围并非固定不变，这直接挑战了局部遗忘的核心假设，即参数的局部性必然反映知识移除效果。

> Large language models often retain unintended content, prompting growing interest in knowledge unlearning. Recent approaches emphasize localized unlearning, which restricts parameter updates to specific regions in an effort to remove target knowledge while preserving unrelated general knowledge. However, their effectiveness remains uncertain due to the lack of robust and thorough evaluation of the trade-off between the competing goals of unlearning. In this paper, we begin by revisiting existing localized unlearning approaches. We then conduct controlled experiments to rigorously evaluate whether local parameter updates causally contribute to unlearning. Our findings reveal that the set of parameters that must be modified for effective unlearning is not strictly determined, challenging the core assumption of localized unlearning that parameter locality is inherently indicative of effective knowledge removal.

[Arxiv](https://arxiv.org/abs/2505.16252)