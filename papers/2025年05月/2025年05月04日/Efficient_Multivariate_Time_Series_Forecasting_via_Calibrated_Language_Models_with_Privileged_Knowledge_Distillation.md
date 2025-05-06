# 高效多元时间序列预测：校准语言模型与特权知识蒸馏结合

发布时间：2025年05月04日

`LLM应用`

> Efficient Multivariate Time Series Forecasting via Calibrated Language Models with Privileged Knowledge Distillation

# 摘要

> 多变量时间序列预测 (MTSF) 旨在利用历史数据预测未来的观测值，在时间序列数据管理中发挥着重要作用。随着大型语言模型 (LLMs) 的发展，近期研究通过文本提示微调将 LLMs 的知识注入到 MTSF 中。然而，LLMs 在推理阶段的低效性一直是部署中的难题。为此，我们提出了 TimeKD，一个高效的 MTSF 框架，结合校准语言模型和特权知识蒸馏技术。TimeKD 通过跨模态教师模型生成高质量的未来表示，并培养高效的预测模型。该教师模型采用带有真实提示的校准语言模型 (CLMs)，这一设计灵感来源于privileged信息学习 (LUPI) 的范式。此外，我们还设计了一种减法交叉注意力 (SCA) 机制来优化这些表示。为了培养高效的预测模型，我们提出了一种创新的特权知识蒸馏 (PKD) 机制，包含相关性和特征蒸馏两部分。PKD 使学生模型能够模仿教师的行为，同时最小化输出差异。通过真实数据上的大量实验，我们验证了 TimeKD 在预测效果、效率和扩展性方面的显著优势。

> Multivariate time series forecasting (MTSF) endeavors to predict future observations given historical data, playing a crucial role in time series data management systems. With advancements in large language models (LLMs), recent studies employ textual prompt tuning to infuse the knowledge of LLMs into MTSF. However, the deployment of LLMs often suffers from low efficiency during the inference phase. To address this problem, we introduce TimeKD, an efficient MTSF framework that leverages the calibrated language models and privileged knowledge distillation. TimeKD aims to generate high-quality future representations from the proposed cross-modality teacher model and cultivate an effective student model. The cross-modality teacher model adopts calibrated language models (CLMs) with ground truth prompts, motivated by the paradigm of Learning Under Privileged Information (LUPI). In addition, we design a subtractive cross attention (SCA) mechanism to refine these representations. To cultivate an effective student model, we propose an innovative privileged knowledge distillation (PKD) mechanism including correlation and feature distillation. PKD enables the student to replicate the teacher's behavior while minimizing their output discrepancy. Extensive experiments on real data offer insight into the effectiveness, efficiency, and scalability of the proposed TimeKD.

[Arxiv](https://arxiv.org/abs/2505.02138)