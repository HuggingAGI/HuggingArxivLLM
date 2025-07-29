# MCP4EDA：LLM驱动的模型上下文协议RTL到GDSII自动化，并实现后端感知的综合优化

发布时间：2025年07月25日

`LLM应用` `电子设计自动化` `EDA`

> MCP4EDA: LLM-Powered Model Context Protocol RTL-to-GDSII Automation with Backend Aware Synthesis Optimization

# 摘要

> 本文介绍MCP4EDA，首个通过自然语言交互实现LLMs对完整开源RTL-to-GDSII设计流程控制与优化的模型上下文协议服务器。该系统将Yosys综合、Icarus Verilog仿真、OpenLane布图与布线、GTKWave分析和KLayout可视化整合为统一的LLM可访问界面，让设计师能够通过Claude Desktop和Cursor IDE等AI助手，以对话方式执行复杂的多工具EDA工作流程。其核心贡献是一种后端感知的综合优化方法，LLMs基于OpenLane结果中的实际布局后时序、功耗和面积指标，迭代优化综合TCL脚本，从而构建闭环优化系统，有效弥合传统综合估计与物理实现现实的差距。与依赖线负载模型的传统方法不同，本方法利用真实后端性能数据指导综合参数调整、优化序列选择和约束细化，LLMs在此过程中充当智能设计空间探索代理。实验评估显示，在代表性数字设计中，该系统较默认综合流程实现15-30%的时序闭合提升和10-20%的面积缩减，确立了MCP4EDA作为首个实用LLM控制端到端开源EDA自动化系统的地位。代码和演示请访问：http://www.agent4eda.com/

> This paper presents MCP4EDA, the first Model Context Protocol server that enables Large Language Models (LLMs) to control and optimize the complete open-source RTL-to-GDSII design flow through natural language interaction. The system integrates Yosys synthesis, Icarus Verilog simulation, OpenLane place-and-route, GTKWave analysis, and KLayout visualization into a unified LLM-accessible interface, enabling designers to execute complex multi-tool EDA workflows conversationally via AI assistants such as Claude Desktop and Cursor IDE. The principal contribution is a backend-aware synthesis optimization methodology wherein LLMs analyze actual post-layout timing, power, and area metrics from OpenLane results to iteratively refine synthesis TCL scripts, establishing a closed-loop optimization system that bridges the traditional gap between synthesis estimates and physical implementation reality. In contrast to conventional flows that rely on wire-load models, this methodology leverages real backend performance data to guide synthesis parameter tuning, optimization sequence selection, and constraint refinement, with the LLM functioning as an intelligent design space exploration agent. Experimental evaluation on representative digital designs demonstrates 15-30% improvements in timing closure and 10-20% area reduction compared to default synthesis flows, establishing MCP4EDA as the first practical LLM-controlled end-to-end open-source EDA automation system. The code and demo are avaiable at: http://www.agent4eda.com/

[Arxiv](https://arxiv.org/abs/2507.19570)