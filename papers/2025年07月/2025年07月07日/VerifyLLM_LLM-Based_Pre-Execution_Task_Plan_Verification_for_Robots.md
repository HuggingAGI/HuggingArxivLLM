# VerifyLLM：基于LLM的机器人任务计划执行前验证系统

发布时间：2025年07月07日

`LLM应用` `机器人`

> VerifyLLM: LLM-Based Pre-Execution Task Plan Verification for Robots

# 摘要

> 在机器人领域，可靠且高效的规划是研究人员面临的重大挑战。在执行前验证高阶任务规划能够显著减少错误，从而提升系统整体性能。本文提出了一种创新架构，用于在仿真或真实环境中自动验证高阶任务规划。我们的方法基于大型语言模型（LLMs），包含两个关键步骤：首先将自然语言指令转换为线性时序逻辑（LTL），然后对动作序列进行详细分析。该模块利用LLM的推理能力来评估逻辑连贯性并识别计划中的潜在漏洞。在不同复杂度的数据集上的严格测试证明了该模块在家务任务中的广泛应用潜力。我们通过提升规划可靠性和效率，为自主系统提供了关键的预执行验证解决方案。代码可在https://verifyllm.github.io获取。

> In the field of robotics, researchers face a critical challenge in ensuring reliable and efficient task planning. Verifying high-level task plans before execution significantly reduces errors and enhance the overall performance of these systems. In this paper, we propose an architecture for automatically verifying high-level task plans before their execution in simulator or real-world environments. Leveraging Large Language Models (LLMs), our approach consists of two key steps: first, the conversion of natural language instructions into Linear Temporal Logic (LTL), followed by a comprehensive analysis of action sequences. The module uses the reasoning capabilities of the LLM to evaluate logical coherence and identify potential gaps in the plan. Rigorous testing on datasets of varying complexity demonstrates the broad applicability of the module to household tasks. We contribute to improving the reliability and efficiency of task planning and addresses the critical need for robust pre-execution verification in autonomous systems. The code is available at https://verifyllm.github.io.

[Arxiv](https://arxiv.org/abs/2507.05118)