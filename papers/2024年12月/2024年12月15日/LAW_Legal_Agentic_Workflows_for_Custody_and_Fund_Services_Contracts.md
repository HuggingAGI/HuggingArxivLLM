# LAW: 托管与基金服务合同的法律智能体工作流

发布时间：2024年12月15日

`Agent

理由：这篇论文介绍了一个名为LAW的系统，该系统采用模块化设计，通过调用领域专用工具和文本代理来响应用户查询。这种设计涉及到多个专业代理的整合，符合“Agent”分类的定义，即涉及多个代理或模块协同工作的系统。` `金融服务`

> LAW: Legal Agentic Workflows for Custody and Fund Services Contracts

# 摘要

> 托管和基金服务领域的法律合同涉及关键条款，如提供方责任、费用结构和赔偿权利。然而，现成的LLM难以处理这些合同，原因在于文本冗长、上下文窗口有限以及法律术语复杂。为此，我们推出了LAW（托管和基金服务合同的法律代理工作流）。LAW采用模块化设计，通过调用领域专用工具和文本代理来响应用户查询。实验表明，LAW通过整合多个专业代理和工具，显著优于基线模型，尤其在计算合同终止日期等复杂任务上，表现提升了92.9个百分点。此外，LAW通过复用领域专用工具，提供了一种比传统微调法律LLM更具成本效益的解决方案。

> Legal contracts in the custody and fund services domain govern critical aspects such as key provider responsibilities, fee schedules, and indemnification rights. However, it is challenging for an off-the-shelf Large Language Model (LLM) to ingest these contracts due to the lengthy unstructured streams of text, limited LLM context windows, and complex legal jargon. To address these challenges, we introduce LAW (Legal Agentic Workflows for Custody and Fund Services Contracts). LAW features a modular design that responds to user queries by orchestrating a suite of domain-specific tools and text agents. Our experiments demonstrate that LAW, by integrating multiple specialized agents and tools, significantly outperforms the baseline. LAW excels particularly in complex tasks such as calculating a contract's termination date, surpassing the baseline by 92.9% points. Furthermore, LAW offers a cost-effective alternative to traditional fine-tuned legal LLMs by leveraging reusable, domain-specific tools.

[Arxiv](https://arxiv.org/abs/2412.11063)