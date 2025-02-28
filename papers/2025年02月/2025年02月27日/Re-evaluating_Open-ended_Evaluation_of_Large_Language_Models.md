# # 重新审视大型语言模型的开放评估
重新审视大型语言模型的开放评估

发布时间：2025年02月27日

`其他` `人工智能评估` `博弈论`

> Re-evaluating Open-ended Evaluation of Large Language Models

# 摘要

> 传统评估方法主要针对特定技能对候选人进行排序。现代通用模型，如大型语言模型（LLMs），已远远超越这一模式。开放式评估系统由此兴起，通过用户提交的提示对候选模型进行对比。尽管这些系统优势众多，但我们的研究发现，当前基于Elo的评分体系可能易受数据中蓄意或无意的偏见影响，甚至可能强化这些偏见，因其对冗余高度敏感。为应对这一挑战，我们提出将评估视为三玩家游戏，并引入创新的博弈论解决方案，以增强对冗余的鲁棒性。我们的方法不仅带来直观的评分结果，还为理解LLM开发的竞争态势提供了深刻见解。

> Evaluation has traditionally focused on ranking candidates for a specific skill. Modern generalist models, such as Large Language Models (LLMs), decidedly outpace this paradigm. Open-ended evaluation systems, where candidate models are compared on user-submitted prompts, have emerged as a popular solution. Despite their many advantages, we show that the current Elo-based rating systems can be susceptible to and even reinforce biases in data, intentional or accidental, due to their sensitivity to redundancies. To address this issue, we propose evaluation as a 3-player game, and introduce novel game-theoretic solution concepts to ensure robustness to redundancy. We show that our method leads to intuitive ratings and provide insights into the competitive landscape of LLM development.

[Arxiv](https://arxiv.org/abs/2502.20170)