# 基于优化大型语言模型的时间序列预测，用于配电电网绝缘子的故障预测。

发布时间：2025年02月24日

`LLM应用

论文摘要：本研究提出了一种结合大语言模型（LLM）的时间序列预测方法，用于预测高压绝缘子的漏电流增加。该方法通过混合深度学习模型，利用LLM进行预测，并结合优化方法和输入滤波器来提高预测精度。实验结果表明，优化后的LLM在不同时间范围内的预测误差均低于现有模型。` `电力系统` `设备监测`

> Time series forecasting based on optimized LLM for fault prediction in distribution power grid insulators

# 摘要

> 绝缘子表面污染会导致漏电流逐渐增加，最终可能引发放电并造成系统停电。为减少停电风险，监测污染和漏电流有助于预测故障发展。针对这一需求，本文提出了一种用于预测高压绝缘子漏电流增加的混合深度学习（DL）模型。该模型结合了基于树形Parzen估计的多准则优化方法和信号噪声衰减的输入滤波器，并利用大语言模型（LLM）进行时间序列预测。实验结果表明，优化后的LLM在短期预测中均方根误差为【数学公式】，中期预测中为【数学公式】，优于现有DL模型。

> Surface contamination on electrical grid insulators leads to an increase in leakage current until an electrical discharge occurs, which can result in a power system shutdown. To mitigate the possibility of disruptive faults resulting in a power outage, monitoring contamination and leakage current can help predict the progression of faults. Given this need, this paper proposes a hybrid deep learning (DL) model for predicting the increase in leakage current in high-voltage insulators. The hybrid structure considers a multi-criteria optimization using tree-structured Parzen estimation, an input stage filter for signal noise attenuation combined with a large language model (LLM) applied for time series forecasting. The proposed optimized LLM outperforms state-of-the-art DL models with a root-mean-square error equal to 2.24$\times10^{-4}$ for a short-term horizon and 1.21$\times10^{-3}$ for a medium-term horizon.

[Arxiv](https://arxiv.org/abs/2502.17341)