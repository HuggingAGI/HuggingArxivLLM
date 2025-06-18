# 从“回应什么”到“何时回应”：开放领域对话智能体的及时响应生成

发布时间：2025年06月17日

`LLM应用` `对话系统` `时间管理`

> From What to Respond to When to Respond: Timely Response Generation for Open-domain Dialogue Agents

# 摘要

> 对话响应生成的研究大多聚焦于基于文本上下文生成连贯的回复，但基于时间上下文决定何时回应这一关键问题却鲜有探索。为填补这一空白，我们提出了“及时对话响应生成”这一新任务，并推出了TimelyChat基准，用于评估语言模型预测合适时间间隔和生成基于时间的响应的能力。此外，我们利用时间常识知识图谱中的无标签事件知识，并借助大型语言模型（LLM）合成了55K个事件驱动的对话，构建了一个大规模的训练数据集。随后，我们训练了名为Timer的对话代理，它能够主动预测时间间隔并生成与之匹配的及时响应。实验结果显示，Timer在回合级别和对话级别的评估中均优于基于提示的LLM和其他微调的基线模型。我们已公开发布了我们的数据、模型和代码。

> While research on dialogue response generation has primarily focused on generating coherent responses conditioning on textual context, the critical question of when to respond grounded on the temporal context remains underexplored. To bridge this gap, we propose a novel task called timely dialogue response generation and introduce the TimelyChat benchmark, which evaluates the capabilities of language models to predict appropriate time intervals and generate time-conditioned responses. Additionally, we construct a large-scale training dataset by leveraging unlabeled event knowledge from a temporal commonsense knowledge graph and employing a large language model (LLM) to synthesize 55K event-driven dialogues. We then train Timer, a dialogue agent designed to proactively predict time intervals and generate timely responses that align with those intervals. Experimental results show that Timer outperforms prompting-based LLMs and other fine-tuned baselines in both turn-level and dialogue-level evaluations. We publicly release our data, model, and code.

[Arxiv](https://arxiv.org/abs/2506.14285)