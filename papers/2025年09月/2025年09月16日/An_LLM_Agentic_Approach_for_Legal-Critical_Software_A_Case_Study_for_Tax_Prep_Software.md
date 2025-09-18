# 面向法律关键软件的大型语言模型智能体方法：税务准备软件的案例研究

发布时间：2025年09月16日

`Agent` `法律科技`

> An LLM Agentic Approach for Legal-Critical Software: A Case Study for Tax Prep Software

# 摘要

> 大型语言模型（LLMs）有望将自然语言法规转化为可执行逻辑，但受模糊性和幻觉影响，在法律关键场景中的可靠性仍面临挑战。我们提出了一种智能体方法用于开发法律关键软件，并以美国联邦税务申报为案例展开研究。核心挑战在于预言机问题下的测试用例生成——此时正确输出需以法律解释为基础。基于变形测试，我们提出高阶变形关系，通过相似个体间的结构化差异来对比系统输出。由于编写这类关系繁琐且易出错，我们采用大型语言模型驱动的角色化框架，实现测试生成与代码合成的自动化。我们构建了多智能体系统，可将税法转化为可执行软件，并集成变形测试智能体以搜索反例。实验表明，我们基于较小模型（GPT-4o-mini）的框架最坏情况下通过率达45%，在复杂税法任务上性能超过前沿模型（GPT-4o和Claude 3.5，9-15%）。这些结果证明，智能体式大型语言模型方法是将自然语言规范转化为稳健可信的法律关键软件的有效途径。

> Large language models (LLMs) show promise for translating natural-language statutes into executable logic, but reliability in legally critical settings remains challenging due to ambiguity and hallucinations. We present an agentic approach for developing legal-critical software, using U.S. federal tax preparation as a case study. The key challenge is test-case generation under the oracle problem, where correct outputs require interpreting law. Building on metamorphic testing, we introduce higher-order metamorphic relations that compare system outputs across structured shifts among similar individuals. Because authoring such relations is tedious and error-prone, we use an LLM-driven, role-based framework to automate test generation and code synthesis. We implement a multi-agent system that translates tax code into executable software and incorporates a metamorphic-testing agent that searches for counterexamples. In experiments, our framework using a smaller model (GPT-4o-mini) achieves a worst-case pass rate of 45%, outperforming frontier models (GPT-4o and Claude 3.5, 9-15%) on complex tax-code tasks. These results support agentic LLM methodologies as a path to robust, trustworthy legal-critical software from natural-language specifications.

[Arxiv](https://arxiv.org/abs/2509.13471)