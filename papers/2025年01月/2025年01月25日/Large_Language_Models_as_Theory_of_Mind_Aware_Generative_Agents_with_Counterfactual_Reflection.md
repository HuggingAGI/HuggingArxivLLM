# 大型语言模型：具备反事实反思能力的心理理论感知生成代理

发布时间：2025年01月25日

`Agent

理由：这篇论文提出了一种名为ToM-agent的新范式，旨在让基于LLMs的生成代理在开放域对话中模拟心理理论（ToM）。ToM-agent通过分离信心与心理状态，帮助代理模拟对手的心理状态，如信念、欲望和意图（BDIs）。此外，论文还提出了一种反事实干预方法，通过反思对手预测响应与实际话语之间的差距，提升反思效率。这些内容主要涉及代理的设计和行为模拟，因此将其分类为Agent。` `心理学` `对话系统`

> Large Language Models as Theory of Mind Aware Generative Agents with Counterfactual Reflection

# 摘要

> # 摘要
最近的研究表明，大型语言模型（LLMs）具备显著的心理理论（ToM）能力，能够在生成代理中模拟心理状态的跟踪。本研究提出了一种名为ToM-agent的新范式，旨在让基于LLMs的生成代理在开放域对话中模拟ToM。ToM-agent将信心与心理状态分离，帮助代理模拟对手的心理状态，如信念、欲望和意图（BDIs）。通过利用过去的对话历史和语言反思，ToM-Agent能够动态调整对手的BDIs推断及其相关信心水平。我们还提出了一种反事实干预方法，通过反思对手预测响应与实际话语之间的差距，提升反思效率。借助共情和说服对话数据集，我们评估了ToM-agent在下游任务中的优势，以及其在一阶和二阶ToM中的表现。研究结果表明，ToM-agent不仅能理解对手行为背后的原因，还能超越基于语义情感或常识的决策，为基于大规模LLMs的人类社会行为模拟研究提供了新的视角。

> Recent studies have increasingly demonstrated that large language models (LLMs) possess significant theory of mind (ToM) capabilities, showing the potential for simulating the tracking of mental states in generative agents. In this study, we propose a novel paradigm called ToM-agent, designed to empower LLMs-based generative agents to simulate ToM in open-domain conversational interactions. ToM-agent disentangles the confidence from mental states, facilitating the emulation of an agent's perception of its counterpart's mental states, such as beliefs, desires, and intentions (BDIs). Using past conversation history and verbal reflections, ToM-Agent can dynamically adjust counterparts' inferred BDIs, along with related confidence levels. We further put forth a counterfactual intervention method that reflects on the gap between the predicted responses of counterparts and their real utterances, thereby enhancing the efficiency of reflection. Leveraging empathetic and persuasion dialogue datasets, we assess the advantages of implementing the ToM-agent with downstream tasks, as well as its performance in both the first-order and the \textit{second-order} ToM. Our findings indicate that the ToM-agent can grasp the underlying reasons for their counterpart's behaviors beyond mere semantic-emotional supporting or decision-making based on common sense, providing new insights for studying large-scale LLMs-based simulation of human social behaviors.

[Arxiv](https://arxiv.org/abs/2501.15355)