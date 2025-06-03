# 情境坦诚：借助层次化不可回答性检测提升大型语言模型的可信度

发布时间：2025年06月01日

`LLM应用` `对话系统` `人工智能`

> Contextual Candor: Enhancing LLM Trustworthiness Through Hierarchical Unanswerability Detection

# 摘要

> 大型语言模型（LLMs）在对话式AI中的广泛应用彻底改变了信息获取方式，但其生成事实不支持或凭空捏造回答的倾向仍是影响可信度和广泛应用的关键障碍。本文提出了一种全新的混合训练范式——强化不可答性学习（RUL），旨在赋予LLMs检测无法回答问题并生成合适回应的能力。与依赖外部分类器或简单提示的传统方法不同，RUL将不可答性预测头与LLM生成核心相结合，并通过多阶段学习策略进行优化。这包括在新型数据集Enhanced-CAsT-Answerability（ECA）上进行监督微调，该数据集具有分层可回答性标签和真实拒绝回应。RUL还引入了带有用户反馈的强化学习（RLHF）阶段，以优化拒绝回应的细微差别、有用性和信息量。实验结果表明，RUL在不可答性检测和生成合适拒绝回应方面表现显著提升，同时在可回答问题上也表现出色。人工评估进一步证实了RUL的有效性，强调了其在提升用户感知有用性和可信度方面的显著优势，为更可靠和以用户为中心的对话式AI铺平了道路。

> The pervasive deployment of large language models (LLMs) in conversational AI systems has revolutionized information access, yet their propensity for generating factually unsupported or hallucinated responses remains a critical impediment to trustworthiness and widespread adoption. This paper introduces Reinforced Unanswerability Learning (RUL), a novel hybrid training paradigm designed to imbue LLMs with the intrinsic capability to accurately detect unanswerable questions and generate reliably appropriate responses. Unlike conventional approaches that rely on external classifiers or simple prompting, RUL integrates a discriminative unanswerability prediction head with the LLM's generative core, guided by a multi-stage learning strategy. This includes supervised fine-tuning on a novel, richly annotated dataset, Enhanced-CAsT-Answerability (ECA), which features hierarchical answerability labels and ground-truth refusal responses. Crucially, RUL incorporates a subsequent reinforcement learning with human feedback (RLHF) phase to refine the nuance, helpfulness, and informativeness of refusal responses. Extensive experiments demonstrate RUL's superior performance, achieving significantly higher accuracy in unanswerability detection across sentence, paragraph, and ranking levels, and substantially increasing the generation of appropriate refusals for unanswerable queries, alongside strong performance on answerable questions. Human evaluations further corroborate RUL's effectiveness, highlighting a marked improvement in perceived helpfulness and trustworthiness, ultimately paving the way for more reliable and user-centric conversational AI.

[Arxiv](https://arxiv.org/abs/2506.01104)