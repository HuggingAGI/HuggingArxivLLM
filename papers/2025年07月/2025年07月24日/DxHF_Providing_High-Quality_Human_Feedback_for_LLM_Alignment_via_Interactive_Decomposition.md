# DxHF：通过交互式分解，为 LLM 对齐提供高质量的人类反馈

发布时间：2025年07月24日

`LLM应用` `人机交互` `用户体验工程`

> DxHF: Providing High-Quality Human Feedback for LLM Alignment via Interactive Decomposition

# 摘要

> 人类偏好是通过强化学习从人类反馈（RLHF）等方法对齐大型语言模型（LLMs）的重要依据。然而，现有的用户界面要求标注人员比较文本段落，这在处理长篇或不熟悉的文本时颇具挑战性。本文探讨了分解原则作为提升LLM对齐中人类反馈质量的方法。这种方法将文本分解为单独的主张，而非直接比较长篇文本响应。基于此，我们开发了新颖的用户界面DxHF。它通过展示分解后的主张、视觉编码主张与对话的相关性以及链接相似主张，优化了比较流程。这使用户能够快速浏览关键信息，精准识别差异，从而做出更高效、更准确的判断。我们的技术评估表明，分解通常能提高反馈与真实情况的一致性，尤其是对存在不确定性的用户而言。一项由160名参与者参与的众包研究显示，使用DxHF可将反馈准确性平均提高5%，尽管它使平均反馈时间增加了18秒。值得注意的是，在用户不确定性较低的情况下，准确性显著更高。该研究结果突显了HCI作为提升人机对齐的有效方法的潜力。

> Human preferences are widely used to align large language models (LLMs) through methods such as reinforcement learning from human feedback (RLHF). However, the current user interfaces require annotators to compare text paragraphs, which is cognitively challenging when the texts are long or unfamiliar. This paper contributes by studying the decomposition principle as an approach to improving the quality of human feedback for LLM alignment. This approach breaks down the text into individual claims instead of directly comparing two long-form text responses. Based on the principle, we build a novel user interface DxHF. It enhances the comparison process by showing decomposed claims, visually encoding the relevance of claims to the conversation and linking similar claims. This allows users to skim through key information and identify differences for better and quicker judgment. Our technical evaluation shows evidence that decomposition generally improves feedback accuracy regarding the ground truth, particularly for users with uncertainty. A crowdsourcing study with 160 participants indicates that using DxHF improves feedback accuracy by an average of 5%, although it increases the average feedback time by 18 seconds. Notably, accuracy is significantly higher in situations where users have less certainty. The finding of the study highlights the potential of HCI as an effective method for improving human-AI alignment.

[Arxiv](https://arxiv.org/abs/2507.18802)