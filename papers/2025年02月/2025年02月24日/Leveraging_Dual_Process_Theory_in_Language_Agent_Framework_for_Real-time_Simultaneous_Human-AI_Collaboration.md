# # 利用双重过程理论实现实时同步的人工智能与人类协作在语言智能体框架中的应用

发布时间：2025年02月24日

`Agent` `人工智能` `人机协作`

> Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration

# 摘要

> 基于大型语言模型（LLMs）的代理在人机协作中表现出色，但在需要实时交互的多任务处理方面表现欠佳。延迟问题和推断多变的人类策略的挑战限制了它们在没有明确指令的情况下做出自主决策的能力。我们通过实验验证了当前独立的System 1和System 2方法，证实了在实时任务中应用双重过程理论（DPT）的必要性。为此，我们提出了一种全新的语言代理框架——DPT-Agent，该框架整合了System 1和System 2，以实现高效的人机实时协作。DPT-Agent的System 1采用有限状态机（FSM）和基于策略的代码实现快速、直观且可控的决策。DPT-Agent的System 2结合了心智理论（ToM）和异步反思机制，用于推断人类意图并进行基于推理的自主决策。通过与基于规则的代理和人类协作的进一步实验，我们展示了DPT-Agent相较于主流LLM框架的显著优势。据我们所知，DPT-Agent是首个实现自主成功的人机实时协作的语言代理框架。DPT-Agent的代码可在https://github.com/sjtu-marl/DPT-Agent获取。

> Agents built on large language models (LLMs) have excelled in turn-by-turn human-AI collaboration but struggle with simultaneous tasks requiring real-time interaction. Latency issues and the challenge of inferring variable human strategies hinder their ability to make autonomous decisions without explicit instructions. Through experiments with current independent System 1 and System 2 methods, we validate the necessity of using Dual Process Theory (DPT) in real-time tasks. We propose DPT-Agent, a novel language agent framework that integrates System 1 and System 2 for efficient real-time simultaneous human-AI collaboration. DPT-Agent's System 1 uses a Finite-state Machine (FSM) and code-as-policy for fast, intuitive, and controllable decision-making. DPT-Agent's System 2 integrates Theory of Mind (ToM) and asynchronous reflection to infer human intentions and perform reasoning-based autonomous decisions. We demonstrate the effectiveness of DPT-Agent through further experiments with rule-based agents and human collaborators, showing significant improvements over mainstream LLM-based frameworks. To the best of our knowledge, DPT-Agent is the first language agent framework that achieves successful real-time simultaneous human-AI collaboration autonomously. Code of DPT-Agent can be found in https://github.com/sjtu-marl/DPT-Agent.

[Arxiv](https://arxiv.org/abs/2502.11882)