# 大型语言模型中的系统提示提取攻击及其防御措施

发布时间：2025年05月27日

`LLM应用` `人工智能`

> System Prompt Extraction Attacks and Defenses in Large Language Models

# 摘要

> 在大型语言模型 (LLMs) 中，系统提示 (system prompt) 对指导模型行为和生成响应起着关键作用。由于其包含私有配置细节、用户角色和操作指令，系统提示已成为新兴攻击目标。近期研究表明，通过精心设计的查询，LLM 系统提示极易遭受提取攻击，引发严重隐私和安全担忧。尽管威胁日益严重，但目前尚缺乏系统性的研究来探讨系统提示提取攻击及其防御方法。本文提出了一种全面的框架 SPE-LLM，旨在系统性地评估 LLM 中的系统提示提取攻击和防御措施。首先，我们设计了一组新颖的对抗查询，能够有效提取先进 (SOTA) LLM 的系统提示，展示了 LLM 系统提示提取攻击的严重风险。其次，我们提出了三种防御技术，以缓解 LLM 中的系统提示提取攻击，为安全部署 LLM 提供了实用解决方案。最后，我们引入了一组严谨的评估指标，准确量化 LLM 中系统提示提取攻击的严重性，并在多个基准数据集上进行了全面实验，验证了我们提出的 SPE-LLM 框架的有效性。

> The system prompt in Large Language Models (LLMs) plays a pivotal role in guiding model behavior and response generation. Often containing private configuration details, user roles, and operational instructions, the system prompt has become an emerging attack target. Recent studies have shown that LLM system prompts are highly susceptible to extraction attacks through meticulously designed queries, raising significant privacy and security concerns. Despite the growing threat, there is a lack of systematic studies of system prompt extraction attacks and defenses. In this paper, we present a comprehensive framework, SPE-LLM, to systematically evaluate System Prompt Extraction attacks and defenses in LLMs. First, we design a set of novel adversarial queries that effectively extract system prompts in state-of-the-art (SOTA) LLMs, demonstrating the severe risks of LLM system prompt extraction attacks. Second, we propose three defense techniques to mitigate system prompt extraction attacks in LLMs, providing practical solutions for secure LLM deployments. Third, we introduce a set of rigorous evaluation metrics to accurately quantify the severity of system prompt extraction attacks in LLMs and conduct comprehensive experiments across multiple benchmark datasets, which validates the efficacy of our proposed SPE-LLM framework.

[Arxiv](https://arxiv.org/abs/2505.23817)