# Skip-Vision：加速视觉语言模型的全方位框架

发布时间：2025年03月26日

`LLM应用

理由：这篇论文讨论了基于Transformer的多模态大语言模型在扩展时的计算效率问题，并提出了Skip-Vision框架来优化训练和推理过程。虽然它涉及模型的优化，但更偏向于应用层面的改进，而非理论探讨。因此，归类为LLM应用。` `计算机视觉` `计算机体系结构`

> Skip-Vision: A Comprehensive Framework for Accelerating Vision-Language Models

# 摘要

> 基于Transformer的模型推动了多模态大语言模型（MLLMs）的显著进展，然而当扩展分辨率、训练数据和模型参数时，其计算成本急剧上升。这一问题的主要瓶颈源于实现图像精细理解所需视觉标记的激增。我们提出Skip-Vision，这是一个统一的框架，旨在解决视觉语言模型中的训练和推理低效问题。在传统的标记压缩方法基础上，我们的方法引入了两种互补的加速策略。在训练加速方面，我们发现视觉标记上的前馈网络（FFN）计算只会带来微小的特征更新。这促使我们提出了Skip-FFN策略，该策略跳过了冗余视觉标记的FFN层。在推理加速方面，我们设计了一种选择性KV缓存移除机制，该机制在解码过程中剪枝了跳过的键值对，同时保持了模型性能。实验结果表明，Skip-Vision将训练时间减少了35%，推理FLOPs减少了75%，延迟减少了45%，同时达到了与现有方法相当或更优的性能。我们的工作为实现高效扩展高性能MLLMs提供了一种切实可行的解决方案。

> Transformer-based models have driven significant advancements in Multimodal Large Language Models (MLLMs), yet their computational costs surge drastically when scaling resolution, training data, and model parameters. A key bottleneck stems from the proliferation of visual tokens required for fine-grained image understanding. We propose Skip-Vision, a unified framework addressing both training and inference inefficiencies in vision-language models. On top of conventional token compression approaches, our method introduces two complementary acceleration strategies. For training acceleration, we observe that Feed-Forward Network (FFN) computations on visual tokens induce marginal feature updates. This motivates our Skip-FFN strategy, which bypasses FFN layers for redundant visual tokens. For inference acceleration, we design a selective KV-cache removal mechanism that prunes the skipped key-value pairs during decoding while preserving model performance. Experimental results demonstrate that Skip-Vision reduces training time by up to 35\%, inference FLOPs by 75\%, and latency by 45\%, while achieving comparable or superior performance to existing methods. Our work provides a practical solution for scaling high-performance MLLMs with enhanced efficiency.

[Arxiv](https://arxiv.org/abs/2503.21817)