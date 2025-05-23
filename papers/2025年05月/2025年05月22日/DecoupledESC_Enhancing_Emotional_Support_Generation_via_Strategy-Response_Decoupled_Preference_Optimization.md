# # **DecoupledESC**：采用策略与响应解耦的偏好优化方法提升情感支持生成效果

发布时间：2025年05月22日

`LLM应用` `心理健康` `对话系统`

> DecoupledESC: Enhancing Emotional Support Generation via Strategy-Response Decoupled Preference Optimization

# 摘要

> 最近，情感支持对话（ESC）领域的进展通过监督式微调（SFT）对大型语言模型（LLMs）进行优化，显著提升了情感支持生成的效果。然而，常见的心理错误问题依然存在。尽管直接偏好优化（DPO）通过成对偏好学习在减少此类错误方面展现出潜力，但其在ESC任务中的有效性受到两大关键挑战的限制：

1. **纠缠的数据结构**：现有的ESC数据将心理策略与响应内容深度结合，导致难以构建高质量的偏好对；
2. **优化模糊性**：将原始DPO应用于这种纠缠的成对数据会引发模糊的训练目标。

为了解决这些问题，我们提出了**推断偏好挖掘（IPM）**方法，构建了高质量的偏好数据集——**IPM-PrefDial**。基于此数据集，我们开发了受Gross情绪调节扩展过程模型启发的**解耦ESC框架**，将ESC任务分解为**策略规划**和**共情响应生成**两个顺序子任务。每个子任务均通过SFT进行基础训练，并通过DPO进一步优化以符合心理偏好。大量实验表明，我们的解耦ESC框架显著优于联合优化基线，成功减少了偏好偏差并显著提升了响应质量。

> Recent advances in Emotional Support Conversation (ESC) have improved emotional support generation by fine-tuning Large Language Models (LLMs) via Supervised Fine-Tuning (SFT). However, common psychological errors still persist. While Direct Preference Optimization (DPO) shows promise in reducing such errors through pairwise preference learning, its effectiveness in ESC tasks is limited by two key challenges: (1) Entangled data structure: Existing ESC data inherently entangles psychological strategies and response content, making it difficult to construct high-quality preference pairs; and (2) Optimization ambiguity: Applying vanilla DPO to such entangled pairwise data leads to ambiguous training objectives. To address these issues, we introduce Inferential Preference Mining (IPM) to construct high-quality preference data, forming the IPM-PrefDial dataset. Building upon this data, we propose a Decoupled ESC framework inspired by Gross's Extended Process Model of Emotion Regulation, which decomposes the ESC task into two sequential subtasks: strategy planning and empathic response generation. Each was trained via SFT and subsequently enhanced by DPO to align with the psychological preference. Extensive experiments demonstrate that our Decoupled ESC framework outperforms joint optimization baselines, reducing preference bias and improving response quality.

[Arxiv](https://arxiv.org/abs/2505.16995)