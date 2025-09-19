# 利用大型语言模型实现Modelica模块生成自动化：以建筑控制描述语言为例的案例研究

发布时间：2025年09月18日

`LLM应用` `能源与环保`

> Automating Modelica Module Generation Using Large Language Models: A Case Study on Building Control Description Language

# 摘要

> 动态能源系统与控制领域需要先进的建模框架，以设计和测试监控及容错策略。Modelica是一种广泛应用的基于方程的语言，但其控制模块的开发不仅耗时费力，还需要专业知识。本文以建筑Modelica库中控制描述语言模块的自动生成为案例，探讨了大型语言模型（LLMs）的应用。我们开发了一种结构化工作流，整合了标准化提示框架、库感知基础、基于OpenModelica的自动编译以及人在回路评估。实验围绕四个基本逻辑任务（与、或、非、切换）和五个控制模块（冷水机组启停、旁通阀控制、冷却塔风扇转速、设备请求及泄压风门控制）展开。结果显示，GPT-4o在零样本模式下无法生成可执行的Modelica代码；而Claude Sonnet 4在精心设计提示词的情况下，基本逻辑块的成功率可达100%。在控制模块方面，成功率达83%，失败的输出则需要中等程度的人工修复（预计1至8小时）。检索增强生成在模块选择时频繁出现匹配错误（如误将“与”检索为“或”），而确定性硬规则搜索策略则可避免此类错误。人工评估的表现同样优于AI评估，原因是当前LLMs无法评估仿真结果或验证行为的正确性。尽管存在这些局限，LLM辅助工作流仍将每个模块的平均开发时间从10至20小时缩短至4至6小时，节省了40%至60%的时间。这些结果既凸显了LLM辅助Modelica生成的潜力，也揭示了其当前的局限性，并为未来在仿真前验证、更强基础构建及闭环评估等方向的研究提供了思路。

> Dynamic energy systems and controls require advanced modeling frameworks to design and test supervisory and fault tolerant strategies. Modelica is a widely used equation based language, but developing control modules is labor intensive and requires specialized expertise. This paper examines the use of large language models (LLMs) to automate the generation of Control Description Language modules in the Building Modelica Library as a case study. We developed a structured workflow that combines standardized prompt scaffolds, library aware grounding, automated compilation with OpenModelica, and human in the loop evaluation. Experiments were carried out on four basic logic tasks (And, Or, Not, and Switch) and five control modules (chiller enable/disable, bypass valve control, cooling tower fan speed, plant requests, and relief damper control). The results showed that GPT 4o failed to produce executable Modelica code in zero shot mode, while Claude Sonnet 4 achieved up to full success for basic logic blocks with carefully engineered prompts. For control modules, success rates reached 83 percent, and failed outputs required medium level human repair (estimated one to eight hours). Retrieval augmented generation often produced mismatches in module selection (for example, And retrieved as Or), while a deterministic hard rule search strategy avoided these errors. Human evaluation also outperformed AI evaluation, since current LLMs cannot assess simulation results or validate behavioral correctness. Despite these limitations, the LLM assisted workflow reduced the average development time from 10 to 20 hours down to 4 to 6 hours per module, corresponding to 40 to 60 percent time savings. These results highlight both the potential and current limitations of LLM assisted Modelica generation, and point to future research in pre simulation validation, stronger grounding, and closed loop evaluation.

[Arxiv](https://arxiv.org/abs/2509.14623)