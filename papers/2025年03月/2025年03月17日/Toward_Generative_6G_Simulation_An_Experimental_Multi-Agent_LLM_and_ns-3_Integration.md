# 探索生成式6G仿真：实验性多智能体LLM与ns-3集成

发布时间：2025年03月17日

`Agent`

> Toward Generative 6G Simulation: An Experimental Multi-Agent LLM and ns-3 Integration

# 摘要

> 迈向开放的第六代（6G）网络，我们需要一种全新的全栈仿真环境方法，在实际原型设计和现实世界实现之前，全面评估复杂的技术发展。本文提出了一种创新方法ootnote{GitHub上提供了一个轻量级的代码模拟版本，该版本结合了多智能体框架与ns-3网络仿真器，实现复杂5G网络场景的自动化生成、调试、执行和分析。我们的框架通过先进的LangChain协调机制，协调一系列专业智能体——仿真生成智能体、测试设计智能体、测试执行智能体和结果解释智能体。仿真生成智能体采用结构化的链式推理（CoT）过程，结合LLMs和检索增强生成（RAG），将自然语言的仿真规范转化为精确的ns-3脚本。测试设计智能体通过整合知识检索技术和动态测试用例合成，生成全面的自动化测试套件。测试执行智能体则负责动态部署和运行仿真，管理依赖关系并解析详细的性能指标。结果解释智能体利用LLM驱动的分析，从仿真输出中提取可操作的见解。通过整合外部资源，如库文档和ns-3测试框架，我们的方法能够提高仿真精度和适应性，减少对广泛编程专业知识的依赖。使用ns-3的5G-LENA模块进行的详细案例研究验证了所提方法的有效性。实验结果显示，代码生成过程平均收敛于1.8次迭代，语法错误率为17.0%，平均响应时间为7.3秒，并获得了7.5的人类评估分数。

> The move toward open Sixth-Generation (6G) networks necessitates a novel approach to full-stack simulation environments for evaluating complex technology developments before prototyping and real-world implementation. This paper introduces an innovative approach\footnote{A lightweight, mock version of the code is available on GitHub at that combines a multi-agent framework with the Network Simulator 3 (ns-3) to automate and optimize the generation, debugging, execution, and analysis of complex 5G network scenarios. Our framework orchestrates a suite of specialized agents -- namely, the Simulation Generation Agent, Test Designer Agent, Test Executor Agent, and Result Interpretation Agent -- using advanced LangChain coordination. The Simulation Generation Agent employs a structured chain-of-thought (CoT) reasoning process, leveraging LLMs and retrieval-augmented generation (RAG) to translate natural language simulation specifications into precise ns-3 scripts. Concurrently, the Test Designer Agent generates comprehensive automated test suites by integrating knowledge retrieval techniques with dynamic test case synthesis. The Test Executor Agent dynamically deploys and runs simulations, managing dependencies and parsing detailed performance metrics. At the same time, the Result Interpretation Agent utilizes LLM-driven analysis to extract actionable insights from the simulation outputs. By integrating external resources such as library documentation and ns-3 testing frameworks, our experimental approach can enhance simulation accuracy and adaptability, reducing reliance on extensive programming expertise. A detailed case study using the ns-3 5G-LENA module validates the effectiveness of the proposed approach. The code generation process converges in an average of 1.8 iterations, has a syntax error rate of 17.0%, a mean response time of 7.3 seconds, and receives a human evaluation score of 7.5.

[Arxiv](https://arxiv.org/abs/2503.13402)