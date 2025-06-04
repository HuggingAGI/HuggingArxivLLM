# 强化学习助力 LLM 代理提升密码 CTF 挑战表现

发布时间：2025年05月31日

`LLM应用` `网络安全` `密码学`

> Improving LLM Agents with Reinforcement Learning on Cryptographic CTF Challenges

# 摘要

> 大型语言模型（LLMs）在网络安全应用中仍面临结构化推理和工具辅助计算的挑战。本研究引入了“random-crypto”框架，一个用于生成密码学Capture-the-Flag（CTF）挑战的工具。我们利用该框架，通过Guided Reinforcement Prompt Optimisation（GRPO）对增强工具的Llama-3.1-8B模型进行微调，使代理能够在隔离的REPL环境中迭代编写并执行Python代码。实验结果显示，GRPO使Pass@8指标在未见过的任务中提升了53%（从0.35提升至0.88），并将Majority@8提升至0.41。此外，该微调模型还能有效推广到外部数据集。在picoCTF密码学问题的子集上，Pass@8指标提升了13个百分点。进一步分析表明，性能提升主要得益于更可靠的工具调用和代码合成能力，而非简单的提示适应.

> Large Language Models (LLMs) still struggle with the structured reasoning and tool-assisted computation needed for problem solving in cybersecurity applications. In this work, we introduce "random-crypto", a cryptographic Capture-the-Flag (CTF) challenge generator framework that we use to fine-tune a tool-augmented Llama-3.1-8B with Guided Reinforcement Prompt Optimisation (GRPO), allowing the agent to iteratively write and execute Python inside an isolated REPL. GRPO yields a +53% absolute jump in Pass@8 on unseen "random-crypto" tasks (0.35 -> 0.88) and raises Majority@8 to 0.41. The fine-tuned agent also generalizes to an external dataset. On a subset of picoCTF cryptography problems, it improves Pass@8 by +13 pp. Ablations show the gains stem from more reliable tool invocation and code synthesis, rather than superficial prompt adaptation.

[Arxiv](https://arxiv.org/abs/2506.02048)