# AnalogXpert：将电路设计专长注入大型语言模型，自动化模拟拓扑合成

发布时间：2024年12月17日

`Agent

理由：这篇论文提出了一个名为AnalogXpert的基于LLM的代理，旨在解决模拟电路拓扑合成的实际问题。论文中详细描述了如何将电路设计专业知识融入LLM，并通过CoT和上下文学习技术将问题分解为子任务，模拟实际设计流程。此外，还引入了校对策略，使LLM能够逐步修正初始设计中的错误。这些内容表明，该论文主要关注的是如何构建一个能够执行特定任务的智能代理（Agent），而不是单纯的理论研究或LLM的应用。因此，将其分类为“Agent”是合适的。` `电子工程` `电路设计`

> AnalogXpert: Automating Analog Topology Synthesis by Incorporating Circuit Design Expertise into Large Language Models

# 摘要

> # 摘要
模拟电路在现代电子系统中扮演着关键角色，其设计的自动化吸引了大量研究关注。拓扑合成作为主要挑战之一，涉及电路组件及其连接的确定。近期研究探索了利用大型语言模型（LLM）进行拓扑合成，但这些研究的情景与实际应用存在较大差距。现有方法通常以模糊的设计要求为输入，输出理想模型，而实际应用中更需要详细的结构要求和设备级模型。此外，当前方法将拓扑合成简化为图生成或Python代码生成，而实际拓扑设计是一个复杂且需要丰富设计知识的过程。为此，我们提出了AnalogXpert，一个基于LLM的代理，旨在通过将电路设计专业知识融入LLM来解决实际的拓扑合成问题。首先，我们将模拟拓扑表示为SPICE代码，并引入子电路库以缩小设计空间，这与经验丰富的设计师的做法一致。其次，我们通过CoT和上下文学习技术将问题分解为块选择和块连接两个子任务，以模拟实际设计流程。第三，我们引入了一种校对策略，使LLM能够逐步修正初始设计中的错误，类似于人类设计师的迭代检查和调整过程。最后，我们构建了一个包含30个真实数据和2000个合成数据的高质量基准。AnalogXpert在合成数据集和真实数据集上的成功率分别为40%和23%，显著优于GPT-4o（在合成数据集和真实数据集上的成功率均为3%）。

> Analog circuits are crucial in modern electronic systems, and automating their design has attracted significant research interest. One of major challenges is topology synthesis, which determines circuit components and their connections. Recent studies explore large language models (LLM) for topology synthesis. However, the scenarios addressed by these studies do not align well with practical applications. Specifically, existing work uses vague design requirements as input and outputs an ideal model, but detailed structural requirements and device-level models are more practical. Moreover, current approaches either formulate topology synthesis as graph generation or Python code generation, whereas practical topology design is a complex process that demands extensive design knowledge. In this work, we propose AnalogXpert, a LLM-based agent aiming at solving practical topology synthesis problem by incorporating circuit design expertise into LLMs. First, we represent analog topology as SPICE code and introduce a subcircuit library to reduce the design space, in the same manner as experienced designers. Second, we decompose the problem into two sub-task (i.e., block selection and block connection) through the use of CoT and incontext learning techniques, to mimic the practical design process. Third, we introduce a proofreading strategy that allows LLMs to incrementally correct the errors in the initial design, akin to human designers who iteratively check and adjust the initial topology design to ensure accuracy. Finally, we construct a high-quality benchmark containing both real data (30) and synthetic data (2k). AnalogXpert achieves 40% and 23% success rates on the synthetic dataset and real dataset respectively, which is markedly better than those of GPT-4o (3% on both the synthetic dataset and the real dataset).

[Arxiv](https://arxiv.org/abs/2412.19824)