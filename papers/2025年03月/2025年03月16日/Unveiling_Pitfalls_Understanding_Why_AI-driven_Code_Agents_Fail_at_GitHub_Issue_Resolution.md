# 揭开AI代码代理在GitHub问题解决中的失败之谜：深入解析背后的陷阱与原因

发布时间：2025年03月16日

`LLM应用` `软件工程` `基准测试`

> Unveiling Pitfalls: Understanding Why AI-driven Code Agents Fail at GitHub Issue Resolution

# 摘要

> 人工智能驱动的软件开发正随着软件开发代理的涌现而快速发展，这些代理利用大型语言模型（LLMs）处理复杂的仓库级软件工程任务。这些代理不仅生成最终代码，还进行多步骤推理，利用多种工具进行代码修改和调试，并与执行环境交互以诊断和迭代解决问题。然而，现有大多数评估主要关注最终代码输出的静态分析，对代理动态解决问题过程的洞察有限。为此，我们对SWE-Bench基准测试中评估的8个顶级代理在500个GitHub问题上的3,977个解决阶段轨迹和3,931个测试阶段日志开展了深入的实证研究。我们的探索性分析显示，在问题解决阶段出现的Python执行错误与较低的解决率和增加的推理开销相关。我们发现最常见的错误，如ModuleNotFoundError和TypeError，并特别指出了一些特别具有挑战性的错误，如OSError和与数据库相关的问题（例如IntegrityError），这些问题需要显著更多的调试努力。此外，我们在SWE-Bench平台上发现了3个影响基准测试公平性和准确性的漏洞；这些问题已报告给维护者并得到确认。为了促进透明度并推动未来的研究，我们公开分享了我们的数据集和分析脚本。

> AI-driven software development has rapidly advanced with the emergence of software development agents that leverage large language models (LLMs) to tackle complex, repository-level software engineering tasks. These agents go beyond just generation of final code; they engage in multi-step reasoning, utilize various tools for code modification and debugging, and interact with execution environments to diagnose and iteratively resolve issues. However, most existing evaluations focus primarily on static analyses of final code outputs, yielding limited insights into the agents' dynamic problem-solving processes. To fill this gap, we conduct an in-depth empirical study on 3,977 solving-phase trajectories and 3,931 testing-phase logs from 8 top-ranked agents evaluated on 500 GitHub issues in the SWE-Bench benchmark. Our exploratory analysis shows that Python execution errors during the issue resolution phase correlate with lower resolution rates and increased reasoning overheads. We have identified the most prevalent errors -- such as ModuleNotFoundError and TypeError -- and highlighted particularly challenging errors like OSError and database-related issues (e.g., IntegrityError) that demand significantly more debugging effort. Furthermore, we have discovered 3 bugs in the SWE-Bench platform that affect benchmark fairness and accuracy; these issues have been reported to and confirmed by the maintainers. To promote transparency and foster future research, we publicly share our datasets and analysis scripts.

[Arxiv](https://arxiv.org/abs/2503.12374)