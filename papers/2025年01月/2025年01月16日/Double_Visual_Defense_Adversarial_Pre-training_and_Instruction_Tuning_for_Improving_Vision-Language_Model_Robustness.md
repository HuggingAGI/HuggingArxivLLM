# 双重视觉防御：对抗性预训练与指令调优，增强视觉-语言模型的鲁棒性

发布时间：2025年01月16日

`LLM应用

**理由**：这篇论文主要讨论了视觉语言模型在对抗性视觉扰动下的鲁棒性，并提出了一种新的防御策略。虽然涉及到对抗性训练和模型优化，但其核心仍然是关于如何应用和改进现有的视觉语言模型（如CLIP和LLaVA）以增强其在实际应用中的鲁棒性。因此，这篇论文应归类为LLM应用。` `计算机视觉`

> Double Visual Defense: Adversarial Pre-training and Instruction Tuning for Improving Vision-Language Model Robustness

# 摘要

> 本文探讨了视觉语言模型对抗对抗性视觉扰动的鲁棒性，并提出了一种创新的“双重视觉防御”策略。与以往依赖预训练CLIP模型轻量级对抗微调的方法不同，我们利用网络规模数据，从头进行大规模对抗性视觉语言预训练。随后，通过引入对抗性视觉指令调优，进一步强化了防御能力。由此产生的模型$Δ$CLIP和$Δ^2$LLaVA，在零-shot鲁棒性上显著提升，为视觉语言模型的对抗性防御树立了新标杆。例如，$Δ$CLIP在ImageNet-1k上的对抗性鲁棒性较之前最佳模型提升了约20%。同样，$Δ^2$LLaVA在图像描述任务中实现了约30%的鲁棒性提升，在视觉问答任务中提升了约20%。此外，与基线模型相比，我们的模型在零-shot识别能力、减少幻觉及推理性能方面均表现出色。项目详情请访问https://doublevisualdefense.github.io/。

> This paper investigates the robustness of vision-language models against adversarial visual perturbations and introduces a novel ``double visual defense" to enhance this robustness. Unlike previous approaches that resort to lightweight adversarial fine-tuning of a pre-trained CLIP model, we perform large-scale adversarial vision-language pre-training from scratch using web-scale data. We then strengthen the defense by incorporating adversarial visual instruction tuning. The resulting models from each stage, $Δ$CLIP and $Δ^2$LLaVA, show substantially enhanced zero-shot robustness and set a new state-of-the-art in adversarial defense for vision-language models. For example, the adversarial robustness of $Δ$CLIP surpasses that of the previous best models on ImageNet-1k by ~20%. %For example, $Δ$CLIP surpasses the previous best models on ImageNet-1k by ~20% in terms of adversarial robustness. Similarly, compared to prior art, $Δ^2$LLaVA brings a ~30% robustness improvement to image captioning task and a ~20% robustness improvement to visual question answering task. Furthermore, our models exhibit stronger zero-shot recognition capability, fewer hallucinations, and superior reasoning performance compared to baselines. Our project page is https://doublevisualdefense.github.io/.

[Arxiv](https://arxiv.org/abs/2501.09446)