# # NordDRG 大语言模型 AI 基准测试

发布时间：2025年06月11日

`LLM应用` `医疗支付`

> The NordDRG AI Benchmark for Large Language Models

# 摘要

> 大型语言模型（LLMs）已在临床编码与决策支持领域开展试点应用。然而，目前尚未有公开基准专注于医院资金层，其中诊断相关组（DRG）决定着许多国家的报销标准。我们推出NordDRG-AI-Benchmark，这是首个公开测试平台，完整捕捉DRG规则集，并评估LLM在多语言诊断、程序及费率逻辑推理中的能力。该基准包含三类核心组件：（i）20个相互关联的定义表，涵盖DRG逻辑、ICD与NCSP代码、年龄性别划分及国家标志；（ii）描述真实治理流程的专家手册与变更日志模板；（iii）14个案例混合任务提示包，涉及代码查找、跨表推理、多语言术语及质量审核。所有组件均已开源：https://github.com/longshoreforrest/norddrg-ai-benchmark。基线测试显示，五款先进LLMs在九项自动验证任务中表现迥异：o3（OpenAI）满分通过，GPT-4o与o4-mini-high获7分，而Gemini 2.5 Pro与Flash分别完成5项与3项任务。这些结果表明，NordDRG-AI-Benchmark精准揭示了领域特定的优劣势，超越了通用LLM基准的局限，为医院资金可信自动化研究提供了可复现的基线.

> Large language models (LLMs) are already being piloted for clinical coding and decision support. However, until now, no open benchmark has targeted the hospital funding layer where Diagnosis-Related Groups (DRG) determine reimbursement across many countries. We release NordDRG-AI-Benchmark, the first public test-bed that captures a complete DRG rule set and evaluates an LLM's ability to reason over multilingual diagnosis, procedure, and tariff logic.
  The benchmark bundles three classes of artefacts: (i) definition tables with 20 interlinked tables covering DRG logic, ICD and NCSP codes, age/sex splits, and country flags; (ii) expert manuals and changelog templates describing real governance workflows; and (iii) a prompt pack of 14 CaseMix tasks that span code lookup, cross-table inference, multilingual terminology, and quality-assurance audits.
  All artefacts are available at: https://github.com/longshoreforrest/norddrg-ai-benchmark
  A baseline demonstration shows that five state-of-the-art LLMs perform very differently on the nine automatically verifiable tasks: o3 (OpenAI) scores 9 out of 9, GPT-4o and o4-mini-high score 7 out of 9, while Gemini 2.5 Pro and Gemini 2.5 Flash solve only 5 out of 9 and 3 out of 9, respectively. These results confirm that NordDRG-AI-Benchmark highlights domain-specific strengths and weaknesses that remain hidden in generic LLM benchmarks, offering a reproducible baseline for research on trustworthy automation in hospital funding.

[Arxiv](https://arxiv.org/abs/2506.13790)