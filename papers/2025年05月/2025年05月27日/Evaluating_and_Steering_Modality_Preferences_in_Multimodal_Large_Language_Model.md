# 多模态大型语言模型中的模态偏好评估与引导

发布时间：2025年05月27日

`LLM应用` `多模态机器翻译`

> Evaluating and Steering Modality Preferences in Multimodal Large Language Model

# 摘要

> 多模态大型语言模型（MLLMs）在复杂多模态任务中表现出色，但它们在处理多模态上下文时是否存在模态偏好仍待研究。为此，我们在受控证据冲突场景下构建了	extbf{MC	extsuperscript{2}}基准测试，系统性评估模态偏好，即基于冲突证据时的模态选择倾向。系统性评估发现，所有测试的MLLMs均表现出明显模态偏见，且偏好可受外部干预影响。深入分析表明，偏好方向可被模型潜在表示捕捉。基于此，我们提出了一种基于表示工程的探测和引导方法，无需额外微调或精心设计提示即可显式控制模态偏好。该方法能有效放大模态偏好朝向预期方向，并成功应用于幻觉缓解和多模态机器翻译等任务，取得了显著改进。

> Multimodal large language models (MLLMs) have achieved remarkable performance on complex tasks with multimodal context. However, it is still understudied whether they exhibit modality preference when processing multimodal contexts. To study this question, we first build a \textbf{MC\textsuperscript{2}} benchmark under controlled evidence conflict scenarios to systematically evaluate modality preference, which is the tendency to favor one modality over another when making decisions based on multimodal conflicting evidence. Our extensive evaluation reveals that all 18 tested MLLMs generally demonstrate clear modality bias, and modality preference can be influenced by external interventions. An in-depth analysis reveals that the preference direction can be captured within the latent representations of MLLMs. Built on this, we propose a probing and steering method based on representation engineering to explicitly control modality preference without additional fine-tuning or carefully crafted prompts. Our method effectively amplifies modality preference toward a desired direction and applies to downstream tasks such as hallucination mitigation and multimodal machine translation, yielding promising improvements.

[Arxiv](https://arxiv.org/abs/2505.20977)