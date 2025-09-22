# 分布对齐解码：助力LLM高效任务适配

发布时间：2025年09月19日

`LLM理论` `基础理论`

> Distribution-Aligned Decoding for Efficient LLM Task Adaptation

# 摘要

> 即使用上参数高效微调（PEFT），要让数十亿参数的语言模型适配下游任务，成本依旧高昂。为此，我们把任务适配重新定义为输出分布对齐——核心目标是在解码时直接引导模型输出分布向任务分布靠拢，而非通过权重更新间接调整。基于这一思路，我们提出了引导向量解码（Steering Vector Decoding, SVD）——一种轻量级、兼容PEFT且理论扎实的新方法。具体而言，我们先进行简短的热启动微调，再从热启动模型与预训练模型的输出分布间提取Kullback-Leibler（KL）散度梯度，进而得到任务感知引导向量。接着，用这个引导向量指导解码过程，精准调控模型输出分布向任务分布对齐。理论上，我们证明SVD与全量微调的梯度更新一阶等价，还推导出了引导向量强度的全局最优解。在三个任务、九个基准测试中，SVD与四种主流PEFT方法搭配使用后，多项选择准确率最高提升5个百分点，开放式任务的真实性提升2个百分点，常识数据集上也有1-2个百分点的改善——关键是，除了PEFT适配器，全程无需额外添加可训练参数。如此一来，SVD就为大型语言模型铺就了一条轻量、理论扎实的高效任务适配新路径。

> Adapting billion-parameter language models to a downstream task is still costly, even with parameter-efficient fine-tuning (PEFT). We re-cast task adaptation as output-distribution alignment: the objective is to steer the output distribution toward the task distribution directly during decoding rather than indirectly through weight updates. Building on this view, we introduce Steering Vector Decoding (SVD), a lightweight, PEFT-compatible, and theoretically grounded method. We start with a short warm-start fine-tune and extract a task-aware steering vector from the Kullback-Leibler (KL) divergence gradient between the output distribution of the warm-started and pre-trained models. This steering vector is then used to guide the decoding process to steer the model's output distribution towards the task distribution. We theoretically prove that SVD is first-order equivalent to the gradient step of full fine-tuning and derive a globally optimal solution for the strength of the steering vector. Across three tasks and nine benchmarks, SVD paired with four standard PEFT methods improves multiple-choice accuracy by up to 5 points and open-ended truthfulness by 2 points, with similar gains (1-2 points) on commonsense datasets without adding trainable parameters beyond the PEFT adapter. SVD thus offers a lightweight, theoretically grounded path to stronger task adaptation for large language models.

[Arxiv](https://arxiv.org/abs/2509.15888)