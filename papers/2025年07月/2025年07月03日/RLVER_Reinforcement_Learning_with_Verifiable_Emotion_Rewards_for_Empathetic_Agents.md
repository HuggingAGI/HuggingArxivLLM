# RLVER：一种基于可验证情感奖励的共情智能体强化学习方法

发布时间：2025年07月03日

`LLM应用` `对话系统` `情感智能`

> RLVER: Reinforcement Learning with Verifiable Emotion Rewards for Empathetic Agents

# 摘要

> 大型语言模型 (LLMs) 在逻辑推理上表现出色，但情商建设仍有很大提升空间。尽管基于可验证奖励的强化学习 (RLVR) 在其他领域取得进展，但其在对话尤其是情商领域的应用仍待探索。本研究推出 RLVER——首个端到端强化学习框架，通过模拟用户提供的可验证情感奖励，培养 LLM 的高级同理心能力。框架中，自我一致的情感模拟用户参与对话展开，实时生成确定性情感评分作为奖励信号，指导 LLM 学习。通过 PPO 对 Qwen2.5-7B-Instruct 模型微调，其 Sentient-Benchmark 评分从 13.3 提升至 79.2，同时保持数学和编码能力。实验结果表明：
(i) RLVER 有效提升多种对话能力；
(ii) 思考型模型在同理心和洞察力方面表现突出，而非思考型模型更倾向于行动导向；
(iii) GRPO 通常带来稳定提升，而 PPO 则能将某些能力推向更高水平；
(iv) 环境挑战性并非越大越好——适度环境往往带来更佳效果。RLVER 为打造情感智能且能力全面的语言智能体提供了实用解决方案。


> Large language models (LLMs) excel at logical and algorithmic reasoning, yet their emotional intelligence (EQ) still lags far behind their cognitive prowess. While reinforcement learning from verifiable rewards (RLVR) has advanced in other domains, its application to dialogue-especially for emotional intelligence-remains underexplored. In this work, we introduce RLVER, the first end-to-end reinforcement learning framework that leverages verifiable emotion rewards from simulated users to cultivate higher-order empathetic abilities in LLMs. Within this framework, self-consistent affective simulated users engage in dialogue rollouts and produce deterministic emotion scores during conversations, serving as reward signals to guide the LLM's learning. Fine-tuning publicly available Qwen2.5-7B-Instruct model with PPO boosts its Sentient-Benchmark score from 13.3 to 79.2 while largely preserving mathematical and coding competence. Extensive experiments reveal that: (i) RLVER consistently improves multiple dialogue capabilities; (ii) Thinking and non-thinking models show distinct trends--thinking models excel in empathy and insight, while non-thinking models favor action; (iii) GRPO often yields stable gains, while PPO can push certain capabilities to a higher ceiling; (iv) More challenging environments are not always better-moderate ones can yield stronger outcomes. Our results show that RLVER is a practical route toward emotionally intelligent and broadly capable language agents.

[Arxiv](https://arxiv.org/abs/2507.03112)