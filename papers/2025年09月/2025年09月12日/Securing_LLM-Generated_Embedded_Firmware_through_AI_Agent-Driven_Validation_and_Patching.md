# 基于AI智能体驱动的验证与修补保障LLM生成嵌入式固件的安全

发布时间：2025年09月12日

`Agent` `工业与制造`

> Securing LLM-Generated Embedded Firmware through AI Agent-Driven Validation and Patching

# 摘要

> 大型语言模型（LLMs）在生成嵌入式系统固件方面展现出潜力，但其生成的固件常存在安全漏洞，且难以满足实时性能要求。本文提出一种三阶段方法，将基于LLM的固件生成、自动化安全验证与虚拟化环境中的迭代优化相融合。借助结构化提示词，GPT-4等模型可生成网络及控制任务固件，并通过QEMU部署至FreeRTOS系统。这些固件实现方案通过模糊测试、静态分析及运行时监控进行检测，可识别缓冲区溢出（CWE-120）、竞态条件（CWE-362）、拒绝服务威胁（CWE-400）等漏洞。专用AI智能体（负责威胁检测、性能优化与合规性验证）协同工作，提升漏洞检测与修复效率。已发现的问题按CWE标准分类后，会用于迭代循环中，引导LLM生成针对性补丁。实验结果显示，漏洞修复率达92.4%（提升37.3%），威胁模型合规率为95.8%，安全覆盖指数为0.87。实时性能指标包括8.6毫秒的最坏情况执行时间与195微秒的抖动。该流程在提升固件安全性与性能的同时，还为后续研究提供了开源数据集。

> Large Language Models (LLMs) show promise in generating firmware for embedded systems, but often introduce security flaws and fail to meet real-time performance constraints. This paper proposes a three-phase methodology that combines LLM-based firmware generation with automated security validation and iterative refinement in a virtualized environment. Using structured prompts, models like GPT-4 generate firmware for networking and control tasks, deployed on FreeRTOS via QEMU. These implementations are tested using fuzzing, static analysis, and runtime monitoring to detect vulnerabilities such as buffer overflows (CWE-120), race conditions (CWE-362), and denial-of-service threats (CWE-400). Specialized AI agents for Threat Detection, Performance Optimization, and Compliance Verification collaborate to improve detection and remediation. Identified issues are categorized using CWE, then used to prompt targeted LLM-generated patches in an iterative loop. Experiments show a 92.4\% Vulnerability Remediation Rate (37.3\% improvement), 95.8\% Threat Model Compliance, and 0.87 Security Coverage Index. Real-time metrics include 8.6ms worst-case execution time and 195μs jitter. This process enhances firmware security and performance while contributing an open-source dataset for future research.

[Arxiv](https://arxiv.org/abs/2509.09970)