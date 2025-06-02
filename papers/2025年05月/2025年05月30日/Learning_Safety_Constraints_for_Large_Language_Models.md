# # 为大型语言模型学习安全约束

发布时间：2025年05月30日

`LLM理论` `人工智能安全` `对抗攻击`

> Learning Safety Constraints for Large Language Models

# 摘要

> 大型语言模型（LLMs）虽然强大，但其有害输出和易受对抗攻击的特性带来了显著的安全隐患。我们提出了一种名为SaP（Safety Polytope，安全多面体）的几何方法，它能够在模型的表示空间中直接学习和实施多种安全约束。通过多面体的面，我们开发了一个框架，能够识别安全与不安全的区域，并通过几何引导实现对不安全输出的检测与修正。与现有需要修改模型权重的方法不同，SaP在模型训练后于表示空间中进行操作，在保持模型原有能力的同时实施安全约束。实验结果表明，我们的方法能够有效识别不道德输入，降低对抗攻击的成功率，同时在标准任务上保持性能。这凸显了拥有明确几何安全模型的重要性。对学习到的多面体面的分析显示，模型在检测不同语义安全概念方面出现了专业化的现象，为理解大型语言模型表示空间中安全性如何被捕获提供了可解释的见解。


> Large language models (LLMs) have emerged as powerful tools but pose significant safety risks through harmful outputs and vulnerability to adversarial attacks. We propose SaP, short for Safety Polytope, a geometric approach to LLM safety that learns and enforces multiple safety constraints directly in the model's representation space. We develop a framework that identifies safe and unsafe regions via the polytope's facets, enabling both detection and correction of unsafe outputs through geometric steering. Unlike existing approaches that modify model weights, SaP operates post-hoc in the representation space, preserving model capabilities while enforcing safety constraints. Experiments across multiple LLMs demonstrate that our method can effectively detect unethical inputs, reduce adversarial attack success rates while maintaining performance on standard tasks, thus highlighting the importance of having an explicit geometric model for safety. Analysis of the learned polytope facets reveals emergence of specialization in detecting different semantic notions of safety, providing interpretable insights into how safety is captured in LLMs' representation space.

[Arxiv](https://arxiv.org/abs/2505.24445)