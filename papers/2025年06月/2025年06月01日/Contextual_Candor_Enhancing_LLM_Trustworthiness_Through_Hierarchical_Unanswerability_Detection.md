# 基于上下文的坦诚：通过分层不可回答性检测让LLM更值得信赖

发布时间：2025年06月01日

`LLM应用

摘要中的论文提出了一种新的训练方法（RUL），用于改进大型语言模型在对话系统中的表现，使其能够更好地识别不可回答的问题并生成可靠的回应。这属于对大型语言模型的应用层面的改进和优化，因此归类为LLM应用。` `对话式AI`

> Contextual Candor: Enhancing LLM Trustworthiness Through Hierarchical Unanswerability Detection

# 摘要

> 大型语言模型 (LLMs) 在对话式 AI 系统中的广泛应用彻底改变了信息获取方式，但它们生成事实依据不足或凭空捏造回答的倾向仍然是影响可信度和广泛应用的关键障碍。本文提出了强化不可回答性学习 (RUL)，这是一种新型的混合训练范式，旨在赋予 LLMs 识别不可回答问题的内在能力，并生成可靠且合适的回答。

与依赖外部分类器或简单提示的传统方法不同，RUL 将一个判别性的不可回答性预测模块与 LLM 的生成核心相结合，并通过一个多阶段学习策略进行引导。这包括在新型的、丰富标注的数据集 Enhanced-CAsT-Answerability (ECA) 上进行监督微调，该数据集包含层次化的可回答性标签和真实的拒绝响应。至关重要的是，RUL 还集成了后续的带有强化学习和人类反馈 (RLHF) 的阶段，以优化拒绝响应的细微差别、有用性和信息量。

大量实验表明 RUL 的优越性能，其在句子、段落和排名级别上对不可回答性检测的准确率显著提高，并大幅增加了对不可回答查询生成合适拒绝响应的数量，同时在可回答问题上也表现出色。人类评估进一步证实了 RUL 的有效性，强调了感知有用性和可信度的显著提升，最终为更可靠和以用户为中心的对话式 AI 铺平了道路。

> The pervasive deployment of large language models (LLMs) in conversational AI systems has revolutionized information access, yet their propensity for generating factually unsupported or hallucinated responses remains a critical impediment to trustworthiness and widespread adoption. This paper introduces Reinforced Unanswerability Learning (RUL), a novel hybrid training paradigm designed to imbue LLMs with the intrinsic capability to accurately detect unanswerable questions and generate reliably appropriate responses. Unlike conventional approaches that rely on external classifiers or simple prompting, RUL integrates a discriminative unanswerability prediction head with the LLM's generative core, guided by a multi-stage learning strategy. This includes supervised fine-tuning on a novel, richly annotated dataset, Enhanced-CAsT-Answerability (ECA), which features hierarchical answerability labels and ground-truth refusal responses. Crucially, RUL incorporates a subsequent reinforcement learning with human feedback (RLHF) phase to refine the nuance, helpfulness, and informativeness of refusal responses. Extensive experiments demonstrate RUL's superior performance, achieving significantly higher accuracy in unanswerability detection across sentence, paragraph, and ranking levels, and substantially increasing the generation of appropriate refusals for unanswerable queries, alongside strong performance on answerable questions. Human evaluations further corroborate RUL's effectiveness, highlighting a marked improvement in perceived helpfulness and trustworthiness, ultimately paving the way for more reliable and user-centric conversational AI.

[Arxiv](https://arxiv.org/abs/2506.01104)