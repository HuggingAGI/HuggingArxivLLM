# EHR-MCP：大型语言模型基于模型上下文协议的临床信息检索真实世界评测

发布时间：2025年09月19日

`Agent` `医疗健康`

> EHR-MCP: Real-world Evaluation of Clinical Information Retrieval by Large Language Models via Model Context Protocol

# 摘要

> Background: 大型语言模型（LLMs）在医学领域潜力巨大，但因电子健康记录（EHR）系统的访问限制，其在医院的落地应用受限。模型上下文协议（MCP）则为LLMs与外部工具的集成提供了可能。
  Objective: 验证通过MCP连接EHR数据库的LLM能否在真实医院环境中自主获取临床相关信息。
  Methods: 我们构建了EHR-MCP——一套与医院EHR数据库集成的定制MCP工具框架，并通过LangGraph ReAct智能体调用GPT-4.1与之交互。测试任务共六项，均源自感染控制团队（ICT）的实际应用场景；同时对ICT会议中讨论的八例患者进行回顾性分析，并评估其与医生制定的金标准的一致性。
  Results: LLM能稳定选择并执行正确的MCP工具。除两项任务外，其余任务准确率接近完美；而在需进行时间依赖性计算的复杂任务中，性能表现稍差。多数错误源于参数设置不当或对工具结果的误读。EHR-MCP的响应可靠，但冗长重复的数据可能导致上下文窗口溢出。
  Conclusions: 在真实医院环境中，LLMs可借助MCP工具从EHR中提取临床数据，在简单任务中表现近乎完美，但复杂任务仍面临挑战。EHR-MCP为安全稳定的数据访问搭建了基础架构，有望成为医院AI智能体的核心支撑。未来研究需突破数据检索的局限，向推理、生成及临床影响评估拓展，为生成式AI融入临床实践奠定基础。

> Background: Large language models (LLMs) show promise in medicine, but their deployment in hospitals is limited by restricted access to electronic health record (EHR) systems. The Model Context Protocol (MCP) enables integration between LLMs and external tools.
  Objective: To evaluate whether an LLM connected to an EHR database via MCP can autonomously retrieve clinically relevant information in a real hospital setting.
  Methods: We developed EHR-MCP, a framework of custom MCP tools integrated with the hospital EHR database, and used GPT-4.1 through a LangGraph ReAct agent to interact with it. Six tasks were tested, derived from use cases of the infection control team (ICT). Eight patients discussed at ICT conferences were retrospectively analyzed. Agreement with physician-generated gold standards was measured.
  Results: The LLM consistently selected and executed the correct MCP tools. Except for two tasks, all tasks achieved near-perfect accuracy. Performance was lower in the complex task requiring time-dependent calculations. Most errors arose from incorrect arguments or misinterpretation of tool results. Responses from EHR-MCP were reliable, though long and repetitive data risked exceeding the context window.
  Conclusions: LLMs can retrieve clinical data from an EHR via MCP tools in a real hospital setting, achieving near-perfect performance in simple tasks while highlighting challenges in complex ones. EHR-MCP provides an infrastructure for secure, consistent data access and may serve as a foundation for hospital AI agents. Future work should extend beyond retrieval to reasoning, generation, and clinical impact assessment, paving the way for effective integration of generative AI into clinical practice.

[Arxiv](https://arxiv.org/abs/2509.15957)