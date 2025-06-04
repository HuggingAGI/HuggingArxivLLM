# RATFM：用于异常检测的增强时间序列基础模型

发布时间：2025年06月02日

`RAG` `异常检测` `时间序列分析`

> RATFM: Retrieval-augmented Time Series Foundation Model for Anomaly Detection

# 摘要

> 受大型语言模型 (LLMs) 在自然语言处理领域取得的成功启发，近期研究开始探索构建时间序列基础模型，并将其应用于预测、分类和异常检测等任务。然而，这些模型在不同领域和任务中的表现差异显著。在基于 LLM 的方法中，由于重新训练成本高昂，测试时适应方法（基于示例的提示）逐渐成为主流。在我们研究关注的异常检测领域，提供目标领域的正常示例同样能够取得良好效果。然而，时间序列基础模型并未自然获得解释或利用示例或指令的能力，因为时间序列数据的特性并未鼓励模型发展这种能力。为解决这一限制，我们提出了一种检索增强的时间序列基础模型 (RATFM)，使预训练的时间序列基础模型能够整合测试时适应的示例。实验表明，RATFM 的性能与领域内微调相当，同时避免了依赖领域的微调过程。在包含九个领域的多领域数据集 UCR 异常存档上的实验，进一步验证了我们提出方法的有效性。

> Inspired by the success of large language models (LLMs) in natural language processing, recent research has explored the building of time series foundation models and applied them to tasks such as forecasting, classification, and anomaly detection. However, their performances vary between different domains and tasks. In LLM-based approaches, test-time adaptation using example-based prompting has become common, owing to the high cost of retraining. In the context of anomaly detection, which is the focus of this study, providing normal examples from the target domain can also be effective. However, time series foundation models do not naturally acquire the ability to interpret or utilize examples or instructions, because the nature of time series data used during training does not encourage such capabilities. To address this limitation, we propose a retrieval augmented time series foundation model (RATFM), which enables pretrained time series foundation models to incorporate examples of test-time adaptation. We show that RATFM achieves a performance comparable to that of in-domain fine-tuning while avoiding domain-dependent fine-tuning. Experiments on the UCR Anomaly Archive, a multi-domain dataset including nine domains, confirms the effectiveness of the proposed approach.

[Arxiv](https://arxiv.org/abs/2506.02081)