# 行为SFT：临床智能体在主动性光谱中的行为标记条件

发布时间：2025年05月27日

`LLM应用` `临床辅助`

> BehaviorSFT: Behavioral Token Conditioning for Clinical Agents Across the Proactivity Spectrum

# 摘要

> 大型语言模型（LLMs）在临床应用中需要谨慎的行为适应。虽然在诊断推理等反应性任务中表现出色，但它们往往在主动性参与方面表现不佳，例如未经提示就识别关键缺失信息或潜在风险。我们推出BehaviorBench，这是一个全面的评估数据集，用于衡量代理在临床辅助场景中的行为表现，涵盖从被动响应到主动干预的多种任务（例如澄清模糊信息、标记关键数据）。实验数据显示，LLMs在主动性任务上的表现参差不齐。为解决这一问题，我们提出了一种创新的训练策略——BehaviorSFT，通过行为令牌机制，引导模型在临床场景中实现动态行为选择。BehaviorSFT显著提升了模型性能，在BehaviorBench上实现了高达97.3%的整体Macro F1，并将主动性任务的得分从95.0%提升至96.5%（以Qwen2.5-7B-Ins为例）。更重要的是，经过盲评的临床医生一致认为，BehaviorSFT训练的代理在临床场景中表现得更加自然，能够在提供及时、相关的建议（有益的主动性）与避免过度干预（必要的克制）之间取得更好的平衡，优于传统微调或显式指令训练的模型。

> Large Language Models (LLMs) as clinical agents require careful behavioral adaptation. While adept at reactive tasks (e.g., diagnosis reasoning), LLMs often struggle with proactive engagement, like unprompted identification of critical missing information or risks. We introduce BehaviorBench, a comprehensive dataset to evaluate agent behaviors across a clinical assistance spectrum, ranging from reactive query responses to proactive interventions (e.g., clarifying ambiguities, flagging overlooked critical data). Our BehaviorBench experiments reveal LLMs' inconsistent proactivity. To address this, we propose BehaviorSFT, a novel training strategy using behavioral tokens to explicitly condition LLMs for dynamic behavioral selection along this spectrum. BehaviorSFT boosts performance, achieving up to 97.3% overall Macro F1 on BehaviorBench and improving proactive task scores (e.g., from 95.0% to 96.5% for Qwen2.5-7B-Ins). Crucially, blind clinician evaluations confirmed BehaviorSFT-trained agents exhibit more realistic clinical behavior, striking a superior balance between helpful proactivity (e.g., timely, relevant suggestions) and necessary restraint (e.g., avoiding over-intervention) versus standard fine-tuning or explicit instructed agents.

[Arxiv](https://arxiv.org/abs/2505.21757)