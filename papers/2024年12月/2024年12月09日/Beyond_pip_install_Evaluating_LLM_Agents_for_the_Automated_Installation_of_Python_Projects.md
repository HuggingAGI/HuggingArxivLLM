# “超越 pip install：评估用于 Python 项目自动安装的 LLM 代理”

发布时间：2024年12月09日

`Agent` `软件工程` `软件开发`

> Beyond pip install: Evaluating LLM Agents for the Automated Installation of Python Projects

# 摘要

> 近来，许多研究都提议采用基于大型语言模型（LLM）的代理来执行“存储库级别”的任务，这类任务大致被定义为一系列范围超过单个文件的任务。这让人猜测，对这些存储库级任务的编排或许能催生几乎无需人类干预就能执行任务的软件工程代理。然而，在这个自主软件工程代理所需执行的一系列任务中，我们指出有一项重要任务缺失，即通过安装其他存储库来满足项目级依赖。为探究此存储库级别安装任务的可行性，我们引入了一个从 40 个开源 Python 项目中精心挑选的存储库安装任务基准，其中涵盖了每个目标存储库的真实安装流程。此外，我们提出了 Installamatic 代理，其旨在通过从存储库中的文档搜索相关指令来执行并验证给定存储库的安装。实证实验显示，我们的代理至少有十分之一的几率能够自动安装 55%的所研究存储库。通过进一步分析，我们明确了代理无法安装存储库的常见原因，探讨了设计和实现此类代理所面临的挑战，并思考了这样的代理可能给开发人员带来的影响。

> Many works have recently proposed the use of Large Language Model (LLM) based agents for performing `repository level' tasks, loosely defined as a set of tasks whose scopes are greater than a single file. This has led to speculation that the orchestration of these repository-level tasks could lead to software engineering agents capable of performing almost independently of human intervention. However, of the suite of tasks that would need to be performed by this autonomous software engineering agent, we argue that one important task is missing, which is to fulfil project level dependency by installing other repositories. To investigate the feasibility of this repository level installation task, we introduce a benchmark of of repository installation tasks curated from 40 open source Python projects, which includes a ground truth installation process for each target repository. Further, we propose Installamatic, an agent which aims to perform and verify the installation of a given repository by searching for relevant instructions from documentation in the repository. Empirical experiments reveal that that 55% of the studied repositories can be automatically installed by our agent at least one out of ten times. Through further analysis, we identify the common causes for our agent's inability to install a repository, discuss the challenges faced in the design and implementation of such an agent and consider the implications that such an agent could have for developers.

[Arxiv](https://arxiv.org/abs/2412.06294)