# 仿真引导的LLM代码生成用于安全自动驾驶软件

发布时间：2025年04月02日

`LLM应用` `自动驾驶`

> On Simulation-Guided LLM-based Code Generation for Safe Autonomous Driving Software

# 摘要

> 自动驾驶系统 (ADS) 是一个安全关键型软件系统，负责解析车辆环境并据此做出决策。由于驾驶环境的复杂性无界且不可预见，持续改进成为必要，通常通过迭代的 DevOps 流程来实现。然而，DevOps 流程的复杂性使得改进既耗时又耗资源。利用大型语言模型 (LLM) 自动化 ADS 的代码生成是解决这一挑战的一个潜在方法。然而，ADS 的开发需要严格的流程来验证、确认、评估和认证代码，才能将其部署到车辆中使用。

在这项研究中，我们在工业环境中开发并评估了一个原型，用于自动代码生成和评估，采用了一个基于 LLM 的代理、仿真模型和基于规则的反馈生成器的流水线设计。LLM 生成的代码在仿真模型中针对多个关键交通场景进行自动评估，并生成评估报告作为反馈提供给 LLM 进行修改或修复。我们报告了使用 Codellama:34b、DeepSeek (r1:32b 和 Coder:33b)、CodeGemma:7b、Mistral:7b 和 GPT4 进行自适应巡航控制 (ACC) 和无监督避障紧急变道 (CAEM) 的原型实验结果。最后，我们通过访谈研究在两家原始设备制造商 (OEM) 中对 11 位专家进行了工具评估。

> Automated Driving System (ADS) is a safety-critical software system responsible for the interpretation of the vehicle's environment and making decisions accordingly. The unbounded complexity of the driving context, including unforeseeable events, necessitate continuous improvement, often achieved through iterative DevOps processes. However, DevOps processes are themselves complex, making these improvements both time- and resource-intensive. Automation in code generation for ADS using Large Language Models (LLM) is one potential approach to address this challenge. Nevertheless, the development of ADS requires rigorous processes to verify, validate, assess, and qualify the code before it can be deployed in the vehicle and used. In this study, we developed and evaluated a prototype for automatic code generation and assessment using a designed pipeline of a LLM-based agent, simulation model, and rule-based feedback generator in an industrial setup. The LLM-generated code is evaluated automatically in a simulation model against multiple critical traffic scenarios, and an assessment report is provided as feedback to the LLM for modification or bug fixing. We report about the experimental results of the prototype employing Codellama:34b, DeepSeek (r1:32b and Coder:33b), CodeGemma:7b, Mistral:7b, and GPT4 for Adaptive Cruise Control (ACC) and Unsupervised Collision Avoidance by Evasive Manoeuvre (CAEM). We finally assessed the tool with 11 experts at two Original Equipment Manufacturers (OEMs) by conducting an interview study.

[Arxiv](https://arxiv.org/abs/2504.02141)