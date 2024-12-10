# LLM-BIP：采用块级前向重要性传播的大型语言模型结构化剪枝

发布时间：2024年12月09日

`LLM应用` `计算机` `人工智能`

> LLM-BIP: Structured Pruning for Large Language Models with Block-Wise Forward Importance Propagation

# 摘要

> 大型语言模型（LLMs）在各类语言任务中表现抢眼，然而其庞大的规模和高昂的计算成本阻碍了广泛应用。结构剪枝是一项常用技术，能在预训练模型中引入稀疏性，通过去除冗余连接（如通道和注意力头之类的结构分组参数），在推理时实现直接硬件加速。现有的结构剪枝方法多采用全局或逐层的剪枝标准；但由于对连接重要性评估不准确，效果不佳。全局剪枝方法通常借助近乎零且不可靠的梯度来评估组件重要性，而逐层剪枝方法则面临显著的剪枝误差累积问题。为此，我们提出了一种基于块级重要性得分传播的更精确的剪枝指标，叫做 LLM-BIP。具体来说，LLM-BIP 通过衡量连接对相应变压器块输出的影响来精确评估连接重要性，这可通过从 Lipschitz 连续性假设得出的上限在单次前向传播中高效近似。我们用 LLaMA-7B、Vicuna-7B 和 LLaMA-13B 在常见的零样本任务中对所提方法进行评估。结果显示，与之前的最优基线相比，我们的方法在常见推理任务中的准确率平均提高 3.26％。在 WikiText2 数据集和 PTB 数据集上，它还分别平均降低了 14.09 和 68.76 的困惑度。

> Large language models (LLMs) have demonstrated remarkable performance across various language tasks, but their widespread deployment is impeded by their large size and high computational costs. Structural pruning is a prevailing technique used to introduce sparsity into pre-trained models and facilitate direct hardware acceleration during inference by removing redundant connections (structurally-grouped parameters), such as channels and attention heads. Existing structural pruning approaches often employ either global or layer-wise pruning criteria; however, they are hindered by ineffectiveness stemming from inaccurate evaluation of connection importance. Global pruning methods typically assess component importance using near-zero and unreliable gradients, while layer-wise pruning approaches encounter significant pruning error accumulation issues. To this end, we propose a more accurate pruning metric based on the block-wise importance score propagation, termed LLM-BIP. Specifically, LLM-BIP precisely evaluates connection importance by gauging its influence on the respective transformer block output, which can be efficiently approximated in a single forward pass through an upper bound derived from the assumption of Lipschitz continuity. We evaluate the proposed method using LLaMA-7B, Vicuna-7B, and LLaMA-13B across common zero-shot tasks. The results demonstrate that our approach achieves an average of 3.26% increase in accuracy for common reasoning tasks compared to previous best baselines. It also reduces perplexity by 14.09 and 68.76 on average for the WikiText2 dataset and PTB dataset, respectively.

[Arxiv](https://arxiv.org/abs/2412.06419)