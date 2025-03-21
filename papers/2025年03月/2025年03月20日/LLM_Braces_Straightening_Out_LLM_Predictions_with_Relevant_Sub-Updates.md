# LLM校准器：借助相关子更新优化模型预测

发布时间：2025年03月20日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）内部结构的前馈层，提出了一种新的方法LLMBRACES，用于优化模型的预测过程和控制生成特性。研究主要集中在模型的内部机制和优化策略上，属于对LLM的理论研究。` `文本生成`

> LLM Braces: Straightening Out LLM Predictions with Relevant Sub-Updates

# 摘要

> 最近的研究发现，基于 Transformer 的大型语言模型 (LLM) 中的大部分知识编码在其前馈 (FFN) 层中，每个 FNN 层可以被解释为子更新的总和，每个子更新对应于 FFN 价值参数矩阵中的一个加权列向量，这些向量通常编码人类可解释的概念。基于这一发现，我们假设通过根据输入或目标输出风格的相关性调节这些子更新的贡献，可以进一步提升和控制模型的性能和行为。因此，我们提出了 LLMBRACES，这是一种新颖且高效的方法，能够计算与 FFN 层中价值向量相关联的相关性得分，并利用这些得分动态调整子更新的贡献。通过优化子更新的贡献，LLMBRACES 改进了预测过程，从而生成更准确和可靠的输出，就像一个提供支持和稳定性的“支架”。此外，LLMBRACES 还可以扩展以支持对生成特性（如情感）的条件控制，从而实现对 LLM 输出的精细调控。在包括 Qwen2.5-1.5B、Llama2-7B 和 Llama3-8B 在内的多种 LLM 上进行的广泛实验表明，与基线方法相比，LLMBRACES 在微调和零样本设置下均表现出更优的性能，同时所需的可调参数数量显著减少，最多可减少 75% 相较于 LoRA。此外，LLMBRACES 在情感控制生成和毒性减少方面表现出色，凸显了其在各种应用场景中实现灵活、可控文本生成的潜力。

> Recent findings reveal that much of the knowledge in a Transformer-based Large Language Model (LLM) is encoded in its feed-forward (FFN) layers, where each FNN layer can be interpreted as the summation of sub-updates, each corresponding to a weighted column vector from the FFN's value parameter matrix that often encodes human-interpretable concepts. In light of this, we hypothesize that model performance and behaviors can be further enhanced and controlled by modulating the contributions of these sub-updates based on their relevance to the input or target output style, and propose LLMBRACES, a novel and efficient method that computes relevance scores associated with value vectors in FFN layers and leverages these scores to dynamically adjust the contribution of sub-updates. By optimizing sub-update contributions, LLMBRACES refines the prediction process, leading to more accurate and reliable outputs, much like a 'brace' providing support and stability. Moreover, LLMBRACES can be extended to support conditional control over generation characteristics, such as sentiment, thereby offering fine-grained steering of LLM outputs. Extensive experiments on various LLMs-including Qwen2.5-1.5B, Llama2-7B, and Llama3-8B-demonstrate that LLMBRACES outperforms baseline approaches in both fine-tuning and zero-shot settings while requiring significantly fewer tunable parameters, up to 75% fewer compared to LoRA. Furthermore, LLMBRACES excels in sentiment-controlled generation and toxicity reduction, highlighting its potential for flexible, controlled text generation across applications.

[Arxiv](https://arxiv.org/abs/2503.16334)