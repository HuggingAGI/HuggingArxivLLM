# 基于期望确认偏好的多轮对话推荐代理优化

发布时间：2025年06月17日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来改进对话推荐代理（CRAs）的性能。论文提出了一种新的多轮偏好优化方法ECPO，并开发了一个基于LLM的用户模拟器AILO。这些贡献都属于将LLM应用于特定任务的范畴，因此归类为LLM应用。` `对话系统` `推荐系统`

> Expectation Confirmation Preference Optimization for Multi-Turn Conversational Recommendation Agent

# 摘要

> 大型语言模型（LLMs）的最新进展极大地推动了对话推荐代理（CRAs）的发展。然而，现有代理往往生成短视的响应，难以持续引导用户并满足期望。尽管偏好优化在使LLMs与用户期望对齐方面已被证明有效，但其成本高昂且在多轮对话中表现不佳。为解决这一挑战，我们提出了一种新型多轮偏好优化（MTPO）范式——ECPO。ECPO基于期望确认理论，能够明确建模多轮对话中用户满意度的演变过程，揭示用户不满的根本原因。这些原因可用于支持对不满意响应的目标优化，从而实现逐轮的偏好优化。ECPO不仅巧妙地消除了现有MTPO方法中的显著采样开销，还确保优化过程带来实质性改进。为了支持ECPO，我们开发了一个基于LLM的用户模拟器AILO，用于模拟用户反馈并在对话推荐中进行期望确认。实验结果表明，ECPO显著提升了CRA的交互能力，与现有MTPO方法相比，在效率和效果方面均有显著提升。

> Recent advancements in Large Language Models (LLMs) have significantly propelled the development of Conversational Recommendation Agents (CRAs). However, these agents often generate short-sighted responses that fail to sustain user guidance and meet expectations. Although preference optimization has proven effective in aligning LLMs with user expectations, it remains costly and performs poorly in multi-turn dialogue. To address this challenge, we introduce a novel multi-turn preference optimization (MTPO) paradigm ECPO, which leverages Expectation Confirmation Theory to explicitly model the evolution of user satisfaction throughout multi-turn dialogues, uncovering the underlying causes of dissatisfaction. These causes can be utilized to support targeted optimization of unsatisfactory responses, thereby achieving turn-level preference optimization. ECPO ingeniously eliminates the significant sampling overhead of existing MTPO methods while ensuring the optimization process drives meaningful improvements. To support ECPO, we introduce an LLM-based user simulator, AILO, to simulate user feedback and perform expectation confirmation during conversational recommendations. Experimental results show that ECPO significantly enhances CRA's interaction capabilities, delivering notable improvements in both efficiency and effectiveness over existing MTPO methods.

[Arxiv](https://arxiv.org/abs/2506.14302)