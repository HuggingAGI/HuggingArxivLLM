# # SetupBench：用于评估软件工程代理启动开发环境能力的基准测试

发布时间：2025年07月11日

`LLM应用` `软件开发`

> SetupBench: Assessing Software Engineering Agents' Ability to Bootstrap Development Environments

# 摘要

> 现代大型语言模型（LLM）代理能够为现实世界的软件任务提供端到端的辅助支持，但现有评估基准几乎全部依赖于预构建环境，所有依赖项均已预先安装。为了弥补这一研究空白，我们推出SetupBench——一个包含93个实例的基准测试，专注于评估代理的环境启动能力：从裸机Linux沙盒环境出发，代理需完成软件包安装、依赖冲突解决、数据库初始化及后台服务配置。我们的任务覆盖七种编程语言生态系统、五种数据库引擎以及多种服务编排场景，每个任务均配有自然语言问题描述和确定性的成功验证命令。通过对最先进的编码代理OpenHands进行评估，我们发现其在各类任务中的成功率普遍偏低，尤其在仓库设置（38.9-57.4%）和本地数据库配置（20.0-53.3%）方面面临较大挑战。深入分析发现，系统性失败模式包括开发工具链安装不完整、虚构的任务约束以及破坏性环境修改，这些都会干扰代理与人类的协作流程。研究还指出，代理的探索策略存在显著低效，与最优人类操作相比，38-89%的操作被视为冗余。这些发现凸显了现有代理在实际环境启动能力上的不足。通过聚焦这一关键但尚未充分评估的能力，SetupBench为下一代致力于解决端到端现实任务的软件开发代理设定了严格的评估标准。

> Modern Large Language Model (LLM) agents promise end to end assistance with real-world software tasks, yet existing benchmarks evaluate LLM agents almost exclusively in pre-baked environments where every dependency is pre-installed. To fill this gap, we introduce SetupBench, a 93 instance benchmark that isolates the environment-bootstrap skill: starting from a bare Linux sandbox, an agent must install packages, resolve dependency conflicts, initialize databases, and configure background services. Our tasks span seven language ecosystems, five database engines, and multi-service orchestration scenarios, each accompanies by a natural language problem statement and a deterministic success command. Through evaluation of OpenHands, a state-of-the-art coding agent, we find low success rates across task categories, with particular challenges in repository setup (38.9-57.4%) and local database configuration (20.0-53.3%). Our analysis reveals systematic failure modes including incomplete development tooling installation, hallucinated task constraints, and non-persistent environment modifications that break agent-human collaboration workflows. We identify substantial inefficiencies in agent exploration strategies, with 38-89% of actions being unnecessary compared to optimal human behavior. These findings highlight gaps in current agents' practical environment-bootstrap capabilities. By targeting this critical yet under-evaluated capability, SetupBench provides a rigorous yard-stick for the next generation of software developer agents aiming to solve end to end real-wold tasks.

[Arxiv](https://arxiv.org/abs/2507.09063)