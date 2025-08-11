# LLM自动红队测试

发布时间：2025年08月06日

`LLM应用` `机器学习`

> Automatic LLM Red Teaming

# 摘要

> 红队测试是发现当前LLMs漏洞并建立信任的关键。然而，现有自动化方法依赖于脆性提示模板或单轮攻击，无法捕捉现实对抗对话的复杂交互本质。我们提出了一种全新范式：训练AI战略性地“击败”另一AI。通过将红队测试建模为马尔可夫决策过程（MDP），并采用分层强化学习框架，我们成功应对了稀疏奖励和长周期的固有挑战。我们的生成模型通过细致的token级别危害奖励，掌握了连贯的多轮攻击策略，能够发现现有方法忽视的微妙漏洞。这一创新方法树立了新标杆，将LLM红队测试重新定义为动态轨迹过程，而非一次性测试，为稳健AI部署奠定了基础。

> Red teaming is critical for identifying vulnerabilities and building trust in current LLMs. However, current automated methods for Large Language Models (LLMs) rely on brittle prompt templates or single-turn attacks, failing to capture the complex, interactive nature of real-world adversarial dialogues. We propose a novel paradigm: training an AI to strategically `break' another AI. By formalizing red teaming as a Markov Decision Process (MDP) and employing a hierarchical Reinforcement Learning (RL) framework, we effectively address the inherent sparse reward and long-horizon challenges. Our generative agent learns coherent, multi-turn attack strategies through a fine-grained, token-level harm reward, enabling it to uncover subtle vulnerabilities missed by existing baselines. This approach sets a new state-of-the-art, fundamentally reframing LLM red teaming as a dynamic, trajectory-based process (rather than a one-step test) essential for robust AI deployment.

[Arxiv](https://arxiv.org/abs/2508.04451)