# SWE-Dev：评估与训练自主特性驱动的软件开发

发布时间：2025年05月22日

`LLM应用` `软件工程` `人工智能`

> SWE-Dev: Evaluating and Training Autonomous Feature-Driven Software Development

# 摘要

> 大型语言模型 (LLMs) 在代码补全、漏洞修复和文档生成等软件工程任务中表现卓越。然而，尽管特征驱动开发 (FDD) 在真实世界中应用广泛，但目前尚未得到充分探索。为此，我们推出了 SWE-Dev，这是首个专注于真实世界特征开发任务的大型数据集，包含 14,000 个训练样本和 500 个测试样本。为了确保训练的多样性和可验证性，SWE-Dev 为每个实例提供了可运行的环境和开发者编写的可执行单元测试。这一数据集不仅为监督微调 (SFT) 提供了高质量的数据支持，还通过可执行单元测试提供的准确奖励信号，为强化学习 (RL) 开辟了新途径。我们在 SWE-Dev 上对 17 个聊天机器人 LLM、10 个推理模型和 10 个多智能体系统 (MAS) 进行了全面评估，结果显示 FDD 对当前 AI 来说是一项极具挑战性的任务（例如，Claude-3.7-Sonnet 在困难测试集上仅达到 22.45% 的 Pass@3）。更重要的是，我们发现 SWE-Dev 是一个卓越的模型优化平台：通过在训练集上进行微调，一个 7B 模型在 	extit{hard} 分割上已能与 GPT-4o 比肩，充分展现了其高质量训练数据的价值。代码可在 https://github.com/justLittleWhite/SWE-Dev 获取。

> Large Language Models (LLMs) have shown strong capability in diverse software engineering tasks, e.g. code completion, bug fixing, and document generation. However, feature-driven development (FDD), a highly prevalent real-world task that involves developing new functionalities for large, existing codebases, remains underexplored. We therefore introduce SWE-Dev, the first large-scale dataset (with 14,000 training and 500 test samples) designed to evaluate and train autonomous coding systems on real-world feature development tasks. To ensure verifiable and diverse training, SWE-Dev uniquely provides all instances with a runnable environment and its developer-authored executable unit tests. This collection not only provides high-quality data for Supervised Fine-Tuning (SFT), but also enables Reinforcement Learning (RL) by delivering accurate reward signals from executable unit tests. Our extensive evaluations on SWE-Dev, covering 17 chatbot LLMs, 10 reasoning models, and 10 Multi-Agent Systems (MAS), reveal that FDD is a profoundly challenging frontier for current AI (e.g., Claude-3.7-Sonnet achieves only 22.45\% Pass@3 on the hard test split). Crucially, we demonstrate that SWE-Dev serves as an effective platform for model improvement: fine-tuning on training set enabled a 7B model comparable to GPT-4o on \textit{hard} split, underscoring the value of its high-quality training data. Code is available here \href{https://github.com/justLittleWhite/SWE-Dev}{https://github.com/justLittleWhite/SWE-Dev}.

[Arxiv](https://arxiv.org/abs/2505.16975)