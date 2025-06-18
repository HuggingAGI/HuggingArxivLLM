# 镜像方法：通过基于提示的可迁移对抗攻击，打破大型语言模型（LLM）智能体的角色一致性

发布时间：2025年06月17日

`Agent` `智能体` `安全性`

> Doppelgänger Method: Breaking Role Consistency in LLM Agent via Prompt-based Transferable Adversarial Attack

# 摘要

> 自大型语言模型诞生以来，提示工程已能够快速、轻松地创建各种自主智能体，这些智能体已得到广泛应用。然而，这种便利也引发了关于安全性和一致性的紧迫担忧，以及防止提示被暴露给用户的迫切需求。本文中，我们提出了''镜像方法''来演示智能体被劫持的风险，从而暴露系统指令和内部信息。我们定义了''对抗转移攻击下的提示对齐崩塌 (PACAT)''级别来评估此类攻击的脆弱性。同时，我们提出了一个''对抗转移防御提示 (CAT)''来对抗镜像方法。实验结果表明，镜像方法能够破坏智能体的一致性并暴露其内部信息，而CAT提示则能够有效防御此类攻击。

> Since the advent of large language models, prompt engineering now enables the rapid, low-effort creation of diverse autonomous agents that are already in widespread use. Yet this convenience raises urgent concerns about the safety, robustness, and behavioral consistency of the underlying prompts, along with the pressing challenge of preventing those prompts from being exposed to user's attempts. In this paper, we propose the ''Doppelgänger method'' to demonstrate the risk of an agent being hijacked, thereby exposing system instructions and internal information. Next, we define the ''Prompt Alignment Collapse under Adversarial Transfer (PACAT)'' level to evaluate the vulnerability to this adversarial transfer attack. We also propose a ''Caution for Adversarial Transfer (CAT)'' prompt to counter the Doppelgänger method. The experimental results demonstrate that the Doppelgänger method can compromise the agent's consistency and expose its internal information. In contrast, CAT prompts enable effective defense against this adversarial attack.

[Arxiv](https://arxiv.org/abs/2506.14539)