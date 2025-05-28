# CXXCrafter: 一个基于LLM的智能体，专为自动化的C/C++开源软件构建而设计

发布时间：2025年05月27日

`LLM应用` `软件工程` `构建系统`

> CXXCrafter: An LLM-Based Agent for Automated C/C++ Open Source Software Building

# 摘要

> 项目构建在程序分析任务中扮演着关键角色，例如为静态分析生成中间表示代码或为漏洞复现准备二进制代码。然而，自动化构建C/C++项目的过程极其复杂，涉及复杂的依赖管理、多样化的构建系统、多样的工具链以及多方面的错误处理机制。因此，构建C/C++项目在实际操作中往往充满困难，阻碍了下游应用的进展。遗憾的是，关于简化C/C++项目构建的研究仍然不足。大型语言模型（LLMs）的出现为自动化软件构建提供了有前景的解决方案。基于大量语料库的训练，LLMs能够通过其理解能力统一各种构建系统，并借助隐性知识存储解决复杂错误。此外，基于LLMs的代理可以系统性地设计为与环境进行动态交互，从而有效管理动态构建问题。受到这些机遇的启发，我们首先开展了一项实证研究，以系统性地分析当前C/C++项目构建过程中的挑战。特别地，我们发现，大多数流行的C/C++项目在仅依赖默认构建系统时，平均会遇到五个错误。基于我们的研究，我们开发了一个名为CXXCrafter的自动化构建系统，专门针对上述挑战（如依赖解析）提供解决方案。我们在开源软件上的评估表明，CXXCrafter在项目构建方面达到了78%的成功率。具体来说，在Top100数据集中，有72个项目通过CXXCrafter和手动努力均能成功构建，3个项目仅能通过CXXCrafter构建，而14个项目仅能通过手动方式构建。...

> Project building is pivotal to support various program analysis tasks, such as generating intermediate rep- resentation code for static analysis and preparing binary code for vulnerability reproduction. However, automating the building process for C/C++ projects is a highly complex endeavor, involving tremendous technical challenges, such as intricate dependency management, diverse build systems, varied toolchains, and multifaceted error handling mechanisms. Consequently, building C/C++ projects often proves to be difficult in practice, hindering the progress of downstream applications. Unfortunately, research on facilitating the building of C/C++ projects remains to be inadequate. The emergence of Large Language Models (LLMs) offers promising solutions to automated software building. Trained on extensive corpora, LLMs can help unify diverse build systems through their comprehension capabilities and address complex errors by leveraging tacit knowledge storage. Moreover, LLM-based agents can be systematically designed to dynamically interact with the environment, effectively managing dynamic building issues. Motivated by these opportunities, we first conduct an empirical study to systematically analyze the current challenges in the C/C++ project building process. Particularly, we observe that most popular C/C++ projects encounter an average of five errors when relying solely on the default build systems. Based on our study, we develop an automated build system called CXXCrafter to specifically address the above-mentioned challenges, such as dependency resolution. Our evaluation on open-source software demonstrates that CXXCrafter achieves a success rate of 78% in project building. Specifically, among the Top100 dataset, 72 projects are built successfully by both CXXCrafter and manual efforts, 3 by CXXCrafter only, and 14 manually only. ...

[Arxiv](https://arxiv.org/abs/2505.21069)