# 基于大型语言模型的蛋白质分子动力学模拟自动化：NAMD-Agent

发布时间：2025年07月10日

`LLM应用` `计算结构生物学` `生物信息学`

> Automating MD simulations for Proteins using Large language Models: NAMD-Agent

# 摘要

> 分子动力学模拟是研究蛋白质结构、动力学与功能在原子尺度上的不可或缺的工具。然而，准备高质量的MD模拟输入文件往往耗时费力且容易出错。本研究提出了一条创新的自动化管道，结合大型语言模型（LLMs）——特别是Gemini 2.0 Flash，以及Python脚本和基于Selenium的网络自动化技术，大幅简化了MD输入文件的生成流程。该管道巧妙运用CHARMM GUI的全面网络界面，为NAMD准备模拟就绪的输入文件。通过整合Gemini的代码生成与迭代优化能力，模拟脚本能够自动编写、执行并修改，从而实现对CHARMM GUI的智能导航、提取合适参数并生成所需的NAMD输入文件。借助额外软件进行后处理，进一步优化模拟输出，从而实现一个完整且几乎无需手动干预的工作流程。我们的实验结果表明，这种方法不仅显著缩短了设置时间，减少了人为错误，还提供了一个可扩展的解决方案，能够同时处理多个蛋白质系统。这一自动化框架为大型语言模型在计算结构生物学中的广泛应用开辟了道路，提供了一个强大且灵活的平台，为未来模拟自动化的进一步发展奠定了坚实基础。

> Molecular dynamics simulations are an essential tool in understanding protein structure, dynamics, and function at the atomic level. However, preparing high quality input files for MD simulations can be a time consuming and error prone process. In this work, we introduce an automated pipeline that leverages Large Language Models (LLMs), specifically Gemini 2.0 Flash, in conjunction with python scripting and Selenium based web automation to streamline the generation of MD input files. The pipeline exploits CHARMM GUI's comprehensive web-based interface for preparing simulation-ready inputs for NAMD. By integrating Gemini's code generation and iterative refinement capabilities, simulation scripts are automatically written, executed, and revised to navigate CHARMM GUI, extract appropriate parameters, and produce the required NAMD input files. Post processing is performed using additional software to further refine the simulation outputs, thereby enabling a complete and largely hands free workflow. Our results demonstrate that this approach reduces setup time, minimizes manual errors, and offers a scalable solution for handling multiple protein systems in parallel. This automated framework paves the way for broader application of LLMs in computational structural biology, offering a robust and adaptable platform for future developments in simulation automation.

[Arxiv](https://arxiv.org/abs/2507.07887)