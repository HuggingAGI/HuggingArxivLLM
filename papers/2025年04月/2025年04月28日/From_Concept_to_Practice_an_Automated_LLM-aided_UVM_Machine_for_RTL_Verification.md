# 从概念到实践：自动化LLM辅助UVM机器实现RTL验证

发布时间：2025年04月28日

`LLM应用

论文摘要：验证是集成电路（IC）开发中的主要瓶颈，占据了近70%的总开发工作量。通用验证方法（UVM）在行业中被广泛应用，通过结构化和可重用的测试台来提高验证效率，但构建这些测试台并生成足够的激励仍然具有挑战性。这些挑战源于需要大量的手动编码工作，多次手动执行多个EDA工具，以及需要深入的领域专业知识来处理复杂的设计。我们提出UVM²，一个利用大型语言模型（LLMs）生成UVM测试台并利用覆盖率反馈进行迭代优化的自动化验证框架，从而显著减少人工努力，同时保持严格的验证标准。为了评估UVM²，我们引入了一个基准测试套件，包含多达1.6千行代码的寄存器传输级（RTL）设计。结果显示，与经验丰富的工程师相比，UVM²将测试台设置时间减少了高达数学公式，并实现了平均代码和功能覆盖率分别为87.44%和89.58%，分别比现有最佳解决方案高出20.96%和23.51%。
LLM应用` `集成电路`

> From Concept to Practice: an Automated LLM-aided UVM Machine for RTL Verification

# 摘要

> 验证是集成电路（IC）开发中的主要瓶颈，占据了近70%的总开发工作量。通用验证方法（UVM）在行业中被广泛应用，通过结构化和可重用的测试台来提高验证效率，但构建这些测试台并生成足够的激励仍然具有挑战性。这些挑战源于需要大量的手动编码工作，多次手动执行多个EDA工具，以及需要深入的领域专业知识来处理复杂的设计。我们提出UVM²，一个利用大型语言模型（LLMs）生成UVM测试台并利用覆盖率反馈进行迭代优化的自动化验证框架，从而显著减少人工努力，同时保持严格的验证标准。为了评估UVM²，我们引入了一个基准测试套件，包含多达1.6千行代码的寄存器传输级（RTL）设计。结果显示，与经验丰富的工程师相比，UVM²将测试台设置时间减少了高达【数学公式】，并实现了平均代码和功能覆盖率分别为87.44%和89.58%，分别比现有最佳解决方案高出20.96%和23.51%。

> Verification presents a major bottleneck in Integrated Circuit (IC) development, consuming nearly 70% of the total development effort. While the Universal Verification Methodology (UVM) is widely used in industry to improve verification efficiency through structured and reusable testbenches, constructing these testbenches and generating sufficient stimuli remain challenging. These challenges arise from the considerable manual coding effort required, repetitive manual execution of multiple EDA tools, and the need for in-depth domain expertise to navigate complex designs.Here, we present UVM^2, an automated verification framework that leverages Large Language Models (LLMs) to generate UVM testbenches and iteratively refine them using coverage feedback, significantly reducing manual effort while maintaining rigorous verification standards.To evaluate UVM^2, we introduce a benchmark suite comprising Register Transfer Level (RTL) designs of up to 1.6K lines of code.The results show that UVM^2 reduces testbench setup time by up to UVM^2 compared to experienced engineers, and achieve average code and function coverage of 87.44% and 89.58%, outperforming state-of-the-art solutions by 20.96% and 23.51%, respectively.

[Arxiv](https://arxiv.org/abs/2504.19959)