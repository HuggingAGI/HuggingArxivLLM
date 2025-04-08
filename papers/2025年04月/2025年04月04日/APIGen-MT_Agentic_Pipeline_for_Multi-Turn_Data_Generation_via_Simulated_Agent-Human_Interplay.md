# APIGen-MT：通过模拟的智能体-人互动实现多轮数据生成的智能体管道

发布时间：2025年04月04日

`Agent` `AI代理` `对话系统`

> APIGen-MT: Agentic Pipeline for Multi-Turn Data Generation via Simulated Agent-Human Interplay

# 摘要

> 训练有效的AI代理以处理多轮交互需要高质量的数据，这些数据能够捕捉到真实的人与代理之间的动态交互。然而，这样的数据既稀缺又昂贵，难以通过人工方式收集。我们引入了APIGen-MT，这是一个两阶段的框架，用于生成可验证且多样化的多轮代理数据。在第一阶段，我们的代理管道利用一个由LLM评审团队组成的委员会和迭代反馈循环，生成带有真实动作的任务蓝图。这些蓝图随后通过模拟的人与代理互动转化为完整的交互轨迹。我们训练了一系列模型——参数规模从10亿到700亿的xLAM-2-fc-r系列模型。在【数学公式】-bench和BFCL基准测试中，我们的模型超越了前沿模型如GPT-4o和Claude 3.5，其中较小的模型在多轮设置下甚至超过了更大的模型，同时在多次试验中保持了优越的一致性。全面的实验表明，我们经过验证的蓝图到细节的方法生成了高质量的训练数据，从而能够开发出更可靠、更高效和更强大的代理。我们开源了收集的合成数据和训练的xLAM-2-fc-r模型，以推动AI代理领域的研究。模型可在HuggingFace上获取：https://huggingface.co/collections/Salesforce/xlam-2-67ef5be12949d8dcdae354c4，项目网站为https://apigen-mt.github.io

> Training effective AI agents for multi-turn interactions requires high-quality data that captures realistic human-agent dynamics, yet such data is scarce and expensive to collect manually. We introduce APIGen-MT, a two-phase framework that generates verifiable and diverse multi-turn agent data. In the first phase, our agentic pipeline produces detailed task blueprints with ground-truth actions, leveraging a committee of LLM reviewers and iterative feedback loops. These blueprints are then transformed into complete interaction trajectories through simulated human-agent interplay. We train a family of models -- the xLAM-2-fc-r series with sizes ranging from 1B to 70B parameters. Our models outperform frontier models such as GPT-4o and Claude 3.5 on $τ$-bench and BFCL benchmarks, with the smaller models surpassing their larger counterparts, particularly in multi-turn settings, while maintaining superior consistency across multiple trials. Comprehensive experiments demonstrate that our verified blueprint-to-details approach yields high-quality training data, enabling the development of more reliable, efficient, and capable agents. We open-source both the synthetic data collected and the trained xLAM-2-fc-r models to advance research in AI agents. Models are available on HuggingFace at https://huggingface.co/collections/Salesforce/xlam-2-67ef5be12949d8dcdae354c4 and project website is https://apigen-mt.github.io

[Arxiv](https://arxiv.org/abs/2504.03601)