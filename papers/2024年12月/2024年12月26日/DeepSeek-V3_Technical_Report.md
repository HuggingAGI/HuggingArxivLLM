# DeepSeek-V3 技术报告

发布时间：2024年12月26日

`LLM理论` `大规模语言模型` `模型优化`

> DeepSeek-V3 Technical Report

# 摘要

> 我们很高兴推出DeepSeek-V3——一款拥有6710亿总参数的强劲专家混合模型（MoE），每个token激活370亿参数。为实现高效推理与经济训练，DeepSeek-V3采用了在DeepSeek-V2中经过充分验证的多头潜在注意力机制（MLA）和DeepSeekMoE架构。此外，它首次提出了一种无辅助损失的负载平衡策略，并设定了一个多token预测目标以提升性能。DeepSeek-V3在14.8万亿多样且高质量的token上完成预训练后，依次经历了监督微调和强化学习阶段，以充分释放其潜力。全面评估显示，DeepSeek-V3不仅超越了现有开源模型，更达到了与领先闭源模型相当的水平。尽管性能卓越，其完整训练仅需278.8万个H800 GPU小时。更值得一提的是，整个训练过程极为稳定，未出现任何不可恢复的损失激增或回滚操作。模型检查点已开源，访问https://github.com/deepseek-ai/DeepSeek-V3即可获取。

> We present DeepSeek-V3, a strong Mixture-of-Experts (MoE) language model with 671B total parameters with 37B activated for each token. To achieve efficient inference and cost-effective training, DeepSeek-V3 adopts Multi-head Latent Attention (MLA) and DeepSeekMoE architectures, which were thoroughly validated in DeepSeek-V2. Furthermore, DeepSeek-V3 pioneers an auxiliary-loss-free strategy for load balancing and sets a multi-token prediction training objective for stronger performance. We pre-train DeepSeek-V3 on 14.8 trillion diverse and high-quality tokens, followed by Supervised Fine-Tuning and Reinforcement Learning stages to fully harness its capabilities. Comprehensive evaluations reveal that DeepSeek-V3 outperforms other open-source models and achieves performance comparable to leading closed-source models. Despite its excellent performance, DeepSeek-V3 requires only 2.788M H800 GPU hours for its full training. In addition, its training process is remarkably stable. Throughout the entire training process, we did not experience any irrecoverable loss spikes or perform any rollbacks. The model checkpoints are available at https://github.com/deepseek-ai/DeepSeek-V3.

[Arxiv](https://arxiv.org/abs/2412.19437)