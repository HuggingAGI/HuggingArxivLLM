# 验证带来的启示：基于强化学习与测试bench反馈训练Verilog生成LLM

发布时间：2025年04月22日

`LLM应用

摘要讨论了将大型语言模型应用于生成Verilog代码，并通过验证和强化学习来提高代码正确性，属于LLM的应用层面创新。` `电子设计自动化（EDA）` `人工智能（AI）`

> Insights from Verification: Training a Verilog Generation LLM with Reinforcement Learning with Testbench Feedback

# 摘要

> 大型语言模型（LLMs）在自然语言描述到Verilog代码的生成任务中表现出色。然而，确保生成代码的功能正确性仍然是一个重大挑战。本文提出了一种创新方法，通过将测试台的验证见解融入Verilog生成LLMs的训练过程，使训练目标与硬件设计的核心目标——功能正确性——相一致。使用LLMs进行Verilog代码生成的主要障碍是缺乏足够的功能性验证数据，特别是与设计规范和代码配对的测试台。为了解决这一难题，我们开发了一个自动测试台生成管道，该管道通过分解生成过程并利用Verilog编译器模拟器（VCS）的反馈，有效减少幻觉现象，确保代码正确性。随后，我们利用生成的测试台对代码进行评估，并将其收集用于进一步训练，在此过程中引入验证见解。我们的方法采用强化学习（RL）技术，特别是直接偏好优化（DPO），通过基于测试台结果训练偏好对，使Verilog代码生成与功能正确性相一致。在VerilogEval-Machine、VerilogEval-Human、RTLLM v1.1、RTLLM v2和VerilogEval v2的评估中，我们的方法在生成功能正确的Verilog代码方面始终优于最先进的基线。所有训练代码、数据和模型均已开源，地址为https://anonymous.4open.science/r/VeriPrefer-E88B。

> Large language models (LLMs) have shown strong performance in Verilog generation from natural language description. However, ensuring the functional correctness of the generated code remains a significant challenge. This paper introduces a method that integrates verification insights from testbench into the training of Verilog generation LLMs, aligning the training with the fundamental goal of hardware design: functional correctness. The main obstacle in using LLMs for Verilog code generation is the lack of sufficient functional verification data, particularly testbenches paired with design specifications and code. To address this problem, we introduce an automatic testbench generation pipeline that decomposes the process and uses feedback from the Verilog compiler simulator (VCS) to reduce hallucination and ensure correctness. We then use the testbench to evaluate the generated codes and collect them for further training, where verification insights are introduced. Our method applies reinforcement learning (RL), specifically direct preference optimization (DPO), to align Verilog code generation with functional correctness by training preference pairs based on testbench outcomes. In evaluations on VerilogEval-Machine, VerilogEval-Human, RTLLM v1.1, RTLLM v2, and VerilogEval v2, our approach consistently outperforms state-of-the-art baselines in generating functionally correct Verilog code. We open source all training code, data, and models at https://anonymous.4open.science/r/VeriPrefer-E88B.

[Arxiv](https://arxiv.org/abs/2504.15804)