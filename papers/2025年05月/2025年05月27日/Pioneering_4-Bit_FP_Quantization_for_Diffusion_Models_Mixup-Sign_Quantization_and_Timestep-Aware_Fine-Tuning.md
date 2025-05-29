# 开创性的4位浮点量化技术专为扩散模型打造：混合符号量化与时间步敏感微调

发布时间：2025年05月27日

`LLM应用

理由：这篇论文主要探讨了扩散模型的模型量化技术，特别是4位浮点量化方法，旨在提升模型的内存效率和推理速度。虽然论文中提到了大型语言模型的启发，但其核心内容是关于扩散模型的优化，属于模型应用和优化的范畴，因此归类为LLM应用。` `机器学习` `生成模型`

> Pioneering 4-Bit FP Quantization for Diffusion Models: Mixup-Sign Quantization and Timestep-Aware Fine-Tuning

# 摘要

> 模型量化通过降低权重和激活的位宽，显著提升了扩散模型的内存效率和推理速度。然而，实现4位量化仍是一项具有挑战性的任务。现有的基于整数量化和训练后量化微调的方法在性能一致性上表现欠佳。受大型语言模型中浮点（FP）量化成功案例的启发，我们探索了扩散模型的低比特FP量化，并识别出三个关键挑战：带符号FP量化无法有效处理不对称的激活分布，微调过程中对去噪过程中的时间复杂性考虑不足，以及微调损失与量化误差之间的不匹配。为应对这些挑战，我们提出了混合符号浮点量化（MSFP）框架，首次在模型量化中引入无符号FP量化，同时结合了感知时间步的LoRA（TALoRA）和去噪因子损失对齐（DFA），以确保精准且稳定的微调。通过大量实验，我们成功实现了扩散模型中首个优异的4位FP量化性能，超越了现有4位整数量化PTQ微调方法的表现。


> Model quantization reduces the bit-width of weights and activations, improving memory efficiency and inference speed in diffusion models. However, achieving 4-bit quantization remains challenging. Existing methods, primarily based on integer quantization and post-training quantization fine-tuning, struggle with inconsistent performance. Inspired by the success of floating-point (FP) quantization in large language models, we explore low-bit FP quantization for diffusion models and identify key challenges: the failure of signed FP quantization to handle asymmetric activation distributions, the insufficient consideration of temporal complexity in the denoising process during fine-tuning, and the misalignment between fine-tuning loss and quantization error. To address these challenges, we propose the mixup-sign floating-point quantization (MSFP) framework, first introducing unsigned FP quantization in model quantization, along with timestep-aware LoRA (TALoRA) and denoising-factor loss alignment (DFA), which ensure precise and stable fine-tuning. Extensive experiments show that we are the first to achieve superior performance in 4-bit FP quantization for diffusion models, outperforming existing PTQ fine-tuning methods in 4-bit INT quantization.

[Arxiv](https://arxiv.org/abs/2505.21591)