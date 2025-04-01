# 智能体大型语言模型综述

发布时间：2025年03月29日

`Agent`

> Agentic Large Language Models, a survey

# 摘要

> 人们对代理型LLM（作为代理的大型语言模型）充满兴趣。我们综述了该领域的研究成果，并提出了一个研究议程。代理型LLM是具备以下能力的LLM：(1)推理，(2)行动，(3)交互。我们根据这三个类别整理文献。第一类研究集中在推理、反思和检索上，旨在提升决策能力；第二类研究集中在行动模型、机器人和工具上，旨在打造有用的助手型代理；第三类研究集中在多智能体系统上，旨在实现协作任务解决和模拟交互以研究涌现的社会行为。我们发现各类研究相互受益：检索能力使代理能够使用工具，反思能力提升多智能体协作，推理能力则对所有类别都有助益。我们探讨了代理型LLM的应用，并提出了未来研究的议程。重要应用领域包括医疗诊断、物流和金融市场分析。同时，具有自我反思能力的代理在科学研究中扮演角色并相互互动，进一步推动了科学研究的发展。此外，代理型LLM可能为解决LLM脱离训练数据的问题提供解决方案：推理时的行为生成新的训练状态，使LLM无需依赖日益庞大的数据集，持续学习。我们注意到，LLM助手在现实世界中采取行动存在风险，而代理型LLM也有可能为社会带来益处。

> There is great interest in agentic LLMs, large language models that act as agents. We review the growing body of work in this area and provide a research agenda. Agentic LLMs are LLMs that (1) reason, (2) act, and (3) interact. We organize the literature according to these three categories. The research in the first category focuses on reasoning, reflection, and retrieval, aiming to improve decision making; the second category focuses on action models, robots, and tools, aiming for agents that act as useful assistants; the third category focuses on multi-agent systems, aiming for collaborative task solving and simulating interaction to study emergent social behavior. We find that works mutually benefit from results in other categories: retrieval enables tool use, reflection improves multi-agent collaboration, and reasoning benefits all categories. We discuss applications of agentic LLMs and provide an agenda for further research. Important applications are in medical diagnosis, logistics and financial market analysis. Meanwhile, self-reflective agents playing roles and interacting with one another augment the process of scientific research itself. Further, agentic LLMs may provide a solution for the problem of LLMs running out of training data: inference-time behavior generates new training states, such that LLMs can keep learning without needing ever larger datasets. We note that there is risk associated with LLM assistants taking action in the real world, while agentic LLMs are also likely to benefit society.

[Arxiv](https://arxiv.org/abs/2503.23037)