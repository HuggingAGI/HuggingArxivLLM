# DyePack：利用后门在LLM中可验证标记测试集污染

发布时间：2025年05月28日

`其他` `模型评估` `模型安全`

> DyePack: Provably Flagging Test Set Contamination in LLMs Using Backdoors

# 摘要

> 开放基准测试是评估和推进大型语言模型的关键工具，为模型提供了可重复性和透明性保障。然而，其开放性也使其成为测试集污染的潜在目标。本研究引入了DyePack框架，该框架通过后门攻击技术，无需访问模型的损失值、logits或任何内部细节，即可识别在训练过程中使用了基准测试集的模型。就像银行将染色包与现金混合以标记抢劫者一样，DyePack通过将后门样本与测试数据混合，成功标记了那些使用过这些数据进行训练的模型。我们提出了一种结合多个后门和随机目标的原理化设计，能够在标记每个模型时精确计算误报率（FPR），从而确保不会错误地指控模型，同时为每个检测到的污染案例提供有力证据。我们在三个数据集上对五个模型进行了全面评估，涵盖了多项选择题和开放生成任务。对于多项选择题，DyePack使用八个后门成功检测到了所有被污染的模型，在MMLU-Pro和Big-Bench-Hard上的误报率分别低至0.000073%和0.000017%。对于开放生成任务，DyePack在Alpaca数据集上表现优异，仅使用六个后门就识别出了所有被污染的模型，误报率仅为0.127%。

> Open benchmarks are essential for evaluating and advancing large language models, offering reproducibility and transparency. However, their accessibility makes them likely targets of test set contamination. In this work, we introduce DyePack, a framework that leverages backdoor attacks to identify models that used benchmark test sets during training, without requiring access to the loss, logits, or any internal details of the model. Like how banks mix dye packs with their money to mark robbers, DyePack mixes backdoor samples with the test data to flag models that trained on it. We propose a principled design incorporating multiple backdoors with stochastic targets, enabling exact false positive rate (FPR) computation when flagging every model. This provably prevents false accusations while providing strong evidence for every detected case of contamination. We evaluate DyePack on five models across three datasets, covering both multiple-choice and open-ended generation tasks. For multiple-choice questions, it successfully detects all contaminated models with guaranteed FPRs as low as 0.000073% on MMLU-Pro and 0.000017% on Big-Bench-Hard using eight backdoors. For open-ended generation tasks, it generalizes well and identifies all contaminated models on Alpaca with a guaranteed false positive rate of just 0.127% using six backdoors.

[Arxiv](https://arxiv.org/abs/2505.23001)