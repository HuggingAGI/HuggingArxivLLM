# 从反思到完美：通过反射调优，扩展文本到图像扩散模型的推理时间优化

发布时间：2025年04月22日

`其他` `计算机视觉` `生成模型`

> From Reflection to Perfection: Scaling Inference-Time Optimization for Text-to-Image Diffusion Models via Reflection Tuning

# 摘要

> 文本到图像扩散模型通过扩展训练数据和模型规模取得了卓越的视觉效果，但在复杂场景和细节处理上仍有不足。受大型语言模型自我反思能力的启发，我们提出ReflectionFlow框架，使扩散模型在推理阶段能够迭代反思并优化输出。该框架引入三个互补扩展维度：噪声级缩放优化潜在空间初始化，提示级缩放提供精准语义指导，以及反思级缩放通过明确反馈迭代改进生成结果。为支持这一创新，我们构建了包含100万组数据的GenRef数据集，每组包含反思、有缺陷图像及优化图像。基于此，我们在FLUX.1-dev模型上实现了高效的反思调优，统一建模多模态输入。实验表明，ReflectionFlow显著超越传统噪声级缩放方法，为复杂任务中的高质量图像生成提供了高效解决方案。


> Recent text-to-image diffusion models achieve impressive visual quality through extensive scaling of training data and model parameters, yet they often struggle with complex scenes and fine-grained details. Inspired by the self-reflection capabilities emergent in large language models, we propose ReflectionFlow, an inference-time framework enabling diffusion models to iteratively reflect upon and refine their outputs. ReflectionFlow introduces three complementary inference-time scaling axes: (1) noise-level scaling to optimize latent initialization; (2) prompt-level scaling for precise semantic guidance; and most notably, (3) reflection-level scaling, which explicitly provides actionable reflections to iteratively assess and correct previous generations. To facilitate reflection-level scaling, we construct GenRef, a large-scale dataset comprising 1 million triplets, each containing a reflection, a flawed image, and an enhanced image. Leveraging this dataset, we efficiently perform reflection tuning on state-of-the-art diffusion transformer, FLUX.1-dev, by jointly modeling multimodal inputs within a unified framework. Experimental results show that ReflectionFlow significantly outperforms naive noise-level scaling methods, offering a scalable and compute-efficient solution toward higher-quality image synthesis on challenging tasks.

[Arxiv](https://arxiv.org/abs/2504.16080)