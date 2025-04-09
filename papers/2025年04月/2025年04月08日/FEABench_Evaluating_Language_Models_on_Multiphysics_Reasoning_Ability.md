# # FEABench：评估语言模型的多物理场推理能力

发布时间：2025年04月08日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在工程和科学领域中的应用，特别是在有限元分析（FEA）中的应用。论文介绍了FEABench基准测试平台，用于评估LLMs及其代理在解决FEA问题中的表现。虽然提到了代理（Agent）的概念，但主要关注点在于LLMs的应用和其在工程自动化中的潜力，因此归类为LLM应用。` `工程自动化`

> FEABench: Evaluating Language Models on Multiphysics Reasoning Ability

# 摘要

> 精确模拟现实世界并解答定量问题是工程和科学研究的核心需求。我们推出FEABench，一个评估大型语言模型（LLMs）及其代理在有限元分析（FEA）领域表现的基准测试平台。通过这套全面的评估方案，我们探究LLMs能否通过解析自然语言问题描述并操作COMSOL Multiphysics$^\circledR$（一款FEA软件）来实现端到端的问题解决。我们还开发了一个具备通过API与软件交互能力的语言模型代理，该代理能够审视输出结果并在多次迭代中优化解决方案。我们的最佳策略在88%的情况下能够生成可执行的API调用。成功实现与FEA软件交互并解决如基准测试中所示问题的LLMs，将推动工程自动化领域的前沿发展。这一能力将使LLMs的推理技能与数值求解器的精确性相结合，助力开发能够应对现实世界复杂问题的自主系统。代码可在https://github.com/google/feabench获取

> Building precise simulations of the real world and invoking numerical solvers to answer quantitative problems is an essential requirement in engineering and science. We present FEABench, a benchmark to evaluate the ability of large language models (LLMs) and LLM agents to simulate and solve physics, mathematics and engineering problems using finite element analysis (FEA). We introduce a comprehensive evaluation scheme to investigate the ability of LLMs to solve these problems end-to-end by reasoning over natural language problem descriptions and operating COMSOL Multiphysics$^\circledR$, an FEA software, to compute the answers. We additionally design a language model agent equipped with the ability to interact with the software through its Application Programming Interface (API), examine its outputs and use tools to improve its solutions over multiple iterations. Our best performing strategy generates executable API calls 88% of the time. LLMs that can successfully interact with and operate FEA software to solve problems such as those in our benchmark would push the frontiers of automation in engineering. Acquiring this capability would augment LLMs' reasoning skills with the precision of numerical solvers and advance the development of autonomous systems that can tackle complex problems in the real world. The code is available at https://github.com/google/feabench

[Arxiv](https://arxiv.org/abs/2504.06260)