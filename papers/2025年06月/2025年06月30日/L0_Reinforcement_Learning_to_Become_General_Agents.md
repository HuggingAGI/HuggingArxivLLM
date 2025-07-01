# L0: 强化学习迈向通用智能体

发布时间：2025年06月30日

`LLM应用` `人工智能` `问答系统`

> L0: Reinforcement Learning to Become General Agents

# 摘要

> 训练大型语言模型（LLMs）以执行多轮、长期任务仍面临可扩展性和训练效率的挑战。我们推出L-Zero（L0），一个适用于通用代理的可扩展端到端训练 pipeline。L0 配备低成本、可扩展且安全的并发代理工作池，降低了在复杂环境中应用强化学习的门槛。我们还引入了NB-Agent，这是L0中的代理框架，它通过Read-Eval-Print-Loop（REPL）以“代码即动作”的方式运行。我们在事实性问答基准上对L0进行了评估。实验表明，仅使用可验证奖励的强化学习（RLVR），基础模型就能够发展出强大的问题解决能力。在Qwen2.5-7B-Instruct模型上，我们的方法将SimpleQA的准确率从30%提升至80%，HotpotQA的准确率从22%提升至41%。我们已经开源了整个L0系统，包括我们的L0系列模型、NB-Agent、完整的训练 pipeline 以及相应的训练配方（https://github.com/cmriat/l0）。

> Training large language models (LLMs) to act as autonomous agents for multi-turn, long-horizon tasks remains significant challenges in scalability and training efficiency. To address this, we introduce L-Zero (L0), a scalable, end-to-end training pipeline for general-purpose agents. Featuring a low-cost, extensible, and sandboxed concurrent agent worker pool, L0 lowers the barrier for applying reinforcement learning in complex environments. We also introduce NB-Agent, the agent scaffold within L0, which operates in a "code-as-action" fashion via a Read-Eval-Print-Loop (REPL). We evaluate L0 on factuality question-answering benchmarks. Our experiments demonstrate that a base model can develop robust problem-solving skills using solely Reinforcement Learning with Verifiable Rewards (RLVR). On the Qwen2.5-7B-Instruct model, our method boosts accuracy on SimpleQA from 30 % to 80 % and on HotpotQA from 22 % to 41 %. We have open-sourced the entire L0 system, including our L0 series models, the NB-Agent, a complete training pipeline, and the corresponding training recipes on (https://github.com/cmriat/l0).

[Arxiv](https://arxiv.org/abs/2506.23667)