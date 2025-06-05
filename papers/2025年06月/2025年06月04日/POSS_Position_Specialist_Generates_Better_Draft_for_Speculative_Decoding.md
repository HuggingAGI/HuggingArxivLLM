# # POSS: 位置专家生成更优草稿，助力推测性解码

发布时间：2025年06月04日

`LLM应用` `模型优化` `推理加速`

> POSS: Position Specialist Generates Better Draft for Speculative Decoding

# 摘要

> 推测解码通过结合小型草稿模型预测多标记与大型目标模型并行验证的机制，显著提升了大型语言模型（LLM）推理速度。近期研究通过利用目标模型的隐藏状态，有效提升了草稿模型的预测精度。然而，现有方法在后续位置上面临草稿模型预测质量下降的难题，其原因在于草稿模型生成特征中的误差累积。本文提出位置专家（PosS），其由多个针对特定位置的草稿层组成，能够精准生成分配的标记。通过让每个位置专家专注于处理特定级别的草稿模型特征偏差，PosS显著提升了后续位置在每轮草稿生成中的标记接受率。在Llama-3-8B-Instruct和Llama-2-13B-chat模型上，跨越六个数据集的实验结果表明，与基线方法相比，PosS在平均接受长度和加速比方面均实现了显著提升。我们的代码库已开源，地址为https://github.com/shrango/PosS。

> Speculative decoding accelerates Large Language Model (LLM) inference by using a small draft model to predict multiple tokens, and a large target model to verify these tokens in parallel. Recent studies leverage the hidden state of the target model to enhance draft model prediction accuracy. However, existing methods suffer from the degrading quality of draft token predictions at later positions, due to error accumulation in draft model generated features. In this paper, we propose Position Specialists (PosS), which consist of multiple position-specialized draft layers to generate tokens at assigned position(s). Position specialists greatly improve token acceptance rate at later positions per drafting round, as each specialist only needs to focus on handling a certain level of draft model feature deviation. Experiment results on Llama-3-8B-Instruct and Llama-2-13B-chat across six datasets demonstrate that PosS effectively improves over baselines on average acceptance length and speed-up ratio. Our codebase is available at https://github.com/shrango/PosS.

[Arxiv](https://arxiv.org/abs/2506.03566)