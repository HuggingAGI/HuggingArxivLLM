# 多模态大型语言模型的高效参数合并方法，结合互补参数调整

发布时间：2025年02月24日

`LLM理论

理由：这篇论文探讨了模型微调和合并的方法，特别是参数高效微调和模型合并的理论分析，属于大型语言模型（LLM）的训练和优化理论。` `机器学习` `人工智能`

> Parameter Efficient Merging for Multimodal Large Language Models with Complementary Parameter Adaptation

# 摘要

> 使用自定义数据微调预训练模型，能够生成众多在特定任务上表现卓越的专家模型。将这些模型合并成一个通用模型以实现多任务能力且避免数据泄漏的方法日益受到关注。随着数据和模型规模的不断扩大，参数高效微调已成为获取任务特定模型的常见实践。然而，我们发现现有为全量微调设计的模型合并方法在高效微调下表现不佳。为了解决这些问题，我们从低秩分解的角度进行分析，发现保持方向一致性并补偿奇异值之间的差距对于高效模型合并至关重要。基于此，我们提出了CoPA-Merging，这是一种无需训练的参数高效合并方法，通过互补参数适配来优化模型性能。具体来说，我们通过参数间关系进行参数剪裁并构建缩放系数，以补偿任务干扰导致的性能下降；同时，我们执行跨任务归一化以增强对未见任务的泛化能力。我们建立了一个包含多样化多模态任务的基准测试集，并在该基准上进行实验，以验证我们方法的卓越性能和泛化能力。进一步的研究和详细分析进一步证明了该方法的有效性。

> Fine-tuning pre-trained models with custom data leads to numerous expert models on specific tasks. Merging models into one universal model to empower multi-task ability refraining from data leakage has gained popularity. With the expansion in data and model size, parameter efficient tuning becomes the common practice for obtaining task-specific models efficiently. However, we observe that existing methods designed for full fine-tuning merging fail under efficient tuning. To address the issues, we analyze from low-rank decomposition and reveal that maintaining direction and compensating for gap between singular values are crucial for efficient model merging. Consequently, we propose CoPA-Merging, a training-free parameter efficient merging method with complementary parameter adaptation. Specifically, we (1) prune parameters and construct scaling coefficients from inter-parameter relation to compensate for performance drop from task interference and (2) perform cross-task normalization to enhance unseen task generalization. We establish a benchmark consisting of diverse multimodal tasks, on which we conduct experiments to certificate the outstanding performance and generalizability of our method. Additional study and extensive analyses further showcase the effectiveness.

[Arxiv](https://arxiv.org/abs/2502.17159)