# 系统提示投毒攻击：突破传统用户注入的大型语言模型持续性攻击

发布时间：2025年05月09日

`LLM应用` `人工智能安全` `计算机科学`

> System Prompt Poisoning: Persistent Attacks on Large Language Models Beyond User Injection

# 摘要

> 大型语言模型（LLMs）凭借其强大的生成能力，已在众多领域得到广泛应用。其即插即用的特性让开发者和终端用户只需通过简单提示即可与其互动。然而，随着LLMs在各领域中的广泛应用，围绕其安全性的担忧也在不断增加。现有研究主要关注用户提示（如提示注入攻击）和模型输出（如模型逆向攻击）的安全威胁，而系统提示的安全性问题却未得到足够重视。本研究填补了这一关键空白。我们提出了一种新型攻击方式——系统提示投毒。与传统用户提示注入不同，该方法通过投毒系统提示，从而对后续所有用户交互和模型响应产生持久影响。我们系统性地研究了四种实际攻击策略在不同投毒场景下的表现。通过对生成型和推理型LLMs的实证演示，我们证明了系统提示投毒无需借助越狱技术即可实现，且在数学、编程、逻辑推理及自然语言处理等广泛任务中均表现出显著有效性。尤为重要的是，即便用户提示采用了先进的提示技术如思维链（CoT），该攻击仍能保持其有效性。此外，我们还发现，包括CoT和检索增强生成（RAG）在内的多种技术，尽管已被证实能有效提升LLMs在众多任务中的性能，但在系统提示投毒的攻击下，其效果会大幅削弱。

> Large language models (LLMs) have gained widespread adoption across diverse applications due to their impressive generative capabilities. Their plug-and-play nature enables both developers and end users to interact with these models through simple prompts. However, as LLMs become more integrated into various systems in diverse domains, concerns around their security are growing. Existing studies mainly focus on threats arising from user prompts (e.g. prompt injection attack) and model output (e.g. model inversion attack), while the security of system prompts remains largely overlooked. This work bridges the critical gap. We introduce system prompt poisoning, a new attack vector against LLMs that, unlike traditional user prompt injection, poisons system prompts hence persistently impacts all subsequent user interactions and model responses. We systematically investigate four practical attack strategies in various poisoning scenarios. Through demonstration on both generative and reasoning LLMs, we show that system prompt poisoning is highly feasible without requiring jailbreak techniques, and effective across a wide range of tasks, including those in mathematics, coding, logical reasoning, and natural language processing. Importantly, our findings reveal that the attack remains effective even when user prompts employ advanced prompting techniques like chain-of-thought (CoT). We also show that such techniques, including CoT and retrieval-augmentation-generation (RAG), which are proven to be effective for improving LLM performance in a wide range of tasks, are significantly weakened in their effectiveness by system prompt poisoning.

[Arxiv](https://arxiv.org/abs/2505.06493)