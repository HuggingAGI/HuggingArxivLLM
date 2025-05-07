# 智能体作为评测者：大型语言模型的高阶社会认知能力评测

发布时间：2025年05月01日

`LLM应用` `人工智能` `情感计算`

> Sentient Agent as a Judge: Evaluating Higher-Order Social Cognition in Large Language Models

# 摘要

> 评估大型语言模型 (LLM) 对人类的理解程度，而非仅仅理解文本，仍然是一个开放性的挑战。为了解决这一难题，我们提出了 Sentient Agent 作为 Judge (SAGE)，这是一个自动化评估框架，用于衡量 LLM 的更高阶社会认知能力。SAGE 实例化了一个 Sentient Agent，在交互过程中模拟人类般的情感变化和内心想法，从而在多轮对话中对被测试模型进行更为真实的评估。在每一轮对话中，该智能体都会推理 (i) 其情感如何变化，(ii) 它的感受如何，以及 (iii) 它应该如何回应，从而生成一个数值化的情感轨迹和可解释的内心想法。在 100 个支持性对话场景上的实验表明，最终的 Sentient 情感评分与巴雷特-伦纳德关系量表 (BLRI) 评分以及 utterance-level 共情指标之间存在强烈的相关性，验证了心理保真度。我们还构建了一个公开的 Sentient Leaderboard，涵盖了 18 个商业和开源模型，揭示了前沿系统 (GPT-4o-Latest, Gemini2.5-Pro) 与早期基线之间的显著差距（高达 4 倍），而这些差距并未体现在传统的排行榜（如 Arena）中。因此，SAGE 提供了一个原则性、可扩展且可解释的工具，用于跟踪迈向真正富有同理心且社交能力强的语言智能体的进步。

> Assessing how well a large language model (LLM) understands human, rather than merely text, remains an open challenge. To bridge the gap, we introduce Sentient Agent as a Judge (SAGE), an automated evaluation framework that measures an LLM's higher-order social cognition. SAGE instantiates a Sentient Agent that simulates human-like emotional changes and inner thoughts during interaction, providing a more realistic evaluation of the tested model in multi-turn conversations. At every turn, the agent reasons about (i) how its emotion changes, (ii) how it feels, and (iii) how it should reply, yielding a numerical emotion trajectory and interpretable inner thoughts. Experiments on 100 supportive-dialogue scenarios show that the final Sentient emotion score correlates strongly with Barrett-Lennard Relationship Inventory (BLRI) ratings and utterance-level empathy metrics, validating psychological fidelity. We also build a public Sentient Leaderboard covering 18 commercial and open-source models that uncovers substantial gaps (up to 4x) between frontier systems (GPT-4o-Latest, Gemini2.5-Pro) and earlier baselines, gaps not reflected in conventional leaderboards (e.g., Arena). SAGE thus provides a principled, scalable and interpretable tool for tracking progress toward genuinely empathetic and socially adept language agents.

[Arxiv](https://arxiv.org/abs/2505.02847)