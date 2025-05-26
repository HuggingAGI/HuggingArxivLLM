# 重塑它！微调中的LLM安全性重塑

发布时间：2025年05月22日

`LLM理论` `模型安全` `模型训练`

> Shape it Up! Restoring LLM Safety during Finetuning

# 摘要

> 微调大型语言模型 (LLMs) 能实现个性化定制，但存在重大安全风险：少量有害示例就可能破坏安全对齐。传统缓解方法是强化模型对安全示例的更新，同时弱化或排除不安全内容。然而，由于安全上下文可能在单个示例内部变化，因此对有害和无害响应部分同等更新并非最优——这种粗放处理方式被称为静态安全塑造。  
相比之下，我们提出了一种动态安全塑造 (DSS) 框架，通过精细安全信号强化对响应安全部分的学习，同时抑制不安全内容。为了实现微调过程中的精细控制，我们发现：传统用于过滤的护轨模型可重新用于评估部分响应，逐段跟踪安全风险的演变。这引出了响应安全轨迹评估 (STAR)，这是一种基于令牌的信号，使塑造能够在训练序列上动态操作。  
在此基础上，我们提出了由 STAR 评分引导的 STAR-DSS 方法，该方法能够稳健缓解微调风险，并在多种威胁、数据集和模型家族中实现显著安全改进，同时保持其在预期任务上的能力。我们鼓励未来的安全研究基于动态塑造原则，以更有效地应对不断演变的微调风险。

> Finetuning large language models (LLMs) enables user-specific customization but introduces critical safety risks: even a few harmful examples can compromise safety alignment. A common mitigation strategy is to update the model more strongly on examples deemed safe, while downweighting or excluding those flagged as unsafe. However, because safety context can shift within a single example, updating the model equally on both harmful and harmless parts of a response is suboptimal-a coarse treatment we term static safety shaping. In contrast, we propose dynamic safety shaping (DSS), a framework that uses fine-grained safety signals to reinforce learning from safe segments of a response while suppressing unsafe content. To enable such fine-grained control during finetuning, we introduce a key insight: guardrail models, traditionally used for filtering, can be repurposed to evaluate partial responses, tracking how safety risk evolves throughout the response, segment by segment. This leads to the Safety Trajectory Assessment of Response (STAR), a token-level signal that enables shaping to operate dynamically over the training sequence. Building on this, we present STAR-DSS, guided by STAR scores, that robustly mitigates finetuning risks and delivers substantial safety improvements across diverse threats, datasets, and model families-all without compromising capability on intended tasks. We encourage future safety research to build on dynamic shaping principles for stronger mitigation against evolving finetuning risks.

[Arxiv](https://arxiv.org/abs/2505.17196)