# LLM驱动的可靠Docker环境配置代理

发布时间：2025年02月19日

`LLM应用` `软件工程` `Docker`

> An LLM-based Agent for Reliable Docker Environment Configuration

# 摘要

> 环境配置在软件开发中至关重要，但耗时费力，尤其面对不熟悉的代码仓库时。尽管大型语言模型（LLMs）在软件工程中展现出潜力，但现有配置方法常依赖手动操作或易出错脚本，效率低下且结果不可靠。我们推出Repo2Run，首个基于LLM的自动化配置代理，能为任意Python仓库生成可执行的Dockerfile。我们攻克两大难题：让LLM代理在隔离Docker容器中完成配置，并确保成功过程准确转化为Dockerfile。为此，我们提出原子式配置合成，采用内外环境双架构加回滚机制，防止失败命令污染环境，确保配置要么全部完成，要么完全不执行。通过Dockerfile生成器，成功配置步骤可转化为可运行的Dockerfile。我们在包含420个Python仓库的基准测试中评估Repo2Run，成功率高达86.0%，远超最佳基线63.9%。

> Environment configuration is a critical yet time-consuming step in software development, especially when dealing with unfamiliar code repositories. While Large Language Models (LLMs) demonstrate the potential to accomplish software engineering tasks, existing methods for environment configuration often rely on manual efforts or fragile scripts, leading to inefficiencies and unreliable outcomes. We introduce Repo2Run, the first LLM-based agent designed to fully automate environment configuration and generate executable Dockerfiles for arbitrary Python repositories. We address two major challenges: (1) enabling the LLM agent to configure environments within isolated Docker containers, and (2) ensuring the successful configuration process is recorded and accurately transferred to a Dockerfile without error. To achieve this, we propose atomic configuration synthesis, featuring a dual-environment architecture (internal and external environment) with a rollback mechanism to prevent environment "pollution" from failed commands, guaranteeing atomic execution (execute fully or not at all) and a Dockerfile generator to transfer successful configuration steps into runnable Dockerfiles. We evaluate Repo2Run~on our proposed benchmark of 420 recent Python repositories with unit tests, where it achieves an 86.0% success rate, outperforming the best baseline by 63.9%.

[Arxiv](https://arxiv.org/abs/2502.13681)