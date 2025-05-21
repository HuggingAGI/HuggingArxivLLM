# # 摘要  
一种结合强化学习子系统改进的智能体系统，用于解析表单类文档

发布时间：2025年05月16日

`Agent` `文档处理`

> An agentic system with reinforcement-learned subsystem improvements for parsing form-like documents

# 摘要

> 从发票、采购订单、账单和财务文件等表格文档中提取字母数字数据，传统方法往往依赖视觉（OCR）技术和学习算法，或采用一体化流程，但这些方法的改进空间有限。我们提出了一种基于大型语言模型（LLM）智能体和强化学习（RL）驱动智能体的创新系统，旨在实现LLM推理不确定性下的持续、自我改进的自动化提取。我们的研究揭示了传统LLM提取方法的局限性，并引入了一种模块化、多智能体框架。通过任务特定提示和奖励与惩罚策略的强化学习政策，引导元提示智能体从过去错误中学习，优化基于提示的执行智能体。这一自适应纠错系统能够处理多样化的文档、文件格式、布局和LLM，目标是无需人工干预，实现精准信息提取的自动化。在SOIRE和CORD两个基准数据集上的实验结果表明，该智能体AI框架展现出显著潜力。

> Extracting alphanumeric data from form-like documents such as invoices, purchase orders, bills, and financial documents is often performed via vision (OCR) and learning algorithms or monolithic pipelines with limited potential for systemic improvements. We propose an agentic AI system that leverages Large Language Model (LLM) agents and a reinforcement learning (RL) driver agent to automate consistent, self-improving extraction under LLM inference uncertainty. Our work highlights the limitations of monolithic LLM-based extraction and introduces a modular, multi-agent framework with task-specific prompts and an RL policy of rewards and penalties to guide a meta-prompting agent to learn from past errors and improve prompt-based actor agents. This self-corrective adaptive system handles diverse documents, file formats, layouts, and LLMs, aiming to automate accurate information extraction without the need for human intervention. Results as reported on two benchmark datasets of SOIRE, and CORD, are promising for the agentic AI framework.

[Arxiv](https://arxiv.org/abs/2505.13504)