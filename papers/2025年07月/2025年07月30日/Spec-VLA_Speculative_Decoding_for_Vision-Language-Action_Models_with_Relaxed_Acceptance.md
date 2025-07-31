# Spec-VLA：针对视觉-语言-动作模型的推测性解码方法，通过宽松接受机制实现

发布时间：2025年07月30日

`LLM应用` `人工智能` `机器人学`

> Spec-VLA: Speculative Decoding for Vision-Language-Action Models with Relaxed Acceptance

# 摘要

> 视觉-语言-动作（VLA）模型在视觉语言模型（VLMs）的强大能力驱动下取得了长足的进步。然而，VLMs的庞大参数规模和自回归（AR）解码特性为VLA模型带来了巨大的计算挑战。尽管Speculative Decoding（SD）通过高效的草稿生成和并行验证加速了大型语言模型（LLMs），并能在一次前向传播中生成多个标记，但其在VLA模型中的应用尚未被探索。本研究提出了一种名为Spec-VLA的SD框架，旨在加速VLA模型。由于动作预测任务的复杂性和VLA模型的贪婪解码机制，直接将先进的SD框架应用于VLA预测任务仅能带来有限的速度提升。为提升生成效率，我们提出了一种基于VLA模型中动作标记相对距离的有效机制，用于放宽接受条件。实验结果表明，Spec-VLA框架在多种测试场景中均表现出色，与OpenVLA基线相比，接受长度提升了44%，速度提升了1.42倍，同时保持了成功率。这一成果凸显了Speculative Execution在VLA预测任务中的广阔应用前景。

> Vision-Language-Action (VLA) models have made substantial progress by leveraging the robust capabilities of Visual Language Models (VLMs). However, VLMs' significant parameter size and autoregressive (AR) decoding nature impose considerable computational demands on VLA models. While Speculative Decoding (SD) has shown efficacy in accelerating Large Language Models (LLMs) by incorporating efficient drafting and parallel verification, allowing multiple tokens to be generated in one forward pass, its application to VLA models remains unexplored. This work introduces Spec-VLA, an SD framework designed to accelerate VLA models. Due to the difficulty of the action prediction task and the greedy decoding mechanism of the VLA models, the direct application of the advanced SD framework to the VLA prediction task yields a minor speed improvement. To boost the generation speed, we propose an effective mechanism to relax acceptance utilizing the relative distances represented by the action tokens of the VLA model. Empirical results across diverse test scenarios affirm the effectiveness of the Spec-VLA framework, and further analysis substantiates the impact of our proposed strategies, which enhance the acceptance length by 44%, achieving 1.42 times speedup compared with the OpenVLA baseline, without compromising the success rate. The success of the Spec-VLA framework highlights the potential for broader application of speculative execution in VLA prediction scenarios.

[Arxiv](https://arxiv.org/abs/2507.22424)