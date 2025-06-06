# 探索与迭代反馈驱动的语言代理自动化技能发现

发布时间：2025年06月04日

`Agent`

> Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback

# 摘要

> 训练大型语言模型（LLM）代理以获取必要技能并在环境中执行多样化任务，正成为实现开放性的重要手段。然而，创建技能获取所需的训练数据集面临多重挑战：手动轨迹收集耗时费力，而LLMs直接提出任务的方法往往不可行，因为它们缺乏对任务可行性的认知。此外，生成的数据可能无法提供有效学习信号，因代理通常已能良好完成所提任务。

为解决这些问题，我们为LLM驱动代理提出了一种新型自动技能发现框架EXIF，旨在提高生成目标行为的可行性，同时考虑代理能力。该方法采用"先探索"策略，通过探索代理Alice训练目标代理Bob学习环境中的关键技能。具体而言，Alice首先与环境交互，生成一个可行且基于环境的技能数据集，用于训练Bob。关键创新在于引入迭代反馈机制：Alice评估Bob表现以识别改进空间，此反馈指导Alice下轮探索，形成闭环数据生成过程。

实验结果表明，EXIF能有效发现有意义技能，并在无需人工干预情况下逐步扩展代理能力，实现显著性能提升。有趣的是，将Alice与Bob设为相同模型亦能显著提升性能，展现了EXIF构建自我演进系统的潜力。

> Training large language model (LLM) agents to acquire necessary skills and perform diverse tasks within an environment is gaining interest as a means to enable open-endedness. However, creating the training dataset for their skill acquisition faces several challenges. Manual trajectory collection requires significant human effort. Another approach, where LLMs directly propose tasks to learn, is often invalid, as the LLMs lack knowledge of which tasks are actually feasible. Moreover, the generated data may not provide a meaningful learning signal, as agents often already perform well on the proposed tasks. To address this, we propose a novel automatic skill discovery framework EXIF for LLM-powered agents, designed to improve the feasibility of generated target behaviors while accounting for the agents' capabilities. Our method adopts an exploration-first strategy by employing an exploration agent (Alice) to train the target agent (Bob) to learn essential skills in the environment. Specifically, Alice first interacts with the environment to retrospectively generate a feasible, environment-grounded skill dataset, which is then used to train Bob. Crucially, we incorporate an iterative feedback loop, where Alice evaluates Bob's performance to identify areas for improvement. This feedback then guides Alice's next round of exploration, forming a closed-loop data generation process. Experiments on Webshop and Crafter demonstrate EXIF's ability to effectively discover meaningful skills and iteratively expand the capabilities of the trained agent without any human intervention, achieving substantial performance improvements. Interestingly, we observe that setting Alice to the same model as Bob also notably improves performance, demonstrating EXIF's potential for building a self-evolving system.

[Arxiv](https://arxiv.org/abs/2506.04287)