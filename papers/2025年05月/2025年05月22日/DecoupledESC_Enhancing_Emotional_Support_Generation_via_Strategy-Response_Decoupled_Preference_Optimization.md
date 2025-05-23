# DecoupledESC: 通过策略与响应的解耦偏好优化，提升情绪支持生成效果

发布时间：2025年05月22日

`LLM应用` `情感支持对话`

> DecoupledESC: Enhancing Emotional Support Generation via Strategy-Response Decoupled Preference Optimization

# 摘要

> 近期，情感支持对话（ESC）领域取得了显著进展，通过监督微调（SFT）优化大型语言模型（LLMs），显著提升了情感支持生成的效果。然而，常见的心理错误仍然存在。尽管直接偏好优化（DPO）通过成对偏好学习在减少此类错误方面展现出潜力，但其在ESC任务中的有效性受到两个关键挑战的限制：(1) 数据结构纠缠：现有的ESC数据本质上将心理策略和响应内容纠缠在一起，使得构建高质量的偏好对变得困难；(2) 优化模糊性：将标准的DPO应用于这种纠缠的成对数据会导致模糊的训练目标。为了解决这些问题，我们引入了推断偏好挖掘（IPM）来构建高质量的偏好数据，形成了IPM-PrefDial数据集。基于此数据集，我们提出了受Gross情绪调节扩展过程模型启发的Decoupled ESC框架，将ESC任务分解为两个连续的子任务：策略规划和共情响应生成。每个子任务均通过SFT进行训练，并随后通过DPO进行增强，以与心理偏好对齐。大量实验表明，我们的Decoupled ESC框架优于联合优化基线，减少了偏好偏差，并提高了响应质量。

> Recent advances in Emotional Support Conversation (ESC) have improved emotional support generation by fine-tuning Large Language Models (LLMs) via Supervised Fine-Tuning (SFT). However, common psychological errors still persist. While Direct Preference Optimization (DPO) shows promise in reducing such errors through pairwise preference learning, its effectiveness in ESC tasks is limited by two key challenges: (1) Entangled data structure: Existing ESC data inherently entangles psychological strategies and response content, making it difficult to construct high-quality preference pairs; and (2) Optimization ambiguity: Applying vanilla DPO to such entangled pairwise data leads to ambiguous training objectives. To address these issues, we introduce Inferential Preference Mining (IPM) to construct high-quality preference data, forming the IPM-PrefDial dataset. Building upon this data, we propose a Decoupled ESC framework inspired by Gross's Extended Process Model of Emotion Regulation, which decomposes the ESC task into two sequential subtasks: strategy planning and empathic response generation. Each was trained via SFT and subsequently enhanced by DPO to align with the psychological preference. Extensive experiments demonstrate that our Decoupled ESC framework outperforms joint optimization baselines, reducing preference bias and improving response quality.

[Arxiv](https://arxiv.org/abs/2505.16995)