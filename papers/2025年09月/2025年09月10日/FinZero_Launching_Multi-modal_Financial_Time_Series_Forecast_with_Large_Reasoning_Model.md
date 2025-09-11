# FinZero: 基于大型推理模型的多模态金融时间序列预测发布

发布时间：2025年09月10日

`LLM应用` `金融科技`

> FinZero: Launching Multi-modal Financial Time Series Forecast with Large Reasoning Model

# 摘要

> 金融时间序列预测既至关重要又极具挑战。以往方法通常会在将时间序列数据输入预测模型前进行标准化处理，但这种编码过程本质上会造成重要信息的损失。此外，过去的时间序列模型往往要求固定数量的变量或回溯窗口长度，这进一步制约了时间序列预测的可扩展性。同时，预测的可解释性与不确定性仍是亟待深入研究的方向，因为这些因素直接关系到预测的可靠性和实用价值。针对这些问题，我们首先构建了多样化金融图文数据集（FVLDB），并提出了不确定性调整组相对策略优化（UARPO）方法，让模型不仅能输出预测结果，还能对这些预测的不确定性进行分析。随后，我们开发了FinZero——一个经UARPO微调的多模态预训练模型，专门用于对FVLDB金融时间序列进行推理、预测与分析理解。大量实验表明，FinZero具备出色的适应性和可扩展性。经UARPO微调后，其在高置信度组的预测准确率较GPT-4o提升约13.48%，这验证了强化学习微调在多模态大模型中的有效性，尤其在金融时间序列预测任务中表现突出。

> Financial time series forecasting is both highly significant and challenging. Previous approaches typically standardized time series data before feeding it into forecasting models, but this encoding process inherently leads to a loss of important information. Moreover, past time series models generally require fixed numbers of variables or lookback window lengths, which further limits the scalability of time series forecasting. Besides, the interpretability and the uncertainty in forecasting remain areas requiring further research, as these factors directly impact the reliability and practical value of predictions. To address these issues, we first construct a diverse financial image-text dataset (FVLDB) and develop the Uncertainty-adjusted Group Relative Policy Optimization (UARPO) method to enable the model not only output predictions but also analyze the uncertainty of those predictions. We then proposed FinZero, a multimodal pre-trained model finetuned by UARPO to perform reasoning, prediction, and analytical understanding on the FVLDB financial time series. Extensive experiments validate that FinZero exhibits strong adaptability and scalability. After fine-tuning with UARPO, FinZero achieves an approximate 13.48\% improvement in prediction accuracy over GPT-4o in the high-confidence group, demonstrating the effectiveness of reinforcement learning fine-tuning in multimodal large model, including in financial time series forecasting tasks.

[Arxiv](https://arxiv.org/abs/2509.08742)