# 语言混搭对双语LLM推理能力的影响

发布时间：2025年07月21日

`LLM理论` `语言模型`

> The Impact of Language Mixing on Bilingual LLM Reasoning

# 摘要

> 熟练的多语言使用者常会在对话中故意切换语言。类似地，近期专注于推理的双语大型语言模型（LLMs）在两种语言上均表现出强大能力，并会在其思维链中交替使用语言——即语言混合。抑制 DeepSeek-R1 中的这种行为会降低准确性，这表明语言混合可能有助于推理。本研究探讨了中英双语推理模型中的语言切换现象。我们发现，使用可验证奖励的强化学习（RLVR）是导致语言混合的关键训练阶段。实验表明，语言混合能够提升推理能力：强制使用单语解码会在数学推理任务上降低 5.6 个百分点的准确率。此外，一个轻量级的探测器可以被训练出来，用于预测潜在的语言切换是否会对推理产生有益或有害的影响，当用于指导解码过程时，准确率最多可提升 6.25 个百分点。我们的研究结果表明，语言混合不仅仅是一个多语言训练的副产品，而是一种战略性的推理行为。

> Proficient multilingual speakers often intentionally switch languages in the middle of a conversation. Similarly, recent reasoning-focused bilingual large language models (LLMs) with strong capabilities in both languages exhibit language mixing--alternating languages within their chain of thought. Discouraging this behavior in DeepSeek-R1 was found to degrade accuracy, suggesting that language mixing may benefit reasoning. In this work, we study language switching in Chinese-English bilingual reasoning models. We identify reinforcement learning with verifiable rewards (RLVR) as the critical training stage that leads to language mixing. We demonstrate that language mixing can enhance reasoning: enforcing monolingual decoding reduces accuracy by 5.6 percentage points on math reasoning tasks. Additionally, a lightweight probe can be trained to predict whether a potential language switch would benefit or harm reasoning, and when used to guide decoding, increases accuracy by up to 6.25 percentage points. Our findings suggest that language mixing is not merely a byproduct of multilingual training, but is a strategic reasoning behavior.

[Arxiv](https://arxiv.org/abs/2507.15849)