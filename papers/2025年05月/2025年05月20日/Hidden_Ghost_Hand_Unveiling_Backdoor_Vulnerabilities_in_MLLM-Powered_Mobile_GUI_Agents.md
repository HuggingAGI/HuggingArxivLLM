# 隐秘的鬼手：深入剖析多语言大型模型赋能的移动GUI代理中的后门漏洞

发布时间：2025年05月20日

`Agent` `人工智能` `网络安全`

> Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents

# 摘要

> 基于多模态大语言模型（MLLMs）的图形用户界面（GUI）代理在人机交互方面展现出巨大潜力。然而，由于高昂的微调成本，用户通常依赖开源的GUI代理或AI提供商提供的API，这引入了一个关键但尚未充分探索的供应链威胁——后门攻击。

在这项研究中，我们首先揭示了MLLM驱动的GUI代理自然暴露了多个交互级触发器，例如历史步骤、环境状态和任务进度。基于这一观察，我们引入了AgentGhost，一个有效且隐蔽的红队后门攻击框架。

具体来说，我们通过结合目标和交互级别构建复合触发器，使GUI代理在无意中激活后门的同时确保任务实用性。然后，我们将后门注入建模为一个极小化极大优化问题，利用监督对比学习在表示空间中最大化样本类别的特征差异，从而提高后门的灵活性。同时，它采用监督微调来最小化后门与干净行为生成之间的差异，增强有效性和实用性。

在两个 established mobile 基准测试中对各种代理模型进行的广泛评估表明，AgentGhost 是有效的且通用的，其攻击准确率达到三个攻击目标的99.7%，并且仅导致1%的实用性下降，显示出其隐蔽性。此外，我们针对AgentGhost定制了一种防御方法，将攻击准确率降低至22.1%。我们的代码可在	exttt{anonymous}获得。

> Graphical user interface (GUI) agents powered by multimodal large language models (MLLMs) have shown greater promise for human-interaction. However, due to the high fine-tuning cost, users often rely on open-source GUI agents or APIs offered by AI providers, which introduces a critical but underexplored supply chain threat: backdoor attacks. In this work, we first unveil that MLLM-powered GUI agents naturally expose multiple interaction-level triggers, such as historical steps, environment states, and task progress. Based on this observation, we introduce AgentGhost, an effective and stealthy framework for red-teaming backdoor attacks. Specifically, we first construct composite triggers by combining goal and interaction levels, allowing GUI agents to unintentionally activate backdoors while ensuring task utility. Then, we formulate backdoor injection as a Min-Max optimization problem that uses supervised contrastive learning to maximize the feature difference across sample classes at the representation space, improving flexibility of the backdoor. Meanwhile, it adopts supervised fine-tuning to minimize the discrepancy between backdoor and clean behavior generation, enhancing effectiveness and utility. Extensive evaluations of various agent models in two established mobile benchmarks show that AgentGhost is effective and generic, with attack accuracy that reaches 99.7\% on three attack objectives, and shows stealthiness with only 1\% utility degradation. Furthermore, we tailor a defense method against AgentGhost that reduces the attack accuracy to 22.1\%. Our code is available at \texttt{anonymous}.

[Arxiv](https://arxiv.org/abs/2505.14418)