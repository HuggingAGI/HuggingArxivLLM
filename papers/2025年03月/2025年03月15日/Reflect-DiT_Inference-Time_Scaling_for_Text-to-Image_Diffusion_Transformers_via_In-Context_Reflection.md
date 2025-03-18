# Reflect-DiT：基于上下文反思的文本到图像扩散变换器推理时间扩展

发布时间：2025年03月15日

`LLM应用` `人工智能` `计算机视觉`

> Reflect-DiT: Inference-Time Scaling for Text-to-Image Diffusion Transformers via In-Context Reflection

# 摘要

> 文本到图像生成的发展主要依赖于训练时间扩展，即通过更大规模的数据和更强的计算资源训练更大型的模型。尽管这种方法有效，但其高昂的计算成本促使人们开始关注通过推理时间扩展来提升性能。当前，文本到图像扩散模型的推理时间扩展主要局限于最佳N选一采样方法，即每个提示生成多张图像，再由选择模型挑选最优输出。受近期语言领域DeepSeek-R1等推理模型的成功启发，我们提出了一种替代简单最佳N选一采样的方法，通过为文本到图像扩散变换器模型赋予上下文反思能力。我们提出了Reflect-DiT方法，该方法使扩散变换器能够利用之前生成图像的上下文示例以及描述必要改进的文本反馈来优化生成效果。与被动依赖随机采样并寄希望于未来生成更好结果不同，Reflect-DiT会针对性地调整生成内容，以改进需要增强的特定方面。实验结果显示，使用SANA-1.0-1.6B作为基础模型时，Reflect-DiT在GenEval基准测试中的性能提升了0.19。此外，它在仅生成每个提示20个样本的情况下，达到了GenEval的新最先进水平0.81，超过了采用更大模型（SANA-1.5-4.8B）在最佳N选一方法下生成2048个样本所获得的0.80分。

> The predominant approach to advancing text-to-image generation has been training-time scaling, where larger models are trained on more data using greater computational resources. While effective, this approach is computationally expensive, leading to growing interest in inference-time scaling to improve performance. Currently, inference-time scaling for text-to-image diffusion models is largely limited to best-of-N sampling, where multiple images are generated per prompt and a selection model chooses the best output. Inspired by the recent success of reasoning models like DeepSeek-R1 in the language domain, we introduce an alternative to naive best-of-N sampling by equipping text-to-image Diffusion Transformers with in-context reflection capabilities. We propose Reflect-DiT, a method that enables Diffusion Transformers to refine their generations using in-context examples of previously generated images alongside textual feedback describing necessary improvements. Instead of passively relying on random sampling and hoping for a better result in a future generation, Reflect-DiT explicitly tailors its generations to address specific aspects requiring enhancement. Experimental results demonstrate that Reflect-DiT improves performance on the GenEval benchmark (+0.19) using SANA-1.0-1.6B as a base model. Additionally, it achieves a new state-of-the-art score of 0.81 on GenEval while generating only 20 samples per prompt, surpassing the previous best score of 0.80, which was obtained using a significantly larger model (SANA-1.5-4.8B) with 2048 samples under the best-of-N approach.

[Arxiv](https://arxiv.org/abs/2503.12271)