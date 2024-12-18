# 具有设备端小型和远程大型语言模型的不确定性感知混合推理

发布时间：2024年12月17日

`LLM应用` `移动设备` `语言模型`

> Uncertainty-Aware Hybrid Inference with On-Device Small and Remote Large Language Models

# 摘要

> 这篇论文探讨了一种混合语言模型（HLM）架构，它把在移动设备上运行的小型语言模型（SLM）和无线网络基站（BS）托管的大型语言模型（LLM）整合起来。HLM 的令牌生成遵循推测推理原则：SLM 的词汇分布上传至 LLM，LLM 要么接受要么拒绝，被拒令牌由 LLM 重新采样。虽说这种方式保证了 SLM 和 LLM 的词汇分布一致，可因上行传输及运行两个语言模型的计算成本，令牌吞吐量不高。为应对此问题，我们提出一种新型的 HLM 结构，名为不确定性感知 HLM（U-HLM），其中 SLM 在本地衡量其输出的不确定性，对于可能被接受的令牌，跳过上行传输和 LLM 操作。这种选择性跳过得益于我们的经验发现，即 SLM 的不确定性与 LLM 的拒绝概率存在线性关联。我们通过分析得出不确定性阈值，并评估其预期拒绝风险。模拟显示，U-HLM 减少了 45.93%的上行传输和 LLM 计算，同时达到了 LLM 高达 97.54%的推理准确率，令牌吞吐量比不跳过的 HLM 快 2.54 倍。

> This paper studies a hybrid language model (HLM) architecture that integrates a small language model (SLM) operating on a mobile device with a large language model (LLM) hosted at the base station (BS) of a wireless network. The HLM token generation process follows the speculative inference principle: the SLM's vocabulary distribution is uploaded to the LLM, which either accepts or rejects it, with rejected tokens being resampled by the LLM. While this approach ensures alignment between the vocabulary distributions of the SLM and LLM, it suffers from low token throughput due to uplink transmission and the computation costs of running both language models. To address this, we propose a novel HLM structure coined Uncertainty-aware HLM (U-HLM), wherein the SLM locally measures its output uncertainty, and skips both uplink transmissions and LLM operations for tokens that are likely to be accepted. This opportunistic skipping is enabled by our empirical finding of a linear correlation between the SLM's uncertainty and the LLM's rejection probability. We analytically derive the uncertainty threshold and evaluate its expected risk of rejection. Simulations show that U-HLM reduces uplink transmissions and LLM computation by 45.93%, while achieving up to 97.54% of the LLM's inference accuracy and 2.54$\times$ faster token throughput than HLM without skipping.

[Arxiv](https://arxiv.org/abs/2412.12687)