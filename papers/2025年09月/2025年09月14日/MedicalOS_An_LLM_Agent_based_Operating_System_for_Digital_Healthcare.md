# MedicalOS：基于LLM智能体的数字医疗操作系统

发布时间：2025年09月14日

`Agent` `医疗健康`

> MedicalOS: An LLM Agent based Operating System for Digital Healthcare

# 摘要

> 数十年来，电子健康记录等数字健康技术的进步极大地简化了常规临床流程。但大多数这类系统仍存在学习使用门槛高的问题：临床医生常需应对多工具管理、为每位患者重复手动操作、在复杂界面树中查找功能等负担，大量时间耗费在行政管理上，而非直接照护患者。近期，基于大型语言模型（LLM）的智能体在编码与计算机操作领域展现出卓越能力，揭示了人类与操作系统及软件交互的新范式——无需直接操作，只需通过自然语言指令智能体即可实现。这一转变催生了对抽象层（即智能体-计算机接口）的需求，该接口能将人类语言转化为机器可执行命令。然而在数字医疗领域，这需要更具针对性的领域抽象层，严格遵循可信临床指南与操作标准，以确保安全性、透明度和合规性。为此，我们提出	extbf{MedicalOS}——一个统一的基于智能体的操作系统，专门作为医疗领域的特定抽象层。它能将人类指令转化为预定义的数字医疗命令（如患者查询、病史检索、检查管理、报告生成、转诊、治疗规划等），并通过机器语言（如Python、API、MCP、Linux）封装为现成工具。我们在22个专科的214个患者病例上对MedicalOS进行实证验证，结果显示其具备高诊断准确性与可信度，能生成临床合理的检查请求，并可一致输出结构化报告与用药建议。这些结果表明，MedicalOS是推进临床实践工作流自动化的可靠且可扩展的基础。

> Decades' advances in digital health technologies, such as electronic health records, have largely streamlined routine clinical processes. Yet, most these systems are still hard to learn and use: Clinicians often face the burden of managing multiple tools, repeating manual actions for each patient, navigating complicated UI trees to locate functions, and spending significant time on administration instead of caring for patients. The recent rise of large language model (LLM) based agents demonstrates exceptional capability in coding and computer operation, revealing the potential for humans to interact with operating systems and software not by direct manipulation, but by instructing agents through natural language. This shift highlights the need for an abstraction layer, an agent-computer interface, that translates human language into machine-executable commands. In digital healthcare, however, requires a more domain-specific abstractions that strictly follow trusted clinical guidelines and procedural standards to ensure safety, transparency, and compliance. To address this need, we present \textbf{MedicalOS}, a unified agent-based operational system designed as such a domain-specific abstract layer for healthcare. It translates human instructions into pre-defined digital healthcare commands, such as patient inquiry, history retrieval, exam management, report generation, referrals, treatment planning, that we wrapped as off-the-shelf tools using machine languages (e.g., Python, APIs, MCP, Linux). We empirically validate MedicalOS on 214 patient cases across 22 specialties, demonstrating high diagnostic accuracy and confidence, clinically sound examination requests, and consistent generation of structured reports and medication recommendations. These results highlight MedicalOS as a trustworthy and scalable foundation for advancing workflow automation in clinical practice.

[Arxiv](https://arxiv.org/abs/2509.11507)