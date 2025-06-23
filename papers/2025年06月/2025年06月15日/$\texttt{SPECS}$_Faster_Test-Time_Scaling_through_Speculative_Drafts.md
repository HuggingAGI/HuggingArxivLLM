# 【数学公式】：通过推测性草稿实现更快的测试时间缩放

发布时间：2025年06月15日

`LLM应用` `机器人流程自动化` `企业级应用`

> $\texttt{SPECS}$: Faster Test-Time Scaling through Speculative Drafts

# 摘要

> # 摘要  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

> Scaling test-time compute has driven the recent advances in the reasoning capabilities of large language models (LLMs), typically by allocating additional computation for more thorough exploration. However, increased compute often comes at the expense of higher user-facing latency, directly impacting user experience. Current test-time scaling methods primarily optimize for accuracy based on total compute resources (FLOPS), often overlooking latency constraints. To address this gap, we propose $\texttt{SPECS}$, a latency-aware test-time scaling method inspired by speculative decoding. $\texttt{SPECS}$~uses a smaller, faster model to generate candidate sequences efficiently, and evaluates these candidates using signals from both a larger target model and a dedicated reward model. We introduce new integration strategies, including reward-guided soft verification and a reward-based deferral mechanism. Empirical results on MATH500, AMC23 and OlympiadBench datasets show that $\texttt{SPECS}$~matches or surpasses beam search accuracy while reducing latency by up to $\sim$19.1\%. Our theoretical analysis shows that our algorithm converges to the solution of a KL-regularized reinforcement learning objective with increasing beam width.

[Arxiv](https://arxiv.org/abs/2506.15733)