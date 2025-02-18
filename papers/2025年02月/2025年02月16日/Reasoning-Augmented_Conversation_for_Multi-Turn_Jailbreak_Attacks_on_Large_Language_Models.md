# 推理增强对话：针对大型语言模型的多轮越狱攻击研究

发布时间：2025年02月16日

`LLM应用` `大型语言模型`

> Reasoning-Augmented Conversation for Multi-Turn Jailbreak Attacks on Large Language Models

# 摘要

> 多轮越狱攻击通过与大型语言模型 (LLMs) 进行迭代对话，模拟真实的人类交互过程，揭示了关键的安全漏洞。然而，现有方法往往难以在语义连贯性和攻击有效性之间取得平衡，导致要么出现良性的语义漂移，要么无法有效规避检测。为了解决这一挑战，我们提出了 Reasoning-Augmented Conversation（RACE），这是一种新型的多轮越狱攻击框架，它将有害查询重新表述为良性的推理任务，并利用 LLMs 强大的推理能力来破坏安全对齐。具体而言，我们引入了一个攻击状态机框架，系统地建模问题转换和迭代推理，确保跨多轮的连贯查询生成。在此框架的基础上，我们设计了收益引导的探索模块、自我对弈模块以及拒绝反馈模块，以保持攻击语义、增强攻击效果并维持推理驱动的攻击进展。在多个 LLM 上进行的广泛实验表明，RACE 在复杂的对话场景中实现了最先进的攻击效果，攻击成功率 (ASR) 最高提升了 96%。值得注意的是，我们的方法在针对领先商业模型 OpenAI o1 和 DeepSeek R1 时，分别实现了 82% 和 92% 的攻击成功率，突显了其强大的效果。我们已将代码发布在 https://github.com/NY1024/RACE，以促进这一关键领域进一步的研究。

> Multi-turn jailbreak attacks simulate real-world human interactions by engaging large language models (LLMs) in iterative dialogues, exposing critical safety vulnerabilities. However, existing methods often struggle to balance semantic coherence with attack effectiveness, resulting in either benign semantic drift or ineffective detection evasion. To address this challenge, we propose Reasoning-Augmented Conversation, a novel multi-turn jailbreak framework that reformulates harmful queries into benign reasoning tasks and leverages LLMs' strong reasoning capabilities to compromise safety alignment. Specifically, we introduce an attack state machine framework to systematically model problem translation and iterative reasoning, ensuring coherent query generation across multiple turns. Building on this framework, we design gain-guided exploration, self-play, and rejection feedback modules to preserve attack semantics, enhance effectiveness, and sustain reasoning-driven attack progression. Extensive experiments on multiple LLMs demonstrate that RACE achieves state-of-the-art attack effectiveness in complex conversational scenarios, with attack success rates (ASRs) increasing by up to 96%. Notably, our approach achieves ASRs of 82% and 92% against leading commercial models, OpenAI o1 and DeepSeek R1, underscoring its potency. We release our code at https://github.com/NY1024/RACE to facilitate further research in this critical domain.

[Arxiv](https://arxiv.org/abs/2502.11054)