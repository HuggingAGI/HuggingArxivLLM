# DynMoLE：借助混合路由机制，提升 LoRA 专家混合微调的效果

发布时间：2025年04月01日

`LLM理论` `参数高效微调`

> DynMoLE: Boosting Mixture of LoRA Experts Fine-Tuning with a Hybrid Routing Mechanism

# 摘要

> 基于指令的大型语言模型（LLMs）微调在NLP任务中表现卓越。参数高效微调（PEFT）方法，如LoRA专家混合模型（MoLE），结合了LoRA的高效性和MoE的灵活性，展现出显著潜力。然而，现有MoLE路由机制存在计算效率与预测准确性的权衡问题，且难以满足不同Transformer层对多样化专家选择的需求。因此，我们提出了DynMoLE，这是一种基于路由器概率分布的Tsallis熵的动态混合路由策略。通过动态调整专家选择，DynMoLE降低了路由器的不确定性，提升了稳定性，并促进了更均衡的专家参与，从而实现了更快的收敛速度和更优的模型性能。此外，我们引入了一种基于Tsallis熵的辅助损失函数，进一步引导模型向更低不确定性方向收敛，从而改善了训练稳定性和性能。实验结果表明，DynMoLE较LoRA提升了9.6%，超越了现有最优方法MoLA 2.3%。我们还进行了全面的消融实验，以评估DynMoLE关键组件的贡献。

> Instruction-based fine-tuning of large language models (LLMs) has achieved remarkable success in various natural language processing (NLP) tasks. Parameter-efficient fine-tuning (PEFT) methods, such as Mixture of LoRA Experts (MoLE), combine the efficiency of Low-Rank Adaptation (LoRA) with the versatility of Mixture of Experts (MoE) models, demonstrating significant potential for handling multiple downstream tasks. However, the existing routing mechanisms for MoLE often involve a trade-off between computational efficiency and predictive accuracy, and they fail to fully address the diverse expert selection demands across different transformer layers. In this work, we propose DynMoLE, a hybrid routing strategy that dynamically adjusts expert selection based on the Tsallis entropy of the router's probability distribution. This approach mitigates router uncertainty, enhances stability, and promotes more equitable expert participation, leading to faster convergence and improved model performance. Additionally, we introduce an auxiliary loss based on Tsallis entropy to further guide the model toward convergence with reduced uncertainty, thereby improving training stability and performance. Our extensive experiments on commonsense reasoning benchmarks demonstrate that DynMoLE achieves substantial performance improvements, outperforming LoRA by 9.6% and surpassing the state-of-the-art MoLE method, MoLA, by 2.3%. We also conduct a comprehensive ablation study to evaluate the contributions of DynMoLE's key components.

[Arxiv](https://arxiv.org/abs/2504.00661)