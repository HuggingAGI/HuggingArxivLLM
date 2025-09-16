# CodeCureAgent：静态分析警告的自动分类与修复

发布时间：2025年09月15日

`Agent` `工业与制造`

> CodeCureAgent: Automatic Classification and Repair of Static Analysis Warnings

# 摘要

> 静态分析工具广泛用于检测代码中的错误、漏洞与异味。传统上，这些警告需开发人员手动修复——由于过程繁琐，他们时常选择忽略，最终导致警告堆积、代码质量下滑。本文提出智能修复工具CodeCureAgent，它借助基于LLM的智能体自动完成静态分析警告的分析、分类与修复。不同于传统方法依赖预设算法，我们采用智能体框架：通过迭代调用工具（如代码搜索）从代码库中挖掘更多信息，进而编辑代码以消除警告。CodeCureAgent能精准识别并过滤误报，同时对确认真报进行修复。我们为其设计了三步启发式补丁验证流程：（1）构建项目；（2）确认警告已消失且未引入新警告；（3）运行测试套件。在包含106个Java项目、1000条SonarQube警告（覆盖291条规则）的数据集上测试发现，CodeCureAgent对96.8%的警告能生成合理修复方案，合理修复率分别超越当前最先进基线方法30.7%和29.2%。对291个案例的人工核查显示，其正确修复率高达86.3%，充分证明了修复的可靠性。该工具的LLM成本约2.9美分（美元），单个警告的端到端处理仅需四分钟。我们期望CodeCureAgent能助力清理存量代码库，并集成到CI/CD流水线中，从源头避免静态分析警告的堆积。

> Static analysis tools are widely used to detect bugs, vulnerabilities, and code smells. Traditionally, developers must resolve these warnings manually. Because this process is tedious, developers sometimes ignore warnings, leading to an accumulation of warnings and a degradation of code quality. This paper presents CodeCureAgent, an approach that harnesses LLM-based agents to automatically analyze, classify, and repair static analysis warnings. Unlike previous work, our method does not follow a predetermined algorithm. Instead, we adopt an agentic framework that iteratively invokes tools to gather additional information from the codebase (e.g., via code search) and edit the codebase to resolve the warning. CodeCureAgent detects and suppresses false positives, while fixing true positives when identified. We equip CodeCureAgent with a three-step heuristic to approve patches: (1) build the project, (2) verify that the warning disappears without introducing new warnings, and (3) run the test suite. We evaluate CodeCureAgent on a dataset of 1,000 SonarQube warnings found in 106 Java projects and covering 291 distinct rules. Our approach produces plausible fixes for 96.8% of the warnings, outperforming state-of-the-art baseline approaches by 30.7% and 29.2% in plausible-fix rate, respectively. Manual inspection of 291 cases reveals a correct-fix rate of 86.3%, showing that CodeCureAgent can reliably repair static analysis warnings. The approach incurs LLM costs of about 2.9 cents (USD) and an end-to-end processing time of about four minutes per warning. We envision CodeCureAgent helping to clean existing codebases and being integrated into CI/CD pipelines to prevent the accumulation of static analysis warnings.

[Arxiv](https://arxiv.org/abs/2509.11787)