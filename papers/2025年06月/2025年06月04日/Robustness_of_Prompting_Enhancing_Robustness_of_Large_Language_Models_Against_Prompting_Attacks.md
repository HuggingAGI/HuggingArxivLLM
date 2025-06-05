# 提升模型鲁棒性：增强大型语言模型抵御提示攻击的能力

发布时间：2025年06月04日

`LLM应用` `认知科学` `人工智能`

> Robustness of Prompting: Enhancing Robustness of Large Language Models Against Prompting Attacks

# 摘要

> 大型语言模型（LLMs）通过巧妙运用提示策略，在各类任务中表现卓越。然而，这些模型对输入扰动极为敏感，如打字错误或字符顺序的轻微变化，都会显著影响性能。尽管提示技术不断进步，但如何设计一种能有效缓解这些扰动负面影响的提示策略仍是一个未解难题。为解决这一问题，我们提出了一种全新策略——提示鲁棒性（RoP），专为提升LLMs的稳健性而设计。RoP包含两个核心阶段：错误纠正与引导。在错误纠正阶段，RoP通过生成多样化的对抗示例并构建自动纠错提示，帮助模型识别并修正输入中的错误。在引导阶段，RoP基于修正后的输入生成优化引导提示，有效提升模型推理的稳健性和准确性。通过在算术、常识推理和逻辑推理等任务上的全面实验，我们验证了RoP在增强LLMs对抗扰动鲁棒性方面的显著效果。值得注意的是，与理想输入场景相比，RoP仅导致轻微性能下降，这充分证明了其在实际应用中作为增强LLMs鲁棒性方法的实用价值和有效性。

> Large Language Models (LLMs) have demonstrated remarkable performance across various tasks by effectively utilizing a prompting strategy. However, they are highly sensitive to input perturbations, such as typographical errors or slight character order errors, which can substantially degrade their performance. Despite advances in prompting techniques, developing a prompting strategy that explicitly mitigates the negative impact of such perturbations remains an open challenge. To bridge this gap, we propose Robustness of Prompting (RoP), a novel prompting strategy specifically designed to enhance the robustness of LLMs. RoP consists of two stages: Error Correction and Guidance. In the Error Correction stage, RoP applies diverse perturbation methods to generate adversarial examples, which are then used to construct prompts that automatically correct input errors. In the Guidance stage, RoP generates an optimal guidance prompting based on the corrected input, steering the model toward more robust and accurate inferences. Through comprehensive experiments spanning arithmetic, commonsense, and logical reasoning tasks, we demonstrate that RoP significantly improves LLMs' robustness against adversarial perturbations. Notably, it maintains model accuracy with only minimal degradation compared to clean input scenarios, thereby establishing RoP as a practical and effective approach for enhancing LLM robustness in real-world applications.

[Arxiv](https://arxiv.org/abs/2506.03627)