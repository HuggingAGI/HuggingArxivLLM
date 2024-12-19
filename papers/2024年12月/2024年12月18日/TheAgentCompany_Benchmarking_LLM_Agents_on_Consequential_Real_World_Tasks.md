# TheAgentCompany：针对重要的现实世界任务对 LLM 代理展开基准测试

发布时间：2024年12月18日

`Agent` `人工智能`

> TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks

# 摘要

> 我们每天都会与计算机打交道，不管是在日常生活还是工作中，工作的诸多方面都能仅靠计算机和互联网来完成。与此同时，得益于大型语言模型（LLMs）的进步，能与周边环境交互并带来改变的人工智能代理也迅速发展起来。然而，人工智能代理在助力加速甚至自主完成工作相关任务方面表现究竟怎样？这个问题的答案对于期望在工作流程中引入人工智能的行业，以及对于经济政策去理解采用人工智能可能给劳动力市场带来的影响，都至关重要。为衡量这些 LLM 代理在执行现实世界专业任务方面的进展，在本文中，我们推出了 TheAgentCompany，这是一个用于评估以类似数字工作者的方式与世界交互的人工智能代理的可扩展基准：比如通过浏览网页、编写代码、运行程序以及与其他同事交流。我们构建了一个带有内部网站和数据的自足环境，模拟了小型软件公司的环境，并设定了可能由该公司员工执行的各类任务。我们测试了由基于封闭 API 和开放权重语言模型（LMs）驱动的基线代理，发现使用最具竞争力的代理，24%的任务能够自主完成。这为使用 LM 代理进行任务自动化勾勒出了一幅微妙的图景——在模拟真实工作场所的情境中，相当一部分较简单的任务能够自主解决，但更具难度的长期任务仍超出当前系统的能力范畴。

> We interact with computers on an everyday basis, be it in everyday life or work, and many aspects of work can be done entirely with access to a computer and the Internet. At the same time, thanks to improvements in large language models (LLMs), there has also been a rapid development in AI agents that interact with and affect change in their surrounding environments. But how performant are AI agents at helping to accelerate or even autonomously perform work-related tasks? The answer to this question has important implications for both industry looking to adopt AI into their workflows, and for economic policy to understand the effects that adoption of AI may have on the labor market. To measure the progress of these LLM agents' performance on performing real-world professional tasks, in this paper, we introduce TheAgentCompany, an extensible benchmark for evaluating AI agents that interact with the world in similar ways to those of a digital worker: by browsing the Web, writing code, running programs, and communicating with other coworkers. We build a self-contained environment with internal web sites and data that mimics a small software company environment, and create a variety of tasks that may be performed by workers in such a company. We test baseline agents powered by both closed API-based and open-weights language models (LMs), and find that with the most competitive agent, 24% of the tasks can be completed autonomously. This paints a nuanced picture on task automation with LM agents -- in a setting simulating a real workplace, a good portion of simpler tasks could be solved autonomously, but more difficult long-horizon tasks are still beyond the reach of current systems.

[Arxiv](https://arxiv.org/abs/2412.14161)