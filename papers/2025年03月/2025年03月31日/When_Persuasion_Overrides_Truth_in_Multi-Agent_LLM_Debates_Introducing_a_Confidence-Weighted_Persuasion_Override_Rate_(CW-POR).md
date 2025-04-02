# 当说服胜过真相：多智能体LLM辩论中的信心加权说服接管率（CW-POR）

发布时间：2025年03月31日

`LLM应用` `人工智能` `智能体与机器人`

> When Persuasion Overrides Truth in Multi-Agent LLM Debates: Introducing a Confidence-Weighted Persuasion Override Rate (CW-POR)

# 摘要

> 在现实场景中，大型语言模型 (LLM) 可能会面对相互矛盾的主张，必须判断真伪。我们通过单轮多智能体辩论框架研究这一风险：一个 LLM 智能体提供事实回答，另一个则强烈维护错误主张，而同一 LLM 担任裁判。我们引入信心加权说服覆盖率 (CW-POR)，不仅衡量裁判被欺骗的频率，还衡量其对错误选项的相信程度。实验表明，即使较小的 LLM 也能构建说服力强的论点，覆盖真实答案且信心度高。这凸显了稳健校准和对抗测试的重要性，以防止 LLM 自信支持错误信息。

> In many real-world scenarios, a single Large Language Model (LLM) may encounter contradictory claims-some accurate, others forcefully incorrect-and must judge which is true. We investigate this risk in a single-turn, multi-agent debate framework: one LLM-based agent provides a factual answer from TruthfulQA, another vigorously defends a falsehood, and the same LLM architecture serves as judge. We introduce the Confidence-Weighted Persuasion Override Rate (CW-POR), which captures not only how often the judge is deceived but also how strongly it believes the incorrect choice. Our experiments on five open-source LLMs (3B-14B parameters), where we systematically vary agent verbosity (30-300 words), reveal that even smaller models can craft persuasive arguments that override truthful answers-often with high confidence. These findings underscore the importance of robust calibration and adversarial testing to prevent LLMs from confidently endorsing misinformation.

[Arxiv](https://arxiv.org/abs/2504.00374)